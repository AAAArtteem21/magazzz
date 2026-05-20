# Magazzz — E-commerce Platform
Интернет-магазин с оплатой через Stripe на обычном Django

## Tech Stack
Python · Django · PostgreSQL · Stripe · HTMX

## Features
- Оплата через Stripe (webhooks, обработка платежей)
- авторизация (JWT)
- Кастомная модель пользователя
- Корзина, заказы, история покупок

## Setup
git clone ...
cd magazzz
cp .env.example .env
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
