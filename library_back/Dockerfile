FROM python:3.8

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

COPY library_back /library_back
WORKDIR /library_back 

#COPY requirements.txt /code/

RUN pip3 install --upgrade pip
RUN pip install -r requirements.txt

