FROM golang:1.12.5-alpine3.9

RUN apk add --no-cache \
	bash \
	gawk \
	sed \
	grep \
	bc \
	coreutils \
	py-pip \
	docker \
	python-dev \
	libffi-dev \
	openssl-dev \
	gcc \
	libc-dev make \
	&& pip install docker-compose

