# Укрорачиватель ссылок
Укорачиватель ссылок на flask
## Описание
Укорачиватель ссылок создан с использованием Flask
## Технологии
* Python
* FLask
* WTForms
* SQLAlchemy
## Как запустить
1. Склонируйте репозиторий
2. Создайте и активируйте виртуальное окружение
    ```commandline
    python -m venv venv
    source venv/Scripts/activate
    ```
3. Установите зависимости
    ```commandline
    pip install -r requirements.txt
   ```
4. Создайте файл .env и укажите настройки:
    ```commandline
    DATABASE_URI=sqlite:///db.sqlite3
    SECRET_KEY=YOUR_SECRET_KEY
   ```
5. Запустите приложение
    ```commandline
    flask run
   ```
## Автор
Николай Козлов
