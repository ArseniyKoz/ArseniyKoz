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

**Языки и база**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**LLM / RAG**

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

**Инструменты и окружение**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

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
