# Задание 1

1. Создать образ
   ```bash
   docker build . --tag nginx-hw
   ```
3. Запустить контейнер
   ```bash
   docker run -d -p 5000:80 nginx-hw
   ```

# Задание 2
1. Создать образ
   ```bash
   docker build . --tag django-hw
   ```
3. Запустить контейнер
   ```bash
   docker run -d -p 5000:6000 django-hw
   ```
5. Для теста можно использовать запросы из docker-hw/docker_django/requests-examples.http
