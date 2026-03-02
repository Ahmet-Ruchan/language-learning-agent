# Build a Language‑Learning Agent with OpenAI, LangGraph, Ollama & MCP

A hands-on project demonstrating how to build an AI-powered language-learning agent by combining:

- **OpenAI** – cloud LLM for high-quality language generation and evaluation
- **LangGraph** – stateful agent orchestration with graph-based control flow
- **Ollama** – local LLM inference for offline/private usage
- **MCP (Model Context Protocol)** – standardized tool and context integration

## Tech Stack

| Component | Purpose |
|-----------|---------|
| OpenAI API | Cloud-based LLM (GPT-4o) |
| LangGraph | Agent graph & state management |
| Ollama | Local model serving |
| MCP | Tool protocol & context injection |
| Python 3.13 | Runtime |

## Getting Started

```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the agent
python main.py
```

## Environment Variables

```
OPENAI_API_KEY=your_openai_api_key
```
