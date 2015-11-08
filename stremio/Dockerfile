FROM alpine:latest

RUN apk add --update curl \
    && curl http://178.62.254.47/Stremio3.3.2.linux.tar.gz | tar xvzf \
    cd Stremio3.3.2.linux \
    && sh Stremio.sh

CMD sh
