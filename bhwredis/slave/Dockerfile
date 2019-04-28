FROM redis
MAINTAINER bhw1994 <bhw1994@gmail.com>

EXPOSE 80
EXPOSE 443
EXPOSE 6380

COPY redis.conf /usr/local/etc/redis/redis.conf
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]

