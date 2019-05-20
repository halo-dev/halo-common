<h1 align="center"><a href="https://github.com/halo-dev" target="_blank">Halo common</a></h1>

> 这里用于存放一些 [Halo](https://github.com/halo-dev/halo) 可能会用到的一些配置文件，请按需下载。

## application-template.yaml

> 该文件为 Halo 的用户配置文件，放置于服务器的 `~/.halo` 下，可覆盖应用本身的配置。

## nginx.conf

> 该文件为 Nginx 的配置文件，可供参考。

## Caddyfile

> 该文件为 Caddy 的配置文件，可供参考。

## docker-compose.yaml

> 该文件为 Docker Compose 的配置文件，使用 Docker Compose 部署的时候可用到。

## halo.service

> 该文件为 Systemd 的文件，用于把 Halo 注册成为系统服务，方便管理 Halo 的运行状态。

## tool.sh

> 该文件为 Halo 的运行脚本，使用方法：

```bash
# 启动 Halo
./tool.sh start

# 停止 Halo
./tool.sh stop

# 重启 Halo
./tool.sh restart

# 查看状态
./tool.sh status
```