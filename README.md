# Описание настройки и запуска приложения

* **App.py**      -  основной скрипт запуска

* **db.json**      - база шаблонов

* **TestApp.py**   - автоматические тесты



## Установка

```bash
pip install -r requirements.txt
```

## Запуск

```bash
python app.py get_tpl --customer=John Smith --дата_заказа=27.05.2025
```

## Тест

```bash
pytest test_app.py
```
