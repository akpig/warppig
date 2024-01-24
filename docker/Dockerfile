FROM alpine:3.16
WORKDIR /config
RUN mkdir - /temp
ADD https://github.com/akpig/warppig/releases/lastest/download/warp-pig_linux.tar.gz /usr/local/bin/

ENTRYPOINT ["warp-pig"]