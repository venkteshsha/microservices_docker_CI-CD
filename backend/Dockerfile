FROM python:3.8-slim-buster

ADD requirement.txt /app/requirement.txt

RUN pip install -r /app/requirement.txt

ADD . .

WORKDIR /app

ENTRYPOINT ["python"]

cmd ["new.py"]

