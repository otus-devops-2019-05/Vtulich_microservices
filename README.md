Выполнено ДЗ 22

    Основное ДЗ

В процессе сделано:

    Накатили и поработали с Helm
    Развернули Gitlab в Kubernetes
    Запустили CI/CD конвейера в Kubernetes

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 21

    Основное ДЗ

В процессе сделано:

    Настроили Ingress
    Добавили секреты
    Настроили балансировщик
    Подцепили хранилища

Как запустить проект:

    Выполнить команду kubectl apply -f *filename*

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 20

    Основное ДЗ

В процессе сделано:

    Развернули локальное окружение для работы с Kubernetes
    Развернули Kubernetes в GKE
    Запустили reddit в Kubernetes

Как запустить проект:

    Выполнить команду kubectl apply -n dev -f *filename*

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 19

    Основное ДЗ

В процессе сделано:

    Развернули вручную kubernetes используя The Hard Way

Как запустить проект:

    Выполнить команду kubectl apply -f *filename*

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 18

    Основное ДЗ

В процессе сделано:

    Собрали неструктурированные логи
    Визуализацировали логи
    Собрали структурированные логи
    Выполнили распределенную трасировку

Как запустить проект:

    Выполнить команду docker-compose up -d&&docker-compose -f docker-compose-logging.yml up -d

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 17

    Основное ДЗ

В процессе сделано:

    Замониторили Docker контейнеры CAdvisor
    Построили графики в Grafana
    Собрали метрики работы приложений и бизнес метрики
    Настроили и проверили алертинг
    Ссылка на репу - https://cloud.docker.com/u/vtulich/repository/list

Как запустить проект:

    Выполнить команду docker-compose up -d&&docker-compose -f docker-compose-monitoring.yml up -d

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 16

    Основное ДЗ

В процессе сделано:

    Сконфигурировали и запустили Prometheus
    Замониторили микросервисы
    Собрали метрики состояния хоста NodeExporter
    Ссылка на репу - https://cloud.docker.com/u/vtulich/repository/list

Как запустить проект:

    Выполнить команду docker-compose up -d

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 15

    Основное ДЗ

В процессе сделано:

    Подготовили инсталляцию Gitlab CI 
    Подготовили репозиторий с кодом приложения
    Описали для приложения этапы пайплайна
    Определили окружения

Как запустить проект:

    Выполнить команду docker-compose up -d

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 14

    Основное ДЗ

В процессе сделано:

    Разобрались с работой сети в Docker(none,bridge,host)
    Установили docker-compose на локальную машину
    Собрали образы приложения reddit спомощью docker-compose
    Запустили приложение reddit спомощью docker-compose
    "Узнайте как образуется базовое имя проекта" - названия папки + название сервиса

Как запустить проект:

    Выполнить команду docker build

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 13

    Основное ДЗ

В процессе сделано:

    Запилили новую структуру приложения
    Подправили предоставленные файлы
    Запустили контейнеры и запушили посты

Как запустить проект:

    Выполнить команду docker build

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices

Выполнено ДЗ 12

    Основное ДЗ

В процессе сделано:

    Установлен Docker его компоненты и зависимости
    Создали и поигрались с контейнерами
    Запилил нашу DB и приложение в контейнер
    Зарегались на docker hub и запушили туда наш образ

Как запустить проект:

    Выполнить команду - "docker build -t reddit:latest ."

Как проверить работоспособность:

    По ссылке https://travis-ci.com/otus-devops-2019-05/Vtulich_microservices
