# Шаблон Python CLI 213 для 213

Это минимальный шаблон CLI на Python для быстрого старта разработки консольного приложения.
213
## Установка
{{project_name}}
1. Создайте и активируйте виртуальное окружение:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Установите зависимости (если есть):

   ```bash
   pip install -r requirements.txt
   ```

## Использование

Запустите CLI с помощью:

```bash
python main.py --name [YourName]
```

Пример:

```bash
python main.py --name Alice
```

Output: `Hello, Alice!`

## Настройка

- Измените main.py, чтобы добавить новые аргументы или функциональность.
- Добавьте зависимости в requirements.txt по мере необходимости.

# Инструкции
CI проверяет, файлы простым pytest. Напишите файлы с названием test_... для работы CI.
Для локального запуска тестов:
1. Установите зависимости: `pip install -r requirements`
2. Запустите: `pytest test_main.py

---
made by [**Floom**](https://github.com/Floom1)