# docker-lnmp-php7.x

docker容器下实现lnmp开发环境，php版本为7.x

## 安装前提

- 安装docker

- 安装docker-compose

> docker-compose 需要用到python-pip来安装

## 安装

mysql版本5.6

php版本7.1.11 (提供了内置composer)

nginx版本 latest

Dockerfiles目录下的是各个服务的Dockerfile

整个环境通过docker-compose.yml连接在一起。

## 操作

```
cd DockerFiles

docker-compose up -d
```

即可完成环境安装。

在浏览器输入

```
locahots.com
```

