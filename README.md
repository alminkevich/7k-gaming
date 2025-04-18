
# 7k-gaming — Telegram Mini App + Bot

Готовый проект Telegram-бота с мини-приложением на Flask. Подходит для деплоя на Render.

## 🚀 Запуск

```bash
pip install -r requirements.txt
python bot.py
```

## 🌐 Мини-приложение

Запускается через Flask (`app/main.py`) и отдаёт HTML-страницу с кнопкой.

## 🤖 Telegram-бот

Использует WebAppButton, чтобы открывать HTML-страницу прямо в Telegram. Обрабатывает данные через `web_app_data`.

## 🛰️ Деплой

1. Залей проект в GitHub
2. Подключи к [Render.com](https://render.com)
3. Укажи команду запуска: `gunicorn app.main:app`
