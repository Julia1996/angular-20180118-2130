Оживляем письма и карточки пользоватей

1. Поместить данные пользователей (из дз1) в сервис UserService
2. С помощью Http сделать получение списка пользователей
- можно использовать либо наш тестовый API (http://test-api.javascript.ru/v1/), либо люобой другой (в том числе свой сервер)
3. То же самое проделать с письмами
4. Сделать сервис логирования, который будет логировать все обращения к сервисам
5. Сделать сервис авторизации (только для хранения и проверки авторизации. саму авторизацию делать пока не нужно) Можно сделать просто кнопку [Login] по нажатию которой записывать в сервис, что пользователь авторизирован, и кнопку [Logout], которая делает обратное действие.
6. Скрывать письма для "неавторизированных" пользователей