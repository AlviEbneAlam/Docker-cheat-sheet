# Docker-cheat-sheet
A file containing essential docker commands

### Image commands
#### List all docker images
- docker images
#### Building a docker image from a docker file
- docker build -t 'jar file name in container'
#### Remove a docker image
- docker rmi 'RepositoryName/ImageID'


### Container commands
#### List all docker containers
- docker ps -a
#### Run a container from a docker image
- docker run -p hostport:containerport --name 'containerName' 'imageName/imageID'
- docker run -p hostport:containerport 'imageName/imageID'
#### List all running containers
- docker ps
#### Remove a container
- docker rm 'containerId'
