# http-server
进入前端 build 产物路径，如 dist，然后执行以下命令
```
npx http-server
```

# Nginx
通过 Docker 启动 Nginx，将 dist 改为前端 build 产物路径
```
docker run --rm -p 80:80 -v dist:/usr/share/nginx/html nginx
```

miniserve
# miniserve
## 安装
```
brew install miniserve
```
## 启动
```
miniserve --spa --index index.html
```
