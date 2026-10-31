Лабораторная работа 1. Кто снизил активность и почему

Работа выполняется в Jupyter Notebook. Зависимости и версия Python описаны в `environment.yml`.

## Требования

- Git
- Miniconda

## 1. Клонирование репозитория

```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git)
cd YOUR_REPOSITORY/Labs/Lab1
```

## 2. Создание окружения

Выполняется один раз:

```bash
conda env create -f environment.yml
conda activate ds-lab1
```

При следующих запусках достаточно активировать существующее окружение:

```bash
conda activate ds-lab1
```

## 3. Запуск ноутбука

Из папки `Labs/Lab1` выполни:

```bash
jupyter lab
```

В открывшемся интерфейсе открой `01_analysis.ipynb` и выполни все ячейки по порядку.

## Исходные данные

Перед запуском поместите файлы из задания в папку:

- data/raw/clients.csv
- data/raw/transactions.csv

Исходные данные не хранятся в репозитории.
Рабочая папка при запуске — корень проекта.
