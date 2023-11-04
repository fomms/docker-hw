# Задание 1

1. Создать образ
   docker build . --tag nginx-hw
2. Запустить контейнер
   docker run -d -p 5000:80 nginx-hw

# Задание 2
1. Создать образ
   docker build . --tag django-hw
2. Запустить контейнер
   docker run -d -p 5000:6000 django-hw
3. Для теста можно использовать запросы из docker-hw/docker_django/requests-examples.http
