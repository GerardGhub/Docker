# Docker

docker run -d --hostname rmq --name rabbit-server -p 8080:15672 -p 5672:5672 rabbitmq:3-management
localhost:8080 on browser

default Credentials
username: guest
password: guest


//docker hub website find httpd for the apached server

docker images
docker build -t hello-docker:1.0.0 .
docker image history 

docker run -d  for disconnected
docker run --name first-container -p 8080:80 hello-docker:1.0.0
docker ps -a  //show all the container
docker start 5fe
docker stop 5fe
docker rm 5fe  for removing the container
docker rmi 5fe for removing the image

docker build -t hello-docker:1.0.1 .
docker pull mysql
