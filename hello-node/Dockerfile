FROM node:latest
MAINTAINER Gabriel Marchini Dantas
RUN mkdir /code
WORKDIR /code
ADD . /code/
RUN cd /code
RUN npm install

ADD https://github.com/ufoscout/docker-compose-wait/releases/download/2.2.1/wait /wait
RUN chmod +x /wait
CMD /wait && npm start