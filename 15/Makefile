NAMESPACE ?= danfoster
APP ?= psql
VERSION ?= 15-0.0.1

build:
	docker build --tag ${NAMESPACE}/${APP}:${VERSION} .

push:
	docker build --tag ${NAMESPACE}/${APP}:${VERSION} . --push