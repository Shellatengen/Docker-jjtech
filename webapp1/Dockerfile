
FROM ubuntu:20.04

RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip3 install flask

WORKDIR /app


EXPOSE 8080

COPY app.py .

CMD ["python3", "app.py"]



