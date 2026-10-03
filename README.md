# LangChain Tool Agents

LangChain agents that call tools: a weather agent with full chat history and LangSmith tracing, and a beginner multi-tool AI assistant.

## Contents

| File | What it is |
|------|------------|
| `notebooks/Beginner_Multi_Tool_AI_Assistant_1.ipynb` | 🧠 Multi-Tool AI Assistant |
| `notebooks/LangChain_Weather_Agent_with_Full_Chat_History_and_LangSmith_Tracing_1_1.ipynb` | LangChain Weather Agent with Full Chat-History Memory and LangSmith Tracing |

## Getting started

```bash
git clone https://github.com/<your-username>/langchain-tool-agents.git
cd langchain-tool-agents
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pip install jupyterlab
jupyter lab   # then open a notebook in notebooks/
```

## Notes

- Copy `.env.example` to `.env` and add your own API keys. Never commit real keys.
