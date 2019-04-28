FROM redis
MAINTAINER bhw1994 <bhw1994@gmail.com>

EXPOSE 80
EXPOSE 443
EXPOSE 6379

COPY ./redis.conf ./redis.conf
CMD [ "redis-server", "./redis.conf" ]

