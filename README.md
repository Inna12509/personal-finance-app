# Personal Finance Manager

Настольное приложение для учета личных финансов на Python + Tkinter.

## Функционал

- Учет доходов и расходов
- Категоризация операций
- Расчет текущего баланса, суммы доходов и расходов
- Аналитика по категориям в отдельном окне
- Автосохранение в CSV-файл и загрузка при запуске
- Удаление операций
- Цветовая индикация доходов (зеленый) и расходов (красный)

## Структура проекта

```
personal-finance-app/
├── finance_classes.py    # Классы Category, Transaction, FinanceManager
├── finance_gui.py        # Графический интерфейс на Tkinter
├── requirements.txt      # Зависимости (отсутствуют)
├── README.md             # Описание проекта
└── transactions.csv      # Файл данных (создается автоматически)
```

## Запуск

1. Установите Python 3.7+
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Inna12509/personal-finance-app.git
   cd personal-finance-app
   ```
3. Создайте и активируйте виртуальное окружение (по желанию):
   ```bash
   python -m venv .venv
   .venv\Scripts\activate      # Windows
   source .venv/bin/activate   # Linux/macOS
   ```
4. Запустите приложение:
   ```bash
   python finance_gui.py
   ```
5. Добавляйте операции через форму вверху
6. Просматривайте аналитику через кнопку «Аналитика»

## Технологии

- Python 3.7+
- Tkinter (GUI)
- CSV (хранение данных)
- ООП, Enum