FROM golang:1.12-alpine

RUN apk update && apk upgrade && \
  apk add --no-cache git

RUN go get -u github.com/onsi/ginkgo/ginkgo && \
  go get -u github.com/onsi/gomega/...
