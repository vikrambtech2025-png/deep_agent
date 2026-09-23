# Deep Agent

Experimental agentic-AI workbench — a **LangChain** demo notebook that combines **Tavily web search** with an OpenAI LLM into a research agent.

## Contents (`DEEP/`)

| File | Description |
|---|---|
| `demoagent.ipynb` | Step-by-step agent demo — web-search tool definition (Tavily), LLM wiring (OpenAI via `langchain-openai`), and the tool-calling loop. |
| `main.py` | Package scaffold entrypoint. |
| `pyproject.toml`, `uv.lock` | uv-managed project metadata. |
| `requirements.txt` | Runtime dependencies (langchain, deepagents, langchain-openai, tavily-python, ipykernel). |

## Setup

```bash
pip install -r requirements.txt      # or: uv sync
```

Set `OPENAI_API_KEY` and `TAVILY_API_KEY` in a `.env` file, then open `DEEP/demoagent.ipynb`.

## License

No license specified — for learning/reference use.