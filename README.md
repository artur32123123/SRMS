# CHVC

Система управления результатами студентов


[![Python Version](https://img.shields.io/badge/Python-3.7.1-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/Django-2.1-green.svg)](https://djangoproject.com)


Система управления результатами студентов - мой первый проект на Django !! Это однопользовательское приложение, в котором пользователь может CRUD (создать, обновить, удалить) ученика, предмет, комбинацию предметов и результат. Затем студенты могут просмотреть результат и загрузить его в виде файла PDF. Этот проект сейчас находится на http://srms.riajul.me/, не стесняйтесь вносить свой вклад в этот проект.

Я могу нанять внештатного сотрудника, свяжитесь со мной через [emeli] ffilosssoff@gmail.com **

![Dashboard](Screenshots/dashboard.png "SRMS Dashboard")

## Запуск проекта локально


Сначала клонируйте репозиторий на свой локальный компьютер:

```bash
git clone https://github.com/RiajulKashem/SRMS.git
```

Теперь войдите в каталог:
```bash
cd SRMS
```

Теперь создайте виртуальную машину:
```bash
virtualenv venv  
source venv/bin/activate
```

Установите требования:

```bash
pip install -r requirments.txt
```


Примените миграции:

```bash
python manage.py makemigrations
python manage.py migrate
```


Наконец, запустите сервер разработки:

```bash
python manage.py runserver
```


Проект будет доступен по адресу ** 127.0.0.1: 8000 **.

## Лицензия


Исходный код выпущен под [MIT License](https://github.com/RiajulKashem/SRMS/blob/master/LICENSE).
## Заключение

Спасибо, что прочитали это. Наконец-то ** Не забудьте поставить звездочку 🌟 !! **

## Автор 

Артур