# docker-node-example
Node js Hello World app using Docker

Building your image:

$ docker build -t <your username>/docker-node-example

List Images :

$ docker images

Run the image:

$ docker run -p 49160:8080 -d <your username>/docker-node-example

# Get container ID
$ docker ps

# Print app output
$ docker logs <container id>

Test :

To test your app, get the port of your app that Docker mapped:

$ docker ps

Run  (install if needed via: sudo apt-get install curl):

$ curl -i localhost:49160
