[Русский](./README.md) | [English](./README.en.md)

# Arseniy Kozhin

Agent / AI Engineer. Работаю с агентными backend-системами: agent core, tool runtime, RAG, eval/observability и локальный inference.

Сейчас я в Лаборатории GenAI НПК "Электросталь". Моя зона - поведение корпоративного AI-агента: как он выбирает инструменты, собирает контекст, возвращает ответ с источниками и как мы проверяем, что изменения не ухудшили качество.

## Что смотреть

| Линия доказательств | Что показывает | Где смотреть |
|---|---|---|
| Production agent work | Закрытая корпоративная работа: agent loop, tool routing, RAG, citations, Langfuse traces, eval runs, локальный inference. | Резюме и описание опыта ниже |
| Public tooling | Умею выносить агентные инструменты в понятный dev runtime, а не только писать notebooks. | [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) |
| Research / math / ML | Могу доводить исследовательские задачи до проверяемого кода, тестов, экспериментов и документации. | [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench), [Random_walk_on_plates](https://github.com/ArseniyKoz/Random_walk_on_plates), [Morze-decoder](https://github.com/ArseniyKoz/Morze-decoder) |

## Инженерный фокус

**Agent core / tools.** Проектирую цикл агента, tool runtime, MCP-интеграции, prompt/tool contracts, streaming statuses и ответы с источниками. Для меня важна не только работа отдельного tool, а поведение всего сценария.

**RAG / eval / observability.** Строю контур, где качество ответа можно проверять: golden datasets, regression runs, RAG metrics, tool-use checks, LLM-as-judge, Langfuse traces/scores и разбор деградаций.

**Backend / inference.** Работаю с Python/FastAPI backend, Qdrant, PostgreSQL, Redis, Docker, LiteLLM, vLLM и llama.cpp. Смотрю на latency, TTFT, token usage, prompt cache и routing как на часть продуктового поведения агента.

## Избранные проекты

| Проект | Роль в профиле | Стек |
|---|---|---|
| [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench) | Воспроизводимый ML benchmark: config-driven runs, safety checks против data leakage, сохраняемые JSON/CSV/NPZ артефакты и pytest-контракты. | Python, scikit-learn, imbalanced-learn, CatBoost, XGBoost, ClearML |
| [Random_walk_on_plates](https://github.com/ArseniyKoz/Random_walk_on_plates) | Численные Monte Carlo методы для внешней задачи Дирихле: C++ core, Python reference, CLI, tests, notebooks и proof-oriented docs. | C++, Python, Jupyter, Monte Carlo |
| [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor) | Dev-only MCP sidecar: `code_run` поверх persistent Jupyter kernels, sessions, timeouts, output caps и artifact resources. Не sandbox для недоверенного кода. | Python, MCP/FastMCP, Jupyter, Starlette/Uvicorn, Pydantic, pytest |
| [Morze-decoder](https://github.com/ArseniyKoz/Morze-decoder) | Pet-проект по декодированию азбуки Морзе из `.opus`-аудио: CTC/LSTM baseline и CNN+BiGRU+CTC pipeline. | Python, PyTorch, audio ML |
| [ECC](https://github.com/ArseniyKoz/ECC) | Учебный материал по эллиптическим кривым и криптографии. | Python, math, cryptography |

## Стек

**Agent / RAG:** MCP, Agent Skills, RAG tools, citations, Langfuse, LiteLLM, OpenWebUI, Qdrant.

**Backend:** Python, FastAPI, PostgreSQL, Redis, Docker, REST API, SSE/streaming, pytest.

**Inference:** vLLM, llama.cpp, local LLM inference, TTFT, prompt cache, quantization, speculative decoding.

**ML / Data:** PyTorch, scikit-learn, NumPy, Pandas, CatBoost, XGBoost, Matplotlib, Seaborn.

## Опыт и образование

- **Agent / AI Engineer, Лаборатория GenAI НПК "Электросталь"** - 2025 - настоящее время.
- **Бакалавриат, прикладная математика, Вологодский государственный университет** - 2022 - 2026.

## Достижения

- ICPC: диплом II степени полуфинала Северной Евразии (2025).
- ICPC: диплом II степени четвертьфинала (2025).
- Научная публикация: анализ количественных метрик оценки генеративно-состязательных сетей (2025).
- Хакатон Сбера: 2 место (2024).

## Контакты

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
