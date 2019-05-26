FROM golang:alpine

RUN apk --no-cache add git ca-certificates wget

WORKDIR /cozy

RUN git clone https://github.com/cozy/cozy-stack.git

RUN go get -d ./...
