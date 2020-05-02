Docker Compose template for [Redis](https://redis.io/).

## Usage

Copy default .env file:

```
cp .env.default .env
```

Copy default redis config:

```
cp redis.conf.default redis.conf
```

Configure Redis. For more information, see [Redis docs](https://redis.io/topics/config).

Then run docker-compose:

```
docker-compose up -d
```

That's it!
