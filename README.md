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

**Agent harness:** agentic RAG, ReAct-style loops, tool routing, query rewrite, citations, MCP, OpenWebUI, LiteLLM, Langfuse.

**Backend:** Python, FastAPI, Qdrant, PostgreSQL, Redis, Docker, REST API, SSE/streaming, pytest.

**ML/data:** PyTorch, scikit-learn, NumPy, Pandas, CatBoost, XGBoost, ClearML, Matplotlib, Seaborn.

**Инструменты:** Git, Linux basics, SQL, Java, C++, LaTeX.

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
