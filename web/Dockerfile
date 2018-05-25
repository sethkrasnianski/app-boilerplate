FROM node:9.6.1
RUN mkdir /web
WORKDIR /web
ENV PATH /web/node_modules/.bin:$PATH
RUN yarn
COPY . /web
