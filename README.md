Веб-прилодение "Переводчик" на Python Django

translator_project


Создаем проект translator_project и виртуальное окружение

Устанавливаем pip install poetry

poetry init

poetry add django

touch .gitignore

django-admin startproject django_translator .

./manage.py startapp main

poetry add googletrans==3.1.0a0