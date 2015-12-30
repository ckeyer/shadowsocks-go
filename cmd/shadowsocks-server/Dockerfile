FROM busybox:latest

WORKDIR /app
EXPOSE 8388

ENV SS_PASSWORD=WangcjHero
ENV SS_PORT=8388
ENV SS_METHOD=aes-256-cfb

COPY ./shadowsocks-server /app/shadowsocks-server

CMD /app/shadowsocks-server