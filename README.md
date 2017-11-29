This repository is intended to build a Redis 4 image pre-loaded with the [redis-ml](https://github.com/RedisLabsModules/redis-ml) module using Docker.

To build the docker image on your computer:
`docker build -t redis-ml .`

Once the image is built, you can run the Redis server like so:
`docker run -it -p 6379:6379 redis-ml`

Then, in another terminal, you can connect to the server using a regular [redis-cli](https://redis.io/topics/rediscli)

See also: [Docker Hub](https://hub.docker.com/r/louisamon/redis-ml/)
