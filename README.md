# Описание настройки и запуска приложения
```bash
App.py       -  основной скрипт запуска
```
```bash
db.json      - база шаблонов
```
```bash
TestApp.py   - автоматические тесты
```


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
