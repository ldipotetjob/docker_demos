### How steps to create the docker images and run the container 

```shell
# move to flask-app directory 
# create the image
docker build -t flask-app .
# run the container
docker run -d --publish 8888:5000 flask-app
```

You can access to the website:\
http://localhost:8888/




[Source of this code](https://github.com/prakhar1989/docker-curriculum/tree/master/flask-app) 
