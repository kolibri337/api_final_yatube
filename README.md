## Проект «API для Yatube»

Yatube - проект социальной сети. «API для Yatube» расширяет возможности социальной сети. Новый функционал позволяет пользователям публиковать свои посты и управлять подписками через программный интерфейс взаимодействия.

### Технологии

- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [Simple JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/)

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
``` bash
`git clone https://github.com/apolwow/api_final_yatube.git`

`cd api_final_yatube`
```

Создать и активировать виртуальное окружение:
``` bash
+ `python3 -m venv env`
+ `source env/bin/activate`
+ `python3 -m pip install --upgrade pip`
```
Установить зависимости:
``` bash
`pip install -r requirements.txt`
```
Выполнить миграции:
``` bash
`python3 manage.py migrate`
```

Запустить проект:
``` bash
`python3 manage.py runserver`
```
Документация проекта будет доступна по адресу:
``` bash
`http://localhost:port/redoc/`
```