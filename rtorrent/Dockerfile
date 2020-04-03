FROM alpine:3.9.5

WORKDIR /rtorrent

RUN apk add --no-cache rtorrent

COPY .rtorrent.rc .

CMD [ "rtorrent", "-o", "import=.rtorrent.rc"]
