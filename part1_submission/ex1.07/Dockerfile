FROM ubuntu:xenial-20201014

COPY script.sh /usr/local/bin/script.sh
RUN apt-get update && apt-get install -y curl
CMD /usr/local/bin/script.sh

