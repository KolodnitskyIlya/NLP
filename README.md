# NLP Course Notebooks

Учебный репозиторий с лекционными ноутбуками и практическими заданиями по обработке естественного языка: от предобработки текста и эмбеддингов до моделей RNN/Transformer, тематического моделирования и концепций LLM/RAG.

## Структура репозитория

```text
.
├── Lectures/
├── 1. PyTorch (Regression + Classification)/
├── 2. RNN LSTM GRU (Text Classification)/
├── 3. Transformer GPT (Text Generation)/
├── 4. NLP Applications (HF Pipelines)/
├── 5. Topic Modeling (BigARTM)/
├── Extra 1. HH.ru Parsing (Async + Threads)/
├── Extra 2. Word2Vec (Skip-Gram + CBOW)/
├── Extra 3. RNN Attention (Classification)/
├── Extra 4. Topic Modeling (sklearn + gensim)/
├── RAG Constitution Search/
├── pyproject.toml
└── uv.lock
```

## Лекции (`Lectures`)

1. Введение
- Предобработка текстовых данных
- Векторные представления и предобученные модели

2. Обработка последовательностей
- RNN, LSTM, GRU
- Encoder-Decoder и нейронный машинный перевод

3. Трансформеры и альтернативные подходы
- Архитектура Transformer
- Transfer learning для BERT/GPT
- Решение прикладных NLP-задач
- Модели пространства состояний (SSM, Mamba)
- Продвинутые рекуррентные архитектуры (xLSTM)

4. Большие языковые модели и AI-агенты
- Основы LLM и RAG
- Обучение и механизмы рассуждений в LLM
- Разработка AI-агентов на базе LLM

5. Тематическое моделирование
- EM-алгоритм и регуляризация
- Аддитивная регуляризация и подходы с трансформерами

6. Основы распознавания и синтеза речи
- Базовые подходы ASR и TTS

## Соответствие заданий и лабораторных

- `1. PyTorch (Regression + Classification)/task.ipynb`: основы Python и PyTorch, полносвязные нейронные сети
- `2. RNN LSTM GRU (Text Classification)/task.ipynb`: классификация текстов с применением RNN
- `3. Transformer GPT (Text Generation)/task.ipynb`: архитектура Transformer и GPT-подход к генерации текста
- `4. NLP Applications (HF Pipelines)/task.ipynb`: решение прикладной NLP-задачи
- `5. Topic Modeling (BigARTM)/task.ipynb`: тематическое моделирование новостных статей
- `Extra 1. HH.ru Parsing (Async + Threads)/task.ipynb`: парсинг данных с hh.ru
- `Extra 2. Word2Vec (Skip-Gram + CBOW)/task.ipynb`: реализация Word2Vec (Skip-Gram / CBOW)
- `Extra 3. RNN Attention (Classification)/task.ipynb`: реализация механизма внимания в RNN
- `Extra 4. Topic Modeling (sklearn + gensim)/task.ipynb`: тематическое моделирование с `scikit-learn` и `gensim`

### РГР
- `RAG Constitution Search/rgr.ipynb`: расчетно-графическая работа по разработке RAG-системы для поиска правовых статей Конституции РФ (чанкинг, эмбеддинги, векторная БД, retrieval, генерация ответа LLM, API/web-часть)

## Технологический стек

- Python 3.12
- PyTorch
- NumPy, Pandas, SciPy, scikit-learn
- NLTK, Razdel, Pymorphy3
- Gensim, Navec
- JupyterLab / Notebook

## Быстрый старт

```bash
# из корня репозитория
uv sync
source .venv/bin/activate
jupyter lab
```

После запуска откройте любой ноутбук из:
- `Lectures/`
- `1. PyTorch (Regression + Classification)/`
- `2. RNN LSTM GRU (Text Classification)/`
- `3. Transformer GPT (Text Generation)/`
- `4. NLP Applications (HF Pipelines)/`
- `5. Topic Modeling (BigARTM)/`
- `Extra 1. HH.ru Parsing (Async + Threads)/`
- `Extra 2. Word2Vec (Skip-Gram + CBOW)/`
- `Extra 3. RNN Attention (Classification)/`
- `Extra 4. Topic Modeling (sklearn + gensim)/`
- `RAG Constitution Search/`

## Примечания

- Большая часть ноутбуков на русском языке.
- Репозиторий предназначен для обучения и экспериментов.
