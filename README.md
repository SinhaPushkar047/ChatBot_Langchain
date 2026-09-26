# Phoenix AI --- Chatbot

### Your AI-powered conversation companion

A conversational AI chatbot built with **LangChain**, **Hugging Face**,
and **Streamlit**.

[**Launch the Live App**](https://phoenix-ai-langchain.streamlit.app/) ·
[View Source Code](https://github.com/SinhaPushkar047/ChatBot_Langchain)
:::

------------------------------------------------------------------------

## About the Project

**Phoenix AI** is a web-based chatbot that lets you ask questions and
interact with an AI language model through a clean, chat-style
interface. It brings together LangChain's LLM integration capabilities
and Streamlit's interactive UI to create an accessible conversational
experience.

> **Try it now:**
> [phoenix-ai-langchain.streamlit.app](https://phoenix-ai-langchain.streamlit.app/)

## Features

-   **Interactive chat interface** --- Ask questions and receive
    AI-generated responses.
-   **Conversation history** --- Keep track of messages during your chat
    session.
-   **LLM integration** --- Connects to a language model through
    LangChain and Hugging Face.
-   **Custom interface styling** --- CSS-powered visual design.
-   **Web-based experience** --- Access the chatbot from your browser
    without setting up the project locally.

## Built With

  Technology      Role
  --------------- ----------------------------------------
  Python          Core application language
  Streamlit       Interactive web interface
  LangChain       LLM orchestration and chat integration
  Hugging Face    Model access and inference
  python-dotenv   Environment-variable configuration

## Project Structure

``` text
ChatBot_Langchain/
├── ChatBot_Streamlit.py   # Main application
├── style.css              # Custom styles
├── requirements.txt       # Python dependencies
├── .gitignore             # Git exclusions
├── .env                   # Local secrets (not committed)
└── README.md
```

## Run Locally

### 1. Clone the repository

``` bash
git clone https://github.com/SinhaPushkar047/ChatBot_Langchain.git
cd ChatBot_Langchain
```

### 2. Create a virtual environment

**Windows PowerShell:**

``` powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

``` bash
python -m pip install -r requirements.txt
```

### 4. Configure your API token

Create a `.env` file in the project root and add the environment
variable your application expects.

Example (replace the variable name if your code uses a different one):

``` env
HF_TOKEN=your_huggingface_token
```

Keep your token private. Never commit `.env` or paste API credentials
into source code.

### 5. Launch the app

``` bash
python -m streamlit run ChatBot_Streamlit.py
```

Open the local URL displayed in your terminal.

## Deployment

The app is deployed on Streamlit Community Cloud:

**[Open Phoenix AI
Chatbot](https://phoenix-ai-langchain.streamlit.app/)**

## Security

-   Keep API keys and tokens in environment variables or the hosting
    platform's Secrets settings.
-   Ensure `.env` is listed in `.gitignore`.
-   Never publish credentials in your repository, README, or
    screenshots.

## License

See the [`LICENSE`](LICENSE) file for licensing information.

------------------------------------------------------------------------
