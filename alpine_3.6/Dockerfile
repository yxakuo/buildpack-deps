FROM alpine:3.6
# yxakuo/buildpack-deps:alpine

MAINTAINER Allen tGuo(yxakuo@hotmail.com)

RUN apk add --update tzdata

ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime \
    && echo $TZ > /etc/timezone

CMD ["/bin/sh"]