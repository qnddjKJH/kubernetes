FROM alpine:3.19.1
ADD https://github.com/qnddjKJH/kubernetes/raw/main/etherium-private-network/geth-azimir/geth-alltools-1.11.6.tar.gz /
CMD [ "/bin/sh" ]
RUN /bin/sh -c apk add --no-cache ca-certificates
COPY /geth-alltools-1.11.6/* /usr/local/bin
EXPOSE 30303/tcp 30303/udp 8545/tcp 8546/tcp
ARG VERSION=
LABEL version=1.11.6