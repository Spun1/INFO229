FROM python:3.6.3

ENV MONGO_HOST localhost
ENV MONGO_PORT 27017

COPY ./requirements.txt /requirements.txt

RUN pip install -r /requirements.txt

WORKDIR /wikipedia

COPY ./app.py /app.py

CMD [ "python", "/app.py" ]