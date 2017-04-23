FROM bash
MAINTAINER chato <quick.xp@gmail.com>

RUN mkdir -p /data/eobackbone
RUN mkdir -p /data/eobackbone/config
WORKDIR /data/eobackbone
VOLUME /data/eobackbone

COPY config/* /data/eobackbone/config/

CMD ["/usr/local/bin/bash"]
