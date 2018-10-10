```
docker run --name nginx -v ~/docker-nginx/conf/nginx.conf:/etc/nginx/nginx.conf:ro -v ~/docker-nginx/conf/conf.d:/etc/nginx/conf.d:ro -p 9527:9527 -d nginx:1.15.2
```
