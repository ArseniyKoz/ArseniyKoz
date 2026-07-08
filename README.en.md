[Русский](./README.md) | [English](./README.en.md)

# Arseniy Kozhin

Agent / AI Engineer. I work on agentic backend systems: agent core, tool runtime, RAG, eval/observability, and local inference.

I currently work in the GenAI Lab at NPK "Electrostal". My scope is the behavior of a corporate AI agent: how it chooses tools, builds context, returns answers with sources, and how we check that changes do not make answer quality worse.

## What To Look At

| Evidence lane | What it shows | Where to look |
|---|---|---|
| Production agent work | Closed corporate work: agent loop, tool routing, RAG, citations, Langfuse traces, eval runs, and local inference. | Resume and experience summary below |
| Public tooling | I can turn agent-facing tools into a clear dev runtime, not only notebooks. | [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) |
| Research / math / ML | I can take research tasks to verifiable code, tests, experiments, and documentation. | [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench), [Random_walk_on_plates](https://github.com/ArseniyKoz/Random_walk_on_plates), [Morze-decoder](https://github.com/ArseniyKoz/Morze-decoder) |

## Engineering Focus

**Agent core / tools.** I design agent loops, tool runtime, MCP integrations, prompt/tool contracts, streaming statuses, and answers with sources. I care about the whole behavior path, not only one tool call.

**RAG / eval / observability.** I build the loop for checking answer quality: golden datasets, regression runs, RAG metrics, tool-use checks, LLM-as-judge, Langfuse traces/scores, and regression analysis.

**Backend / inference.** I work with Python/FastAPI backend, Qdrant, PostgreSQL, Redis, Docker, LiteLLM, vLLM, and llama.cpp. I treat latency, TTFT, token usage, prompt cache, and routing as part of product behavior.

## Selected Projects

| Project | Role in the profile | Stack |
|---|---|---|
| [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench) | Reproducible ML benchmark: config-driven runs, data-leakage safety checks, persisted JSON/CSV/NPZ artifacts, and pytest contracts. | Python, scikit-learn, imbalanced-learn, CatBoost, XGBoost, ClearML |
| [Random_walk_on_plates](https://github.com/ArseniyKoz/Random_walk_on_plates) | Numerical Monte Carlo methods for an exterior Dirichlet problem: C++ core, Python reference, CLI, tests, notebooks, and proof-oriented docs. | C++, Python, Jupyter, Monte Carlo |
| [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) | Dev-only MCP sidecar: `code_run` backed by persistent Jupyter kernels, sessions, timeouts, output caps, and artifact resources. Not a sandbox for untrusted code. | Python, MCP/FastMCP, Jupyter, Starlette/Uvicorn, Pydantic, pytest |
| [Morze-decoder](https://github.com/ArseniyKoz/Morze-decoder) | Pet project for decoding Morse code from `.opus` audio: CTC/LSTM baseline and CNN+BiGRU+CTC pipeline. | Python, PyTorch, audio ML |
| [ECC](https://github.com/ArseniyKoz/ECC) | Coursework material on elliptic curves and cryptography. | Python, math, cryptography |

## Stack

**Agent / RAG:** MCP, Agent Skills, RAG tools, citations, Langfuse, LiteLLM, OpenWebUI, Qdrant.

**Backend:** Python, FastAPI, PostgreSQL, Redis, Docker, REST API, SSE/streaming, pytest.

**Inference:** vLLM, llama.cpp, local LLM inference, TTFT, prompt cache, quantization, speculative decoding.

**ML / Data:** PyTorch, scikit-learn, NumPy, Pandas, CatBoost, XGBoost, Matplotlib, Seaborn.

## Experience and Education

- **Agent / AI Engineer, GenAI Lab, NPK "Electrostal"** - 2025 - present.
- **BSc in Applied Mathematics, Vologda State University** - 2022 - 2026.

## Achievements

- ICPC: Northern Eurasia semifinal diploma, 2nd degree (2025).
- ICPC: quarterfinal diploma, 2nd degree (2025).
- Scientific publication on quantitative metrics for generative adversarial networks (2025).
- Sber hackathon: 2nd place (2024).

## Contacts

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
