FROM alpine
RUN apk add --no-cache curl
RUN wget busybox-extras netcat-openbsd python py-pip && pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null