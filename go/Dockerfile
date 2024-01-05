FROM golang:lastest

WORKDIR /go/app

RUN apt-get update && apt-get install -y librdkafka-davecgh

CMD [ "tail", "-f", "/dev/null" ]