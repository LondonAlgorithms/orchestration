FROM ruby:latest

RUN mkdir -p /usr/src/problem
WORKDIR /usr/src/problem

ADD ./Gemfile /usr/src/problem/Gemfile
ADD ./Gemfile.lock /usr/src/problem/Gemfile.lock

RUN bundle
RUN mkdir /usr/src/problem/spec
