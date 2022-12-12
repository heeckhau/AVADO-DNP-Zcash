ARG VERSION
FROM --platform=linux/amd64 electriccoinco/zcashd:${VERSION}
#https://github.com/zcash/zcash/blob/master/contrib/docker/Dockerfile

VOLUME /srv/zcashd/.zcash/
VOLUME /srv/zcashd/.zcash-params/

RUN mkdir -p /srv/zcashd/.zcash/ && chown -R zcashd:zcashd /srv/zcashd/.zcash/
RUN mkdir -p /srv/zcashd/.zcash-params/ &&  chown -R zcashd:zcashd /srv/zcashd/.zcash-params/