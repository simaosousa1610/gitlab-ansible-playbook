FROM docker:20.10

RUN apk add --no-cache git curl unzip zip python3 py3-pip bash openssh-client \
    && pip3 install --no-cache-dir ansible \
    && rm -rf /var/cache/apk/*