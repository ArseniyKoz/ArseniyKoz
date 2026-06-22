[Русский](./README.md) | [English](./README.en.md)

# Arseniy Kozhin

Agent Engineer/Researcher. Отвечаю за продуктовую логику и качество agentic backend: поведение агента, tool routing, retrieval, финальный ответ, источники, evals и observability.

Сейчас работаю в Лаборатории GenAI НПК "Электросталь". Основной фокус - RuCortex: закрытый FastAPI backend для RAG/agent workflows с Qdrant, OpenWebUI, LiteLLM, Langfuse, Docker и benchmark tooling.

## Инженерный фокус

**Agent core / harness.** Я занимаюсь логикой agentic backend: как агент собирает контекст, выбирает инструменты, вызывает `query_rewrite`, `rag_search` и `document_fetch`, стримит статусы и возвращает ответ с источниками. Моя зона здесь - не только отдельные tools, а весь контур поведения: prompt contract, tool routing, ограничения на шаги агента, OpenWebUI-интеграция и developer harness, через который это можно проверять и отлаживать.

**Eval / observation.** Я строю контур, который показывает, стал агент лучше или хуже после изменения. Это bench datasets, run profiles, regression checks, Langfuse traces/scores, сравнение запусков и RCA по провалам: неправильный tool path, слабый retrieval, плохая groundedness, latency или runtime error. Важная часть работы - сделать качество ответа наблюдаемым, а не оценивать его на глаз.

**LLM inference.** Я работаю с тем, как модели подключаются и ведут себя в реальном backend: LiteLLM routing, streaming, TTFT, token usage, prompt-cache signals и локальные эксперименты с vLLM/llama.cpp/Ollama-compatible inference. Цель - понимать не только "какая модель отвечает", но и как ее latency, streaming behavior и routing влияют на агентный сценарий.

## Избранные проекты

| Проект | Что доказывает | Стек |
|---|---|---|
| RuCortex / backend_pipeline (private) | Agentic RAG backend: ingestion/query API, OpenWebUI adapter, tool-based agent loop, streaming, sources и Langfuse tracing. Моя зона - логика агента, качество ответа, eval/bench и диагностика изменений. | Python, FastAPI, Qdrant, Docker, OpenWebUI, LiteLLM, Langfuse, SSE |
| Benchmark/eval контур RuCortex | Контур проверки agentic RAG и direct RAG baseline: CLI/API/UI, profiles, Langfuse datasets/traces/scores, release_id, profile gates, compare и RCA buckets. | Python, PostgreSQL, Langfuse, pytest, Node tests, browser UI |
| [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) | Dev-only HTTP MCP sidecar: `code_run` поверх persistent Jupyter kernels, sessions, timeouts, output caps, artifact resources и result bundles. Helper для разработки, не sandbox для недоверенного кода. | Python, MCP/FastMCP, Jupyter, Starlette/Uvicorn, Pydantic, pytest |
| [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench) | Исследовательский стенд для сравнения вариантов SMOTE: воспроизводимые эксперименты, метрики качества и визуализация результатов. | Python, scikit-learn, imbalanced-learn, CatBoost, XGBoost |
| GAN metrics research | Исследование метрик качества GAN и OCR-oriented evaluation; результат оформлен в научную публикацию по материалам студенческой конференции. | Python, PyTorch, NumPy, Pandas |

Ранние ML-проекты и учебные эксперименты оставляю как историю, но не ставлю рядом с текущими RAG/eval/backend работами.

## Стек

**Языки и база**

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

**Инструменты и окружение**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

## Опыт и образование

- **LLM Engineer, Лаборатория GenAI НПК "Электросталь"** - 2025 - настоящее время.
- **Бакалавриат, прикладная математика, Вологодский государственный университет** - 2022 - 2026.

## Достижения

- ICPC: диплом II степени полуфинала Северной Евразии (2025).
- ICPC: диплом II степени четвертьфинала (2025).
- Научная публикация: метрики оценки качества генеративно-состязательных сетей в задаче распознавания текста (2025).
- Хакатон Сбера: 2 место в треке Data Science (2024).

## Контакты

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
