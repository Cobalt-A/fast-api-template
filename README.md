# fast-api-template
fast-api-template

# Запуск в докер контейнере:

`docker-compose build && docker-compose up`

# Локальная установка зависимостей:

`poetry install` если нету [poetry](https://python-poetry.org/docs/#installing-with-pipx)

# Добавление новой зависимости:

`poetry add "lib_name"`, для добавления в контейнер, нужно писать именно в контейнере или если добавили локально установить через `poetry install` внутри контейнера (для того чтобы исполнять команды в контейнере: `docker exec -it fast-api bash`)