# our base image
FROM continuumio/miniconda3:latest

WORKDIR /app

COPY 1.sh .

#Install modules pymysql boto3 mlflow
RUN conda install -y -c conda-forge pymysql boto3 mlflow

RUN chmod +x /app/1.sh && /app/1.sh