FROM golang:1.17

RUN apt update && \
    apt install -y protobuf-compiler

RUN go install github.com/twitchtv/twirp/protoc-gen-twirp@latest && \
    go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
