[Русский](./README.md) | [English](./README.en.md)

# Arseniy Kozhin

Agent Engineer/Researcher. I own product logic and quality for an agentic backend: agent behavior, tool routing, retrieval, final answers, sources, evals, and observability.

I currently work in the GenAI Lab at NPK "Electrostal". My main focus is RuCortex: a private FastAPI backend for RAG/agent workflows with Qdrant, OpenWebUI, LiteLLM, Langfuse, Docker, and benchmark tooling.

## Engineering Focus

**Agent core / harness.** I work on the agentic backend logic: how the agent builds context, chooses tools, calls `query_rewrite`, `rag_search`, and `document_fetch`, streams status updates, and returns answers with sources. My scope is the full behavior loop, not just individual tools: prompt contracts, tool routing, agent step limits, OpenWebUI integration, and the developer harness used to test and debug that behavior.

**Eval / observation.** I build the loop that shows whether the agent became better or worse after a change. This includes bench datasets, run profiles, regression checks, Langfuse traces/scores, run comparison, and RCA for failures such as wrong tool paths, weak retrieval, poor groundedness, latency, or runtime errors. The goal is to make answer quality observable instead of judging it by feel.

**LLM inference.** I work with how models are connected and behave inside the backend: LiteLLM routing, streaming, TTFT, token usage, prompt-cache signals, and local experiments with vLLM/llama.cpp/Ollama-compatible inference. The point is to understand not only which model answers, but how latency, streaming behavior, and routing affect the agent workflow.

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

**Languages and fundamentals**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Agent harness**

![OpenWebUI](https://img.shields.io/badge/OpenWebUI-111111?style=for-the-badge)
![LiteLLM](https://img.shields.io/badge/LiteLLM-2E6BFF?style=for-the-badge)
![Langfuse](https://img.shields.io/badge/Langfuse-111111?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-5C2D91?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![vLLM](https://img.shields.io/badge/vLLM-2E7D32?style=for-the-badge)

**Backend / Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge)
![SSE](https://img.shields.io/badge/SSE-FF6F00?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**ML / Data Science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-1F8ACB?style=for-the-badge)
![ClearML](https://img.shields.io/badge/ClearML-00AEEF?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

**Tools and environment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

## Experience and Education

- **LLM Engineer, GenAI Lab, NPK "Electrostal"** - 2025 - present.
- **BSc in Applied Mathematics, Vologda State University** - 2022 - 2026.

## Achievements

- ICPC: Northern Eurasia semifinal diploma, 2nd degree (2025).
- ICPC: quarterfinal diploma, 2nd degree (2025).
- Scientific publication on GAN quality metrics for text recognition (2025).
- Sber hackathon: 2nd place in the Data Science track (2024).

## Contacts

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
