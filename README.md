# 🍔 Food Ordering System

A desktop **food-delivery app** built with **Python, CustomTkinter and MySQL**. Users browse restaurants and menus by category, manage a cart, place orders and track them.

> 👥 Team project (Spring 2025), forked from teammate Buvan0702's repository.

## Features

- Sign up and log in with hashed passwords
- Browse restaurants and menu items by category, with images
- Cart, checkout and order history
- Live order tracking screen
- User profile and saved preferences

## Data model

`Users`, `Categories`, `Restaurants`, `MenuItems`, `Orders`, `OrderItems`, `CartItems`, `UserPreferences`. These are created automatically by `ui/main.py` on first launch, with seed data.

## Run

```bash
pip install -r requirements.txt
# MySQL must be running. Set the root password in ui/main.py and ui/db_connection.py
# (placeholder: "new_password")
cd ui
python main.py
```

## Tech

Python · CustomTkinter · MySQL · Pillow
