###Docker环境生成说明
- 生成镜像
> docker build -t ubuntu-python:1.0 -f ./ubuntu-python/Dockerfile .
- 启动容器（docker-compose）
> docker-compose -f etc/docker-compose.yml up -d
- 进入容器
> docker exec -it 容器名 /bin/sh
