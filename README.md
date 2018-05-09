# prometheus-grafana

> docker compose for prometheus &amp; grafana

# Usage

```sh
# use default password and server root url
# GF_ADMIN_PASSWORD = admin
# GF_SERVER_ROOT_URL = http://localhost:9300
$ docker-compose up -d
# custom GF_ADMIN_PASSWORD and GF_SERVER_ROOT_URL
$ GF_ADMIN_PASSWORD={secret} GF_SERVER_ROOT_URL={your url} docker-compose up -d
```

## License

MIT &copy; zcong1993
