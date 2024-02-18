# Chat with Multiple PDF app

To create a new enviroment in conda, with python 3.11.0 version

```bash-conda
 conda create --prefix=.venv python=3.11.0
```

To activate a enviroment created

```bash-conda
conda C:\path\to\project\.venv
```

Install dependencies (in Feb 16h 2024 faiss-cpu only works in conda global env for windows)

```bash-conda
conda install --file requirements.txt
```

> Note: To fix faiss-cpu error: [Install SWIG on Windows](https://www.dev2qa.com/how-to-install-swig-on-macos-linux-and-windows/#3_Install_Swig_On_Windows)

> Needs to install Ollama for chatbot
> https://python.langchain.com/docs/integrations/chat/ollama
> https://ollama.com/download/windows

## Env structure

```env
OPENAI_API_KEY=
HUGGINGFACEHUB_API_TOKEN=
```
