FROM continuumio/miniconda3:latest

RUN pip install mlflow==2.0.0 boto3 pymysql

ADD . /app
WORKDIR /app