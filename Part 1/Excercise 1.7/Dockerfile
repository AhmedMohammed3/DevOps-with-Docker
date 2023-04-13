FROM ubuntu:20.04

WORKDIR /app

RUN apt update -y

RUN apt upgrade -y

RUN apt install curl -y

COPY . /app

RUN chmod +x instructions.sh

CMD [ "./instructions.sh" ]