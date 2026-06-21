# Deep Agent LangChain

Deep agents demo built with LangChain, DeepAgents, and Streamlit.

## Setup

1. Install [uv](https://docs.astral.sh/uv/).
2. Create the virtual environment and install dependencies:

```powershell
uv sync
```

3. Copy the example env file and add your API keys:

```powershell
copy Deep-agents-With-Langchain\deepagentsdemo\.env.example Deep-agents-With-Langchain\deepagentsdemo\.env
```

Required keys:

- `OPENAI_API_KEY`
- `GROQ_API_KEY` (optional, for Groq models)
- `TAVILY_API_KEY`
- `GOOGLE_API_KEY` (optional)

## Run the Streamlit app

```powershell
uv run streamlit run Deep-agents-With-Langchain\streamlit_app.py
```

Open http://localhost:8501 in your browser.

## Project layout

- `Deep-agents-With-Langchain/streamlit_app.py` — Streamlit chatbot demo
- `Deep-agents-With-Langchain/deepagentsdemo/` — notebooks, skills, and demo assets

## Security

Never commit `.env` files or API keys. Use `.env.example` as a template only.

<img width="1892" height="840" alt="image" src="https://github.com/user-attachments/assets/548f2578-b2cf-4539-a71e-8ff2e62c3508" />
<img width="1845" height="537" alt="image" src="https://github.com/user-attachments/assets/91d8d99f-09d2-4bea-b9b1-b50108ebbd2a" />
<img width="1330" height="650" alt="image" src="https://github.com/user-attachments/assets/c6b41bea-33c6-4a96-9a7c-bb237c73d2c6" />



