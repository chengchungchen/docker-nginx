OS: Ubuntu 16.04

CLI:
```
docker run --name nginx -v ~/docker-nginx/conf/nginx.conf:/etc/nginx/nginx.conf:ro -v ~/docker-nginx/conf/conf.d:/etc/nginx/conf.d:ro -p 9527:9527 -d --log-opt max-size=10m --log-opt max-file=3 nginx:1.15.2
```

docker-compose
```
docker-compose up -d
```

Ref:
https://docs.docker.com/config/containers/logging/json-file/
