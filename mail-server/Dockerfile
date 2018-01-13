FROM alpine:latest
LABEL version="0.1"
LABEL maintainer="Sid Chen <chxzqw@gmail.com>"

RUN apk update \
    && apk --no-cache add postfix \
    dovecot \ 
    nsd \
    amavisd-new \
    clamav \
    spamassassin \
    certbot \
    roundcubemail \
    postfixadmin

EXPOSE 80 443 143 995 53
