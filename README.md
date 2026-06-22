[Русский](./README.md) | [English](./README.en.md)

# Арсений Кожин

LLM/RAG Engineer. Отвечаю за продуктовую логику и качество agentic RAG workflows: поведение агента, маршрутизацию инструментов, retrieval, качество финального ответа, evals, observability и delivery.

Сейчас работаю в Лаборатории GenAI НПК "Электросталь". Основной фокус - RuCortex: приватный FastAPI backend для RAG/agent workflows с Qdrant, OpenWebUI, LiteLLM, Langfuse, Docker и benchmark tooling.

## Что я строю

- Agentic RAG backends: query rewriting, RAG search tools, document fetch, streaming statuses, sources/citations и guardrails для финального ответа.
- Evaluation loops: benchmark CLI/API/UI, Langfuse datasets/traces/scores, release-aware diagnostics и RCA для agent failures.
- Developer tools для AI agents: MCP sidecars, Jupyter-backed code execution, artifact resources, smoke checks и execution guardrails.

## Избранные работы

| Проект | Что это | Стек |
|---|---|---|
| [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) | Dev-only HTTP MCP sidecar, который предоставляет `code_run` на persistent Jupyter kernels. Есть sessions, timeouts, output caps, artifact resources и result bundles. | Python, MCP/FastMCP, Jupyter, Starlette/Uvicorn, Pydantic, pytest |
| RuCortex backend_pipeline | Приватный рабочий проект: agentic RAG backend с ingestion, query API, OpenWebUI pipeline adapter, streaming responses, benchmark tooling и diagnostics. | Python, FastAPI, Qdrant, Docker, OpenWebUI, LiteLLM, Langfuse |
| [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench) | Research bench для сравнения SMOTE-вариантов на imbalanced datasets с воспроизводимыми экспериментами и quality metrics. | Python, scikit-learn, imbalanced-learn, CatBoost/XGBoost |
| GAN metrics research | Исследование метрик качества GAN и OCR-oriented evaluation, позже оформленное в публикацию для студенческой научной конференции. | Python, PyTorch, NumPy, Pandas |

## Стек

**LLM/RAG/backend:** Python, FastAPI, Qdrant, OpenWebUI, LiteLLM, Langfuse, MCP, Jupyter, Docker, PostgreSQL, Redis, SSE/streaming, REST API.

**ML/data:** PyTorch, scikit-learn, NumPy, Pandas, CatBoost, XGBoost, ClearML, Matplotlib, Seaborn.

**Другое:** C++, Java, Git, Linux basics, pytest, LaTeX, SQL.

## Опыт и образование

- LLM Engineer, Лаборатория GenAI, НПК "Электросталь" (2025 - настоящее время).
- Java Developer Intern, SberTech (февраль 2024 - август 2024).
- Бакалавриат по прикладной математике, Вологодский государственный университет (2022 - 2026).

## Достижения

- ICPC: полуфинал, диплом 2 степени (2025).
- ICPC: четвертьфинал, диплом 2 степени (2025).
- Хакатон Сбера: 2 место в треке Data Science (2024).
- Научная публикация по метрикам качества GAN для распознавания текста (2025).

## Контакты

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
