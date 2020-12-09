-it --> interactive mode. shows all logs on the terminal

docker container run -it -p 80:80 nginx

>information of all containers are stored in docker-hub

docker container ls

docker container ls -a

docker container rm d4d

docker images

docker container rm mynginx -f ( removes a running container )

> images are prepackaged containers.
> we can create our own containers as well


docker image rm

docker pull nginx 021

-d  --> detached ( runs in background )
--name --> give a custom name to the container


docker container run -d -p 8080:80 --name mynginx nginx

> outputs the container id

docker ps > older way to show the containers

--------
Environment variables

for mongo : 
MONGO_INITDB_ROOT_USERNAME

MONGO_INITDB_DATABASE => specify the name of the db

