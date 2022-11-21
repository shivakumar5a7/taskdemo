# # getting base image ubuntu
FROM ubuntu

MAINTAINER SHIVAVARMA<vaddeshiva3@gmail.com>

RUN apt-get update

CMD ["echo","Hello World..! From my first docker image"]
