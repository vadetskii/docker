FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip && \
    pip3 install awscli --break-system-packages
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
