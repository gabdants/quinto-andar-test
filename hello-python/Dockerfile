FROM python:3.6
MAINTAINER Gabriel Marchini Dantas
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
EXPOSE 8000
COPY requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/
CMD ["python3", "app.py"]