# docker_rails
```
$ docker-compose run web rails new . --force --no-deps --database=mysql --skip-test --webpacker
```

```
$ docker-compose build
```

```
$ docker-compose run web rake db:create
```

```
$ docker-compose up
```

```
$ curl localhost:3000
```