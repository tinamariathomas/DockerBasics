# Instructions

Here we'll create a simple docker image and copy a config file to the image, and run it.

See the Dockerfile. It is built on python. It sets the working directory to app, and adds the content of our local 'src' into the docker's 'app folder'. Then it executes a python script.


###### To build the docker image

docker build -t myhello .

###### To run the docker container

docker run myhello
