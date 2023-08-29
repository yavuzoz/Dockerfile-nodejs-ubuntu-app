FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash
RUN apt-get install nodejs -y
WORKDIR /node-app
COPY . /node-app/
CMD ["node","/node-app/index.js"];