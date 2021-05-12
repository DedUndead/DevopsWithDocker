FROM golang:1.16

WORKDIR /usr/src/app

EXPOSE 8080

COPY . .

ENV PORT=8080

RUN go build

CMD ./server

