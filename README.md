# dockerExpress
Creating a Docker Image and Container for a simple express application.

## starting the docker container

Build the docker image using 

`docker build -t yourdockerid/docker-express:verison .`

Create container and start it using
`docker run -p 8000:8000 -it yourdockerid/docker-express`

Then head over to `localhost:8000` to see the API in action
