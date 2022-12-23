FROM alpine
WORKDIR /work
ENV TZ=Asia/Tokyo
RUN apk update && \
    apk add git
RUN apk add vim
RUN apk add --no-cache python3 py3-pip
RUN apk add curl
RUN apk add sudo
RUN apk add cmake
RUN apk add python3-dev
RUN apk add build-base
RUN apk add linux-headers