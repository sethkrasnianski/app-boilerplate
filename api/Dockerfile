FROM ruby:2.5.0
RUN apt-get update -qq && apt-get install -y build-essential nodejs
RUN mkdir /api
WORKDIR /api
COPY Gemfile /api/Gemfile
COPY Gemfile.lock /api/Gemfile.lock
RUN bundle install
COPY . /api
