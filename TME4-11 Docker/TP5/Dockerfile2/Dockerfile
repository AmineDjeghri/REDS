FROM debian:latest
LABEL version="1.0" maintainer="Christophe Bouder <christophe.bouder@lip6.fr>"
RUN apt-get update && apt-get install -y python python-pip wget && pip install Flask

EXPOSE 5050
VOLUME /home
WORKDIR /home

CMD python 
ENTRYPOINT /home/hello.py
