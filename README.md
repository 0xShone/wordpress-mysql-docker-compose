# wordpress-mysql-docker-compose

## About this
This is the Docker Compose for WordPress

![demo1](demo_images/demo1.png?raw=true)

## Run
#### Create `.env` file from `.env.sample` and edit as you like.
```shell
$ cp .env.sample .env
```

#### Start docker-compose
```shell
$ docker-compose up
```

If you want to run in the background, use `-d` option.
```shell
$ docker-compose up -d
```

Then you can visit [http://localhost:8080](http://localhost:8080)
