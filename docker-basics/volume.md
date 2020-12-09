

> docker info -> for full info
> docker container run -d -p 8080:80 --name mynginx nginx
> docker container exec -it mynginx bash
> docker container rm 37f347d85a74d7fb7 -f

We can use this command to bash into the image, and view the files inside the image.

- we can create a `volume` to map the server to an area of the local file system.
-  binding local file system to the container


> docker container run -d -p 8080:80 -v $(pwd):/usr/share/nginx/html nginx

Docker cheatsheet :
https://gist.github.com/bradtraversy/89fad226dc058a41b596d586022a9bd3

