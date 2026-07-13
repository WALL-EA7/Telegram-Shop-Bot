# 🛒 Sales Bot

Полнофункциональный Telegram-магазин, написанный на **Python 3.11+** с использованием **Aiogram 3**, **SQLAlchemy** и **SQLite**.

## ✨ Возможности

- 🛍 Каталог товаров
- 🛒 Корзина
- 📦 Оформление заказа
- 👤 Личный кабинет
- 🔑 Админ-панель
- 📢 Рассылка пользователям
- 🤖 AI-консультант
- 💾 SQLite база данных
- ⚡ FSM (машина состояний)
- 🐳 Docker

## 🚀 Стек технологий

- Python 3.11+
- Aiogram 3
- SQLAlchemy
- SQLite
- Docker
- GitHub Actions

## 📂 Структура проекта

```text
handlers/
database/
keyboards/
states/
utils/
main.py
config.py
```

## 📜 Лицензия

MIT

  
## Быстрый старт

```bash
# 1. Клонируем репозиторий
git clone https://github.com/WALL-EA7/Telegram-Shop-Bot/tree/main

# 2. Создаём .env и указываем токен бота
cp .env.example .env
# В открывшемся файле заполните BOT_TOKEN (получить у @BotFather)

# 3. Запускаем через Docker Compose
docker compose up -d

# 4. Бот готов! Перейдите в Telegram → /start
```
<p align="center">
  <img src="assets/logo.png" width="180">
</p>
