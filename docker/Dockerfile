FROM alpine:3.16
WORKDIR /config
RUN apk --no-cache add curl
RUN mkdir - /temp
RUN curl -s -o "/temp/warp-pig_linux.tar.gz" -L "https://github.com/akpig/warppig/releases/latest/download/warp-pig_linux.tar.gz" && cd /usr/local/bin && md5sum /temp/warp-pig_linux.tar.gz && tar -xvf /temp/warp-pig_linux.tar.gz && rm -rf /temp/warp-pig_linux.tar.gz

ENTRYPOINT ["warp-pig"]
