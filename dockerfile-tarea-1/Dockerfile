FROM node:6.14.4-alpine
WORKDIR /usr/src/app
RUN apk update \
	&& apk add tini
EXPOSE 3000/tcp
COPY . /usr/src/app
