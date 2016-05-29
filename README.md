# docker-alpine-shadowsocks-server

在 docker环境下一键启动 ShadowSocks服务器

声明：并非原创， Dockerfile有报告出处。

# Example Usage

```
docker run -d -p {$对外端口}:{$内端口} cmptech/docker-alpine-shadowsocks-server -s 0.0.0.0 -p {$内端口} -k {$密码} -m {$加密算法}

docker run -d -p 9999:9328 cmptech/docker-alpine-shadowsocks-server -s 0.0.0.0 -p 9328 -k your_password -m aes-128-cfb
```
