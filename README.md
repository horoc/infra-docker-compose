# infra-docker-compose
常用基础组件 一键启停脚本

## Command

启动某服务

```shell

docker-compose up -d xxxxx

```

重启某服务

```shell

docker-compose restart xxxxx

```

关闭某服务

```shell

docker-compose kill xxxxx

```

删除某停止的服务

```shell

docker-compose rm xxxxx

```


docker-compose --help你会看到如下这么多命令

```shell
build               Build or rebuild services
bundle              Generate a Docker bundle from the Compose file
config              Validate and view the Compose file
create              Create services
down                Stop and remove containers, networks, images, and volumes
events              Receive real time events from containers
exec                Execute a command in a running container
help                Get help on a command
images              List images
kill                Kill containers
logs                View output from containers
pause               Pause services
port                Print the public port for a port binding
ps                  List containers
pull                Pull service images
push                Push service images
restart             Restart services
rm                  Remove stopped containers
run                 Run a one-off command
scale               Set number of containers for a service
start               Start services
stop                Stop services
top                 Display the running processes
unpause             Unpause services
up                  Create and start containers
version             Show the Docker-Compose version information
```
