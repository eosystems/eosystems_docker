FROM bash
MAINTAINER chato <quick.xp@gmail.com>

RUN mkdir -p /data/eobackbone
RUN mkdir -p /data/eobackbone/config
WORKDIR /data/eobackbone
VOLUME /data/eobackbone
VOLUME /var/www/eobackbone/current/public
VOLUME /var/www/eobackbone/current/log

COPY config/* /data/eobackbone/config/

CMD ["/usr/local/bin/bash"]
