# Кулинарный энтузиаст

Это веб-приложение на Django, которое позволяет пользователям делиться рецептами блюд и просматривать рецепты других 
пользователей.

## Функциональность

- Регистрация и авторизация пользователей
- Просмотр списка случайных рецептов на главной странице
- Просмотр списка всех рецептов
- Просмотр подробной информации о рецепте
- Добавление нового рецепта (только для авторизованных пользователей)
- Редактирование своих рецептов (только для авторизованных пользователей)
- Категоризация рецептов

## Установка

1. Клонируйте репозиторий: https://github.com/b-fang-code/Rec_Project.git
2. Перейдите в директорию проекта: ***cd .\recipesproject***
3. Создайте и активируйте виртуальное окружение: ***python -m venv env*** <br>
***source env/bin/activate***   (# На Windows используйте ***env\Scripts\activate***)
4. Установите зависимости: ***pip install -r requirements.txt***
5. Примените миграции: ***python manage.py migrate***
6. Создайте суперпользователя (для доступа к админ-панели): ***python manage.py createsuperuser***
7. Соберите статические файлы: ***python manage.py collectstatic***
8. Запустите сервер: ***python manage.py runserver***
9. Откройте приложение в браузере по адресу `http://localhost:8000`.

## Зависимости

- Django
- Pillow (для обработки изображений)