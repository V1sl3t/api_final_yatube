# Yatube API

## Описание проекта:
API созданно для того что бы люди могли общаться при помоци постов, оставлять свои коментарии и следить за выходом новых постов.

## Стек технологий:
1.Django
2.REST Framework
3.Djoser
4.SQLite

## Об авторе:
```
https://github.com/V1sl3t
```
## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
## Примеры запросов:

```
http://127.0.0.1:8000/api/v1/posts/
```
```
http://127.0.0.1:8000/api/v1/posts/1/
```
```
http://127.0.0.1:8000/api/v1/groups/
```
```
http://127.0.0.1:8000/api/v1/follow/
```