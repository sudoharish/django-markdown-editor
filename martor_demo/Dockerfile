FROM python:3

ENV PYTHONUNBUFFERED 1

ENV PORT 8000

WORKDIR /app

ADD  . /app

COPY ./requirements.txt /app/requirements.txt

RUN pip install -r requirements.txt

copy . /app








