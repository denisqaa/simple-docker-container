# Express App в Docker

Это простое приложение на Express.js, которое возвращает "Hello World" на корневом URL. Приложение контейнеризовано с использованием Docker и может быть легко настроено и запущено с использованием Docker Compose.

## Предварительные требования

Перед началом работы убедитесь, что у вас установлены следующие программы:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Инструкции по настройке

### 1. Клонируйте репозиторий

```sh
git clone https://github.com/yourusername/express-app.git
cd simple-docker-container
```

### 2. Соберите docker образ
```sh 
docker build -t simple-docker-container .
```

### 3. Запустите docker контейнер
```sh
docker-compose up
```
