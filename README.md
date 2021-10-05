# ysavchen_microservices
ysavchen microservices repository

### Домашнее задание №12 - Docker-2
1. Установлен Docker и Docker Machine
2. Создан инстанс в Yandex Cloud и инициализирован докер с помощью Docker Machine
3. Собран docker image - reddit:latest
4. Запущен контейнер и проверена доступность приложения
5. Docker image запушен в Docker Hub

### Домашнее задание №13 - Docker-3
1. Создан каталог с кодом микросервисов: post-py, comment, ui
2. Добавлен Dockerfile в post-py, comment, ui
3. Собраны образы микросервисов с помощью docker build
4. Создана сеть reddit с помощью docker network
5. Запущено и проверено приложение
6. Оптимизирован размер образа ui и перезапущено приложение

### Домашнее задание №14 - Docker-4
1. Установлен docker-compose на машину
2. Добавлен файл docker-compose.yml с описанием сервисов
3. Вынесены в переменные окружения порт ui и версии сервисов

### Домашнее задание №15 - gitlab-ci
1. Установлен Gitlab с помощью docker-compose.yml на Yandex VM
2. Созданы группа и проект
3. Добавлен CI/CD pipeline
4. Добавлен gitlab-runner
5. Добавлены тесты в pipeline
6. Добавлены окружения
7. Добавлены tags
8. Добавлены динамические окружения

### Домашнее задание №16 - prometheus-1
1. Установлен Prometheus с помощью Docker на Yandex VM
2. Добавлена конфигурация prometheus.yml
3. Пересобраны образы микросервисов с кофигурацией из docker_build.sh
4. Добавлен сервис prometheus в docker-compose.yml с микросервисами
5. Добавлен сервис node-exporter в docker-compose.yml с микросервисами
