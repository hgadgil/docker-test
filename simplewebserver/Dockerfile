# Simple Web server

FROM ubuntu:latest
MAINTAINER hgadgil@icloud.com

RUN apt-get update
RUN apt-get install -y nodejs npm
RUN npm install -g http-server

RUN ln -s /usr/bin/nodejs /usr/bin/node
ADD contents/index.html /usr/apps/hello-docker/index.html
WORKDIR /usr/apps/hello-docker

CMD ["http-server", "-s"]

