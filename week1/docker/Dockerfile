FROM python:3.9.1

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2


WORKDIR /app
COPY ingest2_data.py ingest2_data.py

ENTRYPOINT ['python', 'ingest2_data.py']
