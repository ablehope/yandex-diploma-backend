# news-explorer-api

## Бэкенд часть дипломного проекта Яндекс.Практикум:
```
Проект представляет собой серверную часть для сервиса по поиску

новостей по запросу, и возможностью сохранить их в личном кабинете.
```
[Фронтенд часть](https://github.com/ablehope/news-explorer-frontend)

### Ссылки:
- http://130.193.38.218/,
- http://api.ablehope.ru/.

### Функционал:
| Запрос                                            | Ответ                                                               |
|---------------------------------------------------|---------------------------------------------------------------------|
| GET /articles                                     | возвращает все сохранённые пользователем статьи                     |
| POST /articles                                    | создаёт статью                                                      |
| DELETE /articles/articleId                        | удаляет сохранённую статью  по _id                                  |
| GET /users/me                                     | возвращает информацию о пользователе (email и имя)                  |
| POST /signup                                      | создаёт пользователя с переданными в теле данными                   |
| POST /signin                                      | возвращает JWT, если в теле запроса переданы правильные почта, пароль|

### Установка проекта:

Для установки необходимо наличие установленного Node.JS и npm.

Сохраните проект у себя на компьютере:  
```
git clone https://github.com/ablehope/news-explorer-api.git
```

В корне проекта через консоль/терминал запустите команду:  
```
npm install
```
#### После успешной установки станут доступны команды:  
Запуск локального сервера:  
```
npm run dev
```  
Запуск продакшн сервера:  
```
npm run start
```