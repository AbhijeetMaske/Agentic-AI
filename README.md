# Agentic AI

A small Python project and learning workspace for agentic AI development using LangChain and related tools.

## Overview

This repository contains a minimal Python package plus a set of LangChain notebooks designed to explore agentic workflows, model integration, tools, and message handling.

## Contents

- `main.py` — basic entrypoint with a sample starter function.
- `pyproject.toml` — package metadata and dependency definitions.
- `requirements.txt` — pinned project dependencies.
- `langchain/` — notebook examples that demonstrate core concepts and techniques.

## Notebooks

The notebook collection includes:

1. `1-langChainIntro.ipynb` — introduction to LangChain concepts.
2. `2-model_integration_openAI.ipynb` — examples of connecting with OpenAI models.
3. `3-tools.ipynb` — tool usage and integration patterns.
4. `4-messages.ipynb` — message handling and prompt structure.

## Requirements

- Python 3.12 or newer
- A virtual environment is recommended

## Installation

```bash
python -m venv .venv
.\.venv\Scripts\activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

If you prefer to install via `pyproject.toml`:

```bash
python -m pip install --upgrade pip
python -m pip install .
```

## Running the Project

Run the simple starter script with:

```bash
python main.py
```

## Notes

- The project is primarily a study/demo workspace rather than a production application.
- Use the notebooks to explore LangChain workflows interactively.

## License

This repository does not include a specific license file. Add a license if you plan to share or reuse the code publicly.
