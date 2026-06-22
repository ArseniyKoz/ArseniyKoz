[Русский](./README.md) | [English](./README.en.md)

# Arseniy Kozhin

LLM/RAG Engineer. I own product logic and quality for an agentic RAG backend: agent behavior, tool routing, retrieval, final answers, sources, evals, and observability.

I currently work in the GenAI Lab at NPK "Electrostal". My main focus is RuCortex: a private FastAPI backend for RAG/agent workflows with Qdrant, OpenWebUI, LiteLLM, Langfuse, Docker, and benchmark tooling.

## Engineering Focus

- **Agentic RAG:** agent loop, retrieval orchestration, query rewrite, RAG search, document fetch, tool calling, streaming statuses, sources/citations, OpenWebUI integration.
- **Eval / observability:** benchmark datasets, run profiles, Langfuse traces/datasets/scores, release-aware regression checks, and RCA for agent and RAG quality regressions.
- **Backend / inference:** FastAPI, Qdrant, SSE streaming, Docker, LiteLLM routing, query service boundaries, and local experiments with vLLM/llama.cpp/Ollama-compatible inference.

## Selected Projects

| Project | What it proves | Stack |
|---|---|---|
| RuCortex / backend_pipeline (private) | Agentic RAG backend: ingestion/query API, OpenWebUI adapter, tool-based agent loop, streaming, sources, and Langfuse tracing. My scope is agent logic, answer quality, eval/bench, and change diagnostics. | Python, FastAPI, Qdrant, Docker, OpenWebUI, LiteLLM, Langfuse, SSE |
| RuCortex benchmark/eval loop | Evaluation loop for agentic RAG and direct RAG baseline: CLI/API/UI, profiles, Langfuse datasets/traces/scores, release_id, profile gates, compare, and RCA buckets. | Python, PostgreSQL, Langfuse, pytest, Node tests, browser UI |
| [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) | Dev-only HTTP MCP sidecar: `code_run` backed by persistent Jupyter kernels, sessions, timeouts, output caps, artifact resources, and result bundles. A development helper, not a sandbox for untrusted code. | Python, MCP/FastMCP, Jupyter, Starlette/Uvicorn, Pydantic, pytest |
| [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench) | Research bench for comparing SMOTE variants: reproducible experiments, quality metrics, and result visualization. | Python, scikit-learn, imbalanced-learn, CatBoost, XGBoost |
| GAN metrics research | Research on GAN quality metrics and OCR-oriented evaluation; later written up as a student scientific conference publication. | Python, PyTorch, NumPy, Pandas |

Earlier ML projects and coursework experiments are part of my history, but I do not place them next to my current RAG/eval/backend work.

## Stack

**LLM/RAG:** agentic RAG, ReAct-style loops, tool routing, query rewrite, citations, MCP, OpenWebUI, LiteLLM, Langfuse.

**Backend:** Python, FastAPI, Qdrant, PostgreSQL, Redis, Docker, REST API, SSE/streaming, pytest.

**ML/data:** PyTorch, scikit-learn, NumPy, Pandas, CatBoost, XGBoost, ClearML, Matplotlib, Seaborn.

**Tools:** Git, Linux basics, SQL, Java, C++, LaTeX.

## Experience and Education

- **LLM Engineer, GenAI Lab, NPK "Electrostal"** - 2025 - present.
- **Java Developer Intern, SberTech** - February 2024 - August 2024.
- **BSc in Applied Mathematics, Vologda State University** - 2022 - 2026.

## Achievements

- ICPC: Northern Eurasia semifinal diploma, 2nd degree (2025).
- ICPC: quarterfinal diploma, 2nd degree (2025).
- Sber hackathon: 2nd place in the Data Science track (2024).
- Scientific publication on GAN quality metrics for text recognition (2025).

## Contacts

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
