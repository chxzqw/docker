FROM alpine:latest
LABEL version="0.1"
LABEL maintainer="chxzqw@gmail.com"

RUN apk update && apk --no-cache add postfix \
    dovecot \ 
    nsd \
    amavisd-new \
    clamav \
    spamassassin \
    certbot
