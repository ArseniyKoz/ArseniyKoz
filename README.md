[Русский](./README.md) | [English](./README.en.md)

# Арсений Кожин

Я инженер на стыке LLM/RAG, backend и прикладной математики. Больше всего мне интересны системы, где модель не просто отвечает текстом, а работает внутри проверяемого контура: ищет источники, вызывает инструменты, пишет трассы, проходит evals и дает результат, который можно разобрать после сбоя.

Сейчас работаю LLM Engineer в Лаборатории GenAI НПК "Электросталь". В открытом профиле не раскрываю внутренние детали продукта, но область работы публично описываю так: закрытая RAG/agent platform, retrieval, tool routing, streaming responses, evals, observability и диагностика поведения.

## Что мне интересно строить

- RAG/agent backends, где у ответа есть маршрут: rewrite запроса, поиск, fetch, источники, tool calls, статусы выполнения и финальная проверка.
- Evaluation loops для LLM-систем: datasets, traces, scores, regression checks и разбор причин, почему агент дал плохой ответ.
- Developer tools для AI agents: узкие MCP sidecars, controlled code execution, artifacts и guardrails вокруг выполнения.
- Численные и ML-эксперименты, где важны воспроизводимость, тесты и честное описание ограничений.

## Избранные работы

### [Random_walk_on_plates](https://github.com/ArseniyKoz/Random_walk_on_plates)

Математико-инженерная работа по Monte Carlo методам для внешней задачи Дирихле: Walk on Planes / Walk on Spheres, C++/Python реализация, CLI, tests, notebooks и proof-oriented docs.

Что показывает: умею доводить исследовательский алгоритм до кода с проверками, документацией и сравнением режимов, а не оставлять его только в notebook.

Где смотреть: `docs/`, `external_wop_cpp/tests/`, `external_wop/tests/`, `compare_wop_cpp_rmax_modes.ipynb`.

### [SMOTE-test-bench](https://github.com/ArseniyKoz/SMOTE-test-bench)

Стенд для сравнения oversampling-методов семейства SMOTE на imbalanced binary classification задачах. В проекте есть config-driven запуск, локальные реализации методов, pytest-тесты, safety checks против data leakage и сохранение run artifacts.

Что показывает: умею строить воспроизводимый ML-бенчмарк, где результат можно проверить через конфиги, тесты и сохраненные артефакты.

Где смотреть: `configs/`, `src/methods/classic/`, `tests/`, `pyproject.toml`.

### [just-jupyter-code-executor](https://github.com/ArseniyKoz/just-jupyter-code-executor)

Небольшой MCP sidecar для локальных agent workflows: `code_run` поверх persistent Jupyter kernels, sessions, timeouts, output caps и artifact resources.

Что показывает: интерес к AI developer tooling и к тому, как безопасно давать агенту ограниченное исполняемое окружение.

### [Morze-decoder](https://github.com/ArseniyKoz/Morze-decoder)

Audio ML проект по распознаванию азбуки Морзе из `.opus` файлов. В фокусе не production-сервис, а полный ML-проход: подготовка аудио, baseline, CNN/RNN модель и оценка качества.

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
- Публикация в международной научно-практической конференции по метрикам качества GAN для распознавания текста (2025).
- Хакатон Сбера: 2 место в треке Data Science (2024).
- ICPC: четвертьфинал, диплом 3 степени (2024).

## Контакты

- Email: [arseniykozhin@gmail.com](mailto:arseniykozhin@gmail.com)
- Telegram: [@rssk1n](https://t.me/rssk1n)
