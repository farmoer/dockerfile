FROM openjdk:8-alpine
ENV TZ Asia/Shanghai
RUN apk add -U tzdata
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN apk del tzdata
RUN echo $TZ > /etc/timezone
