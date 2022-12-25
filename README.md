### CRUD для Yatube

### Описание
CRUD для проекта социальной сети Yatube.

### Функционал
- Реализован REST API для сервиса публикации постов, Yatube;
- Аутентификация по JWT-токену;
- Работает со всеми модулями Yatube: постами, комментариями, группами и подписчиками.
- Поддерживает методы GET, POST, PUT, PATCH, DELETE;
- Предоставляет данные в формате JSON.

### Запуск проекта в dev-режиме
1. Клонировать репозиторий:
2. Перейти в папку с проектом:
3. Установить виртуальное окружение для проекта:
```
python -m venv venv
``` 
4. Активировать виртуальное окружение для проекта:
```
# для OS Lunix и MacOS
source venv/bin/activate

# для OS Windows
source venv/Scripts/activate
```
5. Установить зависимости:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
6. Выполнить миграции на уровне проекта:
```
cd yatube
python3 manage.py makemigrations
python3 manage.py migrate
```
7. Запустить проект локально:
```
python3 manage.py runserver

# адрес запущенного проекта
http://127.0.0.1:8000
```
### Автор проекта
Артем Римша
