FROM quay.io/fedora/fedora:34-x86_64
MAINTAINER Brandon Young <brandon@byitkc.com>

RUN mkdir /downloads
RUN dnf -y install rtorrent
WORKDIR /downloads

ENTRYPOINT [ "/bin/bash" ]