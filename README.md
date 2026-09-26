# FDE-2 · ARGUS

Project 2 of the FDE Agent Engineering Bootcamp (Module 3: Production Agentic RAG).

## Contents

| Path | What |
|---|---|
| [`notebooks/001_agentic_router.ipynb`](notebooks/001_agentic_router.ipynb) | Agentic router assignment — Part 1: sub-query division; Bonus: role-aware semantic cache with audit log. Executed end to end; runs on Colab. |
| [`src/moment_rag/`](src/moment_rag/) | Semantic search → Moment search over one YouTube transcript: a baseline fixed-chunk RAG and a moment-level RAG modelled on the course's [Moment RAG](https://github.com/hamzafarooq/multi-agent-course/tree/main/modules/Module_3_Production_Agentic_RAG_AI_Systems/Moment_RAG) *(in progress)* |

## Running

```bash
uv sync                    # Python 3.12, dependencies from uv.lock
cp .env.example .env       # add OPENAI_API_KEY
```
