FROM alpine:3.16
WORKDIR /config
RUN mkdir - /temp
ADD https://github.com/akpig/warppig/releases/lastest/download/warp-pig_linux.tar.gz /temp
#ADD ./warp-pig_linux.tar.gz /usr/local/bin/
#RUN tar -xvf /temp/warp-pig_linux.tar.gz

ENTRYPOINT ["warp-pig"]