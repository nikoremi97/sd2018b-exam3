FROM python:3.7.1-alpine3.8

LABEL author="nrecalde"

ADD greedy.py /tmp

WORKDIR /tmp

RUN pip install flask

CMD python /tmp/greedy.py
