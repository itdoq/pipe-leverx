FROM alpine
RUN apk add --no-cache curl
RUN docker search nginx -- filter stars=3 --no-trunc busybox
RUN docker start nginx
CMD tail -f /dev/null