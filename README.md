# api_yatube
## Описание проекта:
API для социальной сети YATUBE, позволяющий публиковать посты, создавать комментарии, вступать в группы, а также подписываться на других авторов.
В рамках этого учебного спринта был реализован API для всех моделей приложения.

## СТЕК технологий:
* Python == 3.10.12
* Django == 3.2.16
* Django Rest Framework == 3.12.4

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```sh
git clone git@github.com:FeodorPyth/api_yatube.git
```

```sh
cd api_yatube
```

Cоздать и активировать виртуальное окружение:

```sh
python3 -m venv env
```

```sh
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```sh
python3 -m pip install --upgrade pip
```

```sh
pip install -r requirements.txt
```

Выполнить миграции:

```sh
python3 manage.py migrate
```

Запустить проект:

```sh
python3 manage.py runserver
```

## Автор:
[FeodorPyth](https://github.com/FeodorPyth)
