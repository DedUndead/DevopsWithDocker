FROM ubuntu:18.04

WORKDIR /usr/src/app

COPY webscript.sh .

RUN apt update; apt install -y curl

CMD ./webscript.sh

