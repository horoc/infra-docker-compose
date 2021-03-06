# infra-docker-compose

docker compose file for some commonly used back-end components

- [x] mysql
- [x] redis
- [x] zookeeper
- [x] kafka
- [x] hbase
- [x] prometheus
- [x] canal

## Command


```shell

docker-compose up -d xxxxx

```


```shell

docker-compose restart xxxxx

```


```shell

docker-compose kill xxxxx

```


```shell

docker-compose rm xxxxx

```

all


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
