FROM python:3.9.10

WORKDIR /app
COPY ./req.txt .
COPY ./api.ini .
RUN pip install --upgrade pip
RUN pip install -r /app/req.txt