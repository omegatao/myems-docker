FROM ubuntu:20.04
FROM python:3.6
WORKDIR /myems-api
COPY /requirements.txt /myems-api/
COPY /myems-api/ /myems-api/
RUN ls -la /myems-api/*
RUN pip3 install -r requirements.txt
CMD ["gunicorn", "-b", "127.0.0.1:8000", "app:api"]