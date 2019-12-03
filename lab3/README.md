# Lab_3: Вступ до моніторингу.

1. Створюю папку з назвою лабораторної роботи у власному репозиторію. Перейшовши у папку ініціалізовую середовище `pipenv` та встановлюю необхідні пакети:
    ```
    pipenv --python 3.7
    pipenv install django
    ```
2. За допомогою Django Framework створюю заготовку проекту `lsite`. Для зручності виношу всі створені файли на один рівень вище:
    ```
    pipenv run django-admin startproject lsite
    mv lsite/lsite/* lsite/
    mv lsite/manage.py ./
    ```
