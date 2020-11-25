FROM debian:latest
MAINTAINER Christophe Bouder "christophe.bouder@lip6.fr"

RUN apt-get update && apt-get install -y python python-pip wget && pip install Flask


EXPOSE 5050
VOLUME /home
WORKDIR /home

CMD python /home/hello.py
