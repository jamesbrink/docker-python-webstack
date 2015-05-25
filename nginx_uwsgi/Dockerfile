# Python Nginx uWSGI
#
# VERSION      1.0.0

FROM ubuntu:vivid
MAINTAINER James Brink, brink.james@gmail.com

# Setup needed dependencies
RUN apt-get update && apt-get install -y \
  libexpat1 \
  nginx \
  python \
  python \
  python-pip \
  python-virtualenv \
  ssl-cert \
  && rm -rf /var/lib/apt/lists/* 

RUN mkdir /app && virtualenv /app/

CMD ["/bin/bash"]
