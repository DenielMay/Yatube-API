### _Описание проекта_

>>
Проект небольшой социальной сети. 
Позволяет публиковать собственные заметки и размещать к ним фото или любую другую картинку (желательно приличного содержания). Данный проект позволяет найти друзей, узнать что-нибудь новое и сделать это мир немного лучше.

### _Технологии_
 - _[Python 3.9.7](https://docs.python.org/3/)_
 - _[Django 2.2.16](https://docs.djangoproject.com/en/2.2/)_
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:DenielMay/api_final_yatube.git
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
