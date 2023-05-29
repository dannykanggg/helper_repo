## Setting up Docker
- Add "Dockerfile" to project base folder
- from outside base, run "docker buildx build <project-name>" to build image

|Command|Description|
|-----------------------------------------------|--------------------|
|`docker buildx build <project-name>`           | switch between branches |
|`docker images`                                | list of docker images |
|`docker image rm <image-id>`                   | delete image by id |
|`docker run <image-id>`                        | build container from image-id |
|`docker ps`                                    | list of currently running containers |
|`docker ps -a`                                 | lsit of all existing containers |
|`docker rm <container-id>`                     | delete container by id |