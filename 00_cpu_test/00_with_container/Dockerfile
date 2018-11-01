FROM python:3.7.1-alpine3.8

LABEL author="zehcort"

ADD greedy.py /tmp

RUN pip install flask

WORKDIR /tmp

CMD python greedy.py
