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

Copy example `docker-compose.yml` file:

```
cp docker-compose.example.yml docker-compose.yml
```

Update docker-compose file. Edit current service container or add more.

Then run docker-compose:

```
docker-compose up -d
```

That's it!
