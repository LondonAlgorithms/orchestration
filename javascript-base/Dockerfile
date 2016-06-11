FROM node:latest

RUN mkdir -p /usr/src/problem
WORKDIR /usr/src/problem

ADD ./package.json /usr/src/problem/package.json

RUN npm install

RUN mkdir /usr/src/problem/spec
ADD mocha.opts /usr/src/problem/
