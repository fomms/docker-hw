FROM python:3.10

WORKDIR src

COPY . /src

RUN pip3 install --no-cache-dir --upgrade -r /src/requirements.txt

RUN python manage.py migrate

EXPOSE 6000

CMD ["python3", "manage.py", "runserver", "0.0.0.0:6000"]