FROM python:3.13.0a6-slim

WORKDIR /usr/src/app/api

COPY ./infrastructure/webhook/requirements.txt /usr/src/app/api/requirements.txt
RUN pip install -r /usr/src/app/api/requirements.txt --pre

COPY . /usr/src/app/api