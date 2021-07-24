FROM quay.io/fedora/fedora-minimal:34-x86_64
MAINTAINER Brandon Young <brandon@byitkc.com>

RUN mkdir /downloads
RUN mkdir /tmp/install
WORKDIR /tmp/install
RUN rpm -U https://download-ib01.fedoraproject.org/pub/fedora/linux/releases/34/Everything/x86_64/os/Packages/l/libstdc++-11.0.1-0.3.fc34.x86_64.rpm
RUN rpm -U https://download-ib01.fedoraproject.org/pub/fedora/linux/releases/34/Everything/x86_64/os/Packages/l/libtorrent-0.13.8-5.fc34.x86_64.rpm
RUN rpm -U https://download-ib01.fedoraproject.org/pub/fedora/linux/releases/34/Everything/x86_64/os/Packages/x/xmlrpc-c-1.51.0-12.fc34.x86_64.rpm
RUN rpm -U https://download-ib01.fedoraproject.org/pub/fedora/linux/releases/34/Everything/x86_64/os/Packages/r/rtorrent-0.9.8-5.fc34.x86_64.rpm

ENTRYPOINT [ "/bin/bash" ]