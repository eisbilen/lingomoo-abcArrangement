FROM python:3.8-slim

COPY requirements.txt /
RUN pip install -r /requirements.txt

ADD . /app
WORKDIR /app

CMD ["python", "./abc-arrangement.py]
