# jenkins-docker

Simple example of how to install Docker inside of Jenkins, mount the socket,
and use the entrypoint to give jenkins access to that socket with the docker
gid permissions.

### Installation
```
mkdir jenkins_home
sudo chown 1000.1000 jenkins_home
docker-compose up -d
```

