# Install Docker
Follow this documentation to set up Docker on __CentOS 7__.


## On Centos7

##### Switch to root user


```
sudo su
```


##### Update repo list


```
yum update -y
```


##### Install Wget

```
yum install wget -y
```


##### Install docker

```
wget -qO- https://get.docker.com/ | sh 
```


##### Verify Docker Installation

```
docker version
```

##### Start Service

```
service docker start
```
