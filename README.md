# docker-nginx-phpfpm

This is a simple sample.

- docker
- nginx
- php-fpm

(with Docker for Mac. )

# Prerequisites

Make sure that you installed Docker (for Mac).

Ref. [Docker for Mac](https://docs.docker.com/docker-for-mac/)

```
$ docker -v
Docker version 1.13.1-rc1, build 2527cfc

$ docker-compose -v
docker-compose version 1.10.0, build 4bd6f1a

$ docker-machine -v
docker-machine version 0.9.0, build 15fd4c7
```

# Usage

```
$ git clone git@github.com:mochizukikotaro/docker-nginx-phpfpm.git
$ cd docker-nginx-phpfpm.git
$ docker-compose up
```

Access `localhost:8080`, then you can get phpinfo. 


![2017-02-05 22 32 27](https://cloud.githubusercontent.com/assets/7911481/22626536/087ded2e-ebf3-11e6-8276-f31ac71ae05a.png)


```
$ docker-compose ps
$ docker-compose down
```
