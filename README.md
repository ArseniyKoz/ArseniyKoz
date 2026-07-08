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

**Языки и база**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Agent / RAG**

![MCP](https://img.shields.io/badge/MCP-5C2D91?style=for-the-badge)
![Agent Skills](https://img.shields.io/badge/Agent_Skills-111111?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0B7285?style=for-the-badge)
![OpenWebUI](https://img.shields.io/badge/OpenWebUI-111111?style=for-the-badge)
![LiteLLM](https://img.shields.io/badge/LiteLLM-2E6BFF?style=for-the-badge)
![Langfuse](https://img.shields.io/badge/Langfuse-111111?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)

**Backend / Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge)
![SSE](https://img.shields.io/badge/SSE-FF6F00?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Inference**

![vLLM](https://img.shields.io/badge/vLLM-2E7D32?style=for-the-badge)
![llama.cpp](https://img.shields.io/badge/llama.cpp-111111?style=for-the-badge)
![Local LLM](https://img.shields.io/badge/Local_LLM-6A1B9A?style=for-the-badge)
![Prompt Cache](https://img.shields.io/badge/Prompt_Cache-455A64?style=for-the-badge)

**ML / Data**

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

- **Agent / AI Engineer, Лаборатория GenAI НПК "Электросталь"** - 2025 - настоящее время.
- **Бакалавриат, прикладная математика, Вологодский государственный университет** - 2022 - 2026.

## Достижения

- [ICPC](https://drive.google.com/drive/folders/1hG1wawnaO2ttI6T6_KWWJjLcB5nkk5PA): диплом II степени полуфинала Северной Евразии (2025).
- [ICPC](https://drive.google.com/drive/folders/1hG1wawnaO2ttI6T6_KWWJjLcB5nkk5PA): диплом II степени четвертьфинала (2025).
- [Научная публикация](https://drive.google.com/file/d/1OaIeC-db5_pM4eg55557coUdI50LkAlV/view): анализ количественных метрик оценки генеративно-состязательных сетей (2025).
- [Хакатон Сбера](https://drive.google.com/drive/folders/1hG1wawnaO2ttI6T6_KWWJjLcB5nkk5PA): 2 место (2024).

## Контакты

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
