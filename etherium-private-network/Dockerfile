FROM alpine:3.19.1
RUN apk add --no-cache ca-certificates gcompat
ADD https://github.com/qnddjKJH/kubernetes/raw/main/etherium-private-network/geth-azimir/geth-alltools-1.11.6.tar.gz /
RUN tar -zxvf /geth-alltools-1.11.6.tar.gz -C /usr/local/bin --strip-components 1 && rm /geth-alltools-1.11.6.tar.gz
CMD [ "/bin/sh" ]
EXPOSE 30303/tcp 30303/udp 8545/tcp 8546/tcp
ARG VERSION=
LABEL version=1.11.6