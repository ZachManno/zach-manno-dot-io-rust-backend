# zach-manno-dot-io
Rust Docker backend API using actix-web framework

# Docker

## Build image

```shell
docker build -t zach_manno_dot_io .
```

## Run built image

```shell
docker run -d -p 8080:8080 zach_manno_dot_io
# and the server should start instantly
curl http://localhost:8080
```

## Running unit tests

```shell
docker build -t zach_manno_dot_io:test .
docker run --rm zach_manno_dot_io:test
```


