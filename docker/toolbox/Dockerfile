FROM alpine
RUN apk add --no cache curl wget busybox-extras netcat-opnebsd python py-pip
RUN pip install awscli
apk --purge -v del py-pip
CMD tail -f /dev/null
