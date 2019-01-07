FROM ubuntu:16.04

WORKDIR /usr/local
RUN apt update && apt install -y wget xorg libgtk2.0-0 \
 && wget -O cistem-1.0.0-beta-intel-linux.tar.gz 'https://cistem.org/system/tdf/upload3/cistem-1.0.0-beta-intel-linux.tar.gz?file=1&type=cistem_details&id=37&force=0&s3fs=1' \
 && tar xf cistem-1.0.0-beta-intel-linux.tar.gz \
 && rm cistem-1.0.0-beta-intel-linux.tar.gz \
 && echo PATH="/usr/local/cistem-1.0.0-beta:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin" > /etc/environment

