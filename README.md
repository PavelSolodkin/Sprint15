# Деплой проекта
Деплой бэкенда на внешний веб-сервер

## Функционал
- GET localhost:3000/users сервер вернёт JSON-объект со всеми пользователями.
-  GET localhost:3000/users/userId вернёт запрошенного по ID пользователя.
- POST localhost:3000/signup создаст пользователя по введённым данным name, about, avatar. В поле avatar должна быть ссылка, а в поле email должен быть корректный адрес, иначе сервер вернёт ошибку.
- POST localhost:3000/signin выполняет авторизацию пользователя, выдаёт токен на 7 дней.
- GET localhost:3000/cards возвращает JSON-объект со всеми карточками.
- POST localhost:3000/cards создаст карточку по введённым данным name, link. В поле link должна быть ссылка, иначе сервер вернёт ошибку.
- DELETE localhost:3000/cards/cardId удаляет найденную по ID карточку, если она создана вами.

Сервер может возвращать ошибки с соответствующими кодами, если пытаться перейти по несуществующему адресу, создать карточку/пользователя с невалидными данными или допустить ошибку при вводе ID.

## Технологии:
JS (ES5 / ES6); Node.js; express.js; GIT; MongoDB; Mongoose; Postman; nginx; Яндекс.Облако

## Развертывание:
1. установить Git, Node.js с NPM, Mongo и Postman
2. Клонировать репозиторий командой git clone
3. Установить пакеты npm i
4. Запустить необходимую сборку
