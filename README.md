# Hands-On AI Agents, Level 2: RAG, MCP and Multi-Agent Systems

**Free code companion** for the book by Exobean Engineering: the book's code, a notebook for every lesson, and self-grading exercises with answers.

## [⬇ Download the code companion](https://github.com/exobean/ai-agents-level2/releases/latest/download/agentlab-companion.zip)

`agentlab-companion.zip`. No account or sign-in needed.

## Set up in four steps

1. Unzip the file you downloaded.
2. Install [uv](https://docs.astral.sh/uv/), a free Python tool (it also installs Python for you).
3. Open a terminal inside the unzipped folder and run `uv sync`.
4. Check everything works: `uv run python -m shopassist.doctor`

Grade a lesson's exercises any time: `uv run pytest exercises/<lesson>`. The book explains every step with pictures.

## Browser only? Use Google Colab

Click **Open in Colab** next to your lesson, then run the first cell. It downloads the companion for you; then run the rest in order.

## Lesson notebooks

| Lesson | Notebook |
| --- | --- |
| 1.1 Embeddings: meaning as a map | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m01_l01_embeddings.ipynb) |
| 1.2 Chunking documents | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m01_l02_chunking.ipynb) |
| 1.3 Vector search | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m01_l03_search.ipynb) |
| 1.4 RAG: answers with sources | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m01_l04_rag.ipynb) |
| 1.5 Measuring RAG quality | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m01_l05_rag_quality.ipynb) |
| 2.1 Summaries: short-term memory that fits | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m02_l01_summaries.ipynb) |
| 2.2 Long-term memory | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m02_l02_longterm.ipynb) |
| 2.3 State machines: guard rails for agents | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m02_l03_state.ipynb) |
| 2.4 Saving and resuming sessions | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m02_l04_persist.ipynb) |
| 3.1 MCP: one plug for every tool | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m03_l01_mcp.ipynb) |
| 3.2 Build an MCP server | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m03_l02_server.ipynb) |
| 3.3 An agent with MCP tools | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m03_l03_client.ipynb) |
| 3.4 Using MCP servers safely | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m03_l04_mcp_safety.ipynb) |
| 4.1 Workflows, agents and prompt chaining | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m04_l01_chaining.ipynb) |
| 4.2 Routing | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m04_l02_routing.ipynb) |
| 4.3 Parallel steps: sectioning and voting | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m04_l03_parallel.ipynb) |
| 4.4 Orchestrator and workers | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m04_l04_orchestrator.ipynb) |
| 4.5 Evaluator and optimizer; choosing a pattern | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m04_l05_evaluator.ipynb) |
| 5.1 Agents that hand off | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m05_l01_handoffs.ipynb) |
| 5.2 A supervisor agent | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m05_l02_supervisor.ipynb) |
| 5.3 How multi-agent systems fail | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m05_l03_failures.ipynb) |
| 5.4 Lab: evaluate the team | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m05_l04_team_lab.ipynb) |
| 6.1 How a coding agent works | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m06_l01_coding_agent.ipynb) |
| 6.2 A safe workspace for coding agents | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m06_l02_sandbox.ipynb) |
| 6.3 Reviewing AI-written changes | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m06_l03_review.ipynb) |
| 7.1 Capstone: assemble ShopAssist 2.0 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m07_l01_assemble.ipynb) |
| 7.2 Capstone: the release scorecard | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m07_l02_scorecard.ipynb) |
| 7.3 Capstone: ship it as an MCP tool | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level2/blob/main/notebooks/m07_l03_ship.ipynb) |

## Licence

Copyright 2026 Exobean Engineering. Free for your own learning and projects; see `LICENSE.txt`. For learning purposes only.
