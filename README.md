# lca-lc

A small AI engineering workspace containing an experimental local chain/agent project.

This repository contains a minimal runner plus several agent development notebooks used while exploring local AI agents, memory, and tools integration.

**Quick overview**

- **Purpose**: House experiments and a lightweight runner for agent workflows and Local LLM chaining.
- **Language**: Python
- **Entry point**: `src/main.py`
- **Notebooks**: interactive agent experiments are in `src/agents/`
- **Dependencies**: see `pyproject.toml` for project dependencies and packaging information.

**Repository structure**

- [src/main.py](src/main.py) — main runner for the project
- [src/agents/](src/agents/) — interactive Jupyter notebooks (Chat, ChefAgent, Memory, Tools)
- pyproject.toml — Python packaging and dependency metadata

Getting started

1. Install dependencies (use the tool you prefer; the project uses `pyproject.toml`):

```bash
pip install -e .
# or use poetry: `poetry install`
```

2. Run the main script (subject to how `src/main.py` is implemented):

```bash
python -m src.main
```

3. Open and run the notebooks in `src/agents/` using Jupyter or VS Code's notebook support:

```bash
jupyter lab src/agents
```





