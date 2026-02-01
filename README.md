# iad-lab1

Лабораторная работа №1 по дисциплине "Интеллектуальный анализ данных»: первичное исследование датасета и оценка качества данных".

## Датасет
Используется файл: `data/extreme_pollution.csv` (случаи экстремального загрязнения поверхностных вод РФ).

## Структура репозитория
- `notebooks/01_data_understanding.ipynb` — основной ноутбук с анализом.
- `report/quality_report.md` — текстовый отчёт о качестве данных.
- `data/` — датасет.

## Запуск

### 1) Клонирование репозитория

```
git clone https://github.com/chasernoy/iad-lab1.git   
cd iad-lab1
```

### 2) Окружение и зависимости

```
python3 -m venv .venv   
source .venv/bin/activate   
pip install -U pip   
pip install pandas numpy matplotlib seaborn jupyterlab
```

### 3) Запуск ноутбука
```
python3 -m jupyter lab
```

Открыть notebooks/01_data_understanding.ipynb и выполнить ячейки сверху вниз (или через Restart Kernel and Run All Cells… ).
