# Python Apache WSGI (mod_wsgi)
#
# VERSION      1.0.0

FROM ubuntu:vivid
MAINTAINER James Brink, brink.james@gmail.com

# Setup needed dependencies
RUN apt-get update && apt-get install -y \
  apache2 \
  apache2-mpm-prefork \
  apache2-utils \
  apache2.2-common \
  libapache2-mod-wsgi \
  libexpat1 \
  python \
  python \
  python-virtualenv \
  ssl-cert \
  && rm -rf /var/lib/apt/lists/* 

RUN mkdir /app && virtualenv /app/

CMD ["/bin/bash"]
