# gs-spring-boot

use the https://github.com/spring-guides/gs-spring-boot.git repo to dockerize a spring boot application with multi-stage build.

## Installation
``` bash
git clone https://github.com/saeedismael/gs-spring-boot

cd gs-spring-boot

docker build -t gs-spring-boot .

docker tag gs-spring-boot cyberpunks77/gs-spring-boot:latest

docker push cyberpunks77/gs-spring-boot:latest
```


## Run Container
Run these commands
``` bash
git clone https://github.com/saeedismael/gs-spring-boot.git

cd gs-spring-boot

docker build -t gs-spring-boot .

docker run -d -p 8080:8080 gs-spring-boot

pull the image from the Docker Hub and run it:

docker pull cyberpunks77/gs-spring-boot

docker run -d -p 8080:8080 cyberpunks77/gs-spring-boot
```
visit the application at http://localhost:8080/
