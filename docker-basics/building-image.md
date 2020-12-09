
Building an image from docker file

> docker image build -t awsafalam/nginx-test-site .
> docker images
> docker container run -d -p 8082:80 awsafalam/nginx-test-site

Now, going to http://localhost:8082 -> we will se the contents of this folder served.

This does not build the image each time. only store the image once. modifying the code and redeploying the container will not change the image.

This will push into docker hub, and will work on any computer.

> docker login
> docker push awsafalam/nginx-test-site