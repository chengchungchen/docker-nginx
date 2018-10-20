OS: Ubuntu 16.04

```
docker run --name nginx -v ~/docker-nginx/conf/nginx.conf:/etc/nginx/nginx.conf:ro -v ~/docker-nginx/conf/conf.d:/etc/nginx/conf.d:ro -p 9527:9527 -d --log-opt max-size=256m nginx:1.15.2
```
Ref:
https://docs.docker.com/config/containers/logging/json-file/
