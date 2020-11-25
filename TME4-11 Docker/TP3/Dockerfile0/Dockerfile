FROM debian:latest
MAINTAINER Christophe Bouder "christophe.bouder@lip6.fr"

RUN apt-get update
RUN apt-get install -y python python-pip wget
RUN pip install Flask

ADD hello.py /home/hello.py

WORKDIR /home
