# AI Researcher
A simple AI Agent using Deepseek, LangGraph, and Streamlit to find results from the web that matches the user's query and give a summarized answer based on those results.
Tavily is an AI-powered web **search** **API** that helps LLMs (like GPT) retrieve **real-time information** from the internet.

# Pre-requisites
Install Ollama on your local machine from the [official website](https://ollama.com/). And then pull the Deepseek model:

```bash
ollama pull deepseek-r1:1.5b
```

Install the dependencies using pip:

```bash
pip install -r requirements.txt
```

# Run
Run the Streamlit app:

```bash
streamlit run ai_researcher.py
```
