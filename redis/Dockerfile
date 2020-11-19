FROM redis:latest

COPY redis.conf /redis.conf

RUN mkdir -p /usr/local/etc/redis
COPY redis.conf /usr/local/etc/redis/redis.conf

VOLUME /data

CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]