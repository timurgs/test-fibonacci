FROM python:3.11

RUN pip install pika

ENV PYTHONUNBUFFERED=1

WORKDIR /usr/src/app
COPY rpc_client.py .

CMD ["python", "/usr/src/app/rpc_client.py"]