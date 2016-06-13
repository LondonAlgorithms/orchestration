FROM ruby:latest

RUN mkdir -p /usr/src/problem
WORKDIR /usr/src/problem

Add ./.rspec /usr/src/problem/.rspec
ADD ./Gemfile /usr/src/problem/Gemfile
ADD ./Gemfile.lock /usr/src/problem/Gemfile.lock

RUN bundle
RUN mkdir /usr/src/problem/spec
ADD ./spec_helper.rb /usr/src/problem/spec/spec_helper.rb
