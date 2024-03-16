# http-server
进入前端 build 产物路径，如 dist，然后执行以下命令
```
npx http-server
```

# Nginx
通过 Docker 启动 Nginx，将 dist 改为前端 build 产物路径
```
docker run --name mynignx -e TZ="Asia/Shanghai" -d -p 80:80 -v dist:/usr/share/nginx/html nginx
```
