# Docker Operations 🐬


##### Switch to root user


```
sudo su
```


##### Deploy Ubuntu Server 

```
docker run -i -t -d ubuntu:14.04 /bin/bash
```

## Explanation

- **docker run** : Run a command in a new container
- **-i** : Keep STDIN open even if not attached
- **-t** : Allocate a pseudo-tty
- **--detach , -d**	:	Run container in background and print container ID
- **ubuntu** : Image
- **14:04** : Version/Tags
- **/bin/bash** : Shell


##### List the running containers

```
docker ps 
```


##### List Images

```
docker images
```

##### Fetch info about Container

```
docker inspect <container_id>    # Example: docker inspect 04707a043ac9
```

##### Login to the container

```
docker exec -i -t <container_id> /bin/bash     # Example: docker exec -i -t 04707a043ac9 /bin/bash
```

##### Validate Container IP [ Inside the Container ]

```
ip a
```

##### Exit from the Container
```
exit
```
