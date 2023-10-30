# Монорепа содержит исходные поды `@i-novus/oidc-pkce-public-client` и приложение для демонстрации работы  

npm-пакет `@i-novus/oidc-pkce-public-client` предназначен для использования в `react 17+`  приложениях, где необходима авторизация через oauth сервер с использованием публичного (public) клиента (confidential не поддерживается)   

## ENV - переменные

Для запуска демонстрационного web-приложения необходимо указать `.env` переменные (см. README.md приложения)


## Установка зависимостей

Перед выполнением скриптов необходимо установить зависимости. В корне выполните команду:

```yarn install```

Требуется глобально установленный `yarn`. Использоваться автоматически будет `yarn@v3` из папки `.yarn/releases`


## Скрипты `package.json`

`yarn run build` Запускает сборку кода библиотеки и web-приложения с проверкой качества кода

`yarn run start` Запускает демонстрационное web приложение в продуктивном режиме на http://localhost:8081/

`yarn run dev:lib:watch` Запускает сборку библиотеки в режиме разработки в watch-режиме с функцией hot reload. Если сначала запустить `yarn run dev:lib:watch` а следом `yarn run dev`, то будет hot reload, даже при изменении кода библиотеки

`yarn run dev:app:watch` Запускает приложение в режиме разработки на http://localhost:8081/ с функцией hot reload

`yarn run build-fast` Запускает сборку кода библиотеки и web-приложения без проверки качества кода

`yarn run lint` Запускает проверку качества кода библиотеки и web-приложения


## License

[Apache-2.0](./LICENSE)
