# apisix 3.2LTS

本分支基于apisix v3.2 LTS版本进行定制化开发,更加符合企业级网关。
官方[readme](./readme_apisix.md)


# 一、安装

## 1.1 docker部署
### 前提 
- etcd

*注：镜像采用本地etcd服务`host.docker.internal`，采用其他etcd服务修改地址即可。*


### 打镜像
```
docker build  -t apisix:ty3.2  .
```
### 运行容器

```
docker-compose  up  -d
```