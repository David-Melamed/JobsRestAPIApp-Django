FROM python:3.8.9

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY requirements.txt /code/

RUN pip install --upgrade pip

#Django application packages
RUN pip install -r requirements.txt

COPY . /code/

RUN chmod -R 755 /code/

