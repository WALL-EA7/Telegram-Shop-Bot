#sales_bot
**Sales Bot** – это полнофункциональный магазин‑бот для Telegram, написанный на Python 3.11+ с использованием **aiogram 3**, **SQLAlchemy** и **FSM**.  
Включает каталог товаров, корзину, оформление заказа, админ‑панель, базу заказов, рассылку и даже AI‑консультанта.
>  **Docker‑композиция** позволяет быстро развернуть в любом окружении, а GitHub Actions настроены для автоматического CI‑проверок.
##Быстрый старт

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
