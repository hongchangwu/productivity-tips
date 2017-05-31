# Docker

## Useful commands

### Build without cache

```
docker build --no-cache .
```

### Run Docker without sudo

```
sudo addgroup -a username docker
```

### Remove containers

Remove all containers:

```
docker ps -a -q | xargs --no-run-if-empty docker rm -f
```

Remove all containers that have exited:

```
docker ps -a -q --filter status=exited | xargs --no-run-if-empty docker rm
```
