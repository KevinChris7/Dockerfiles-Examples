# Dockerfiles-Examples

# Basic Docker Commands

Install docker in ubuntu:
sudo apt-get update
sudo apt-get install docker.io
docker --version

//use docker without sudo command

sudo usermod -aG docker $USER

//pull docker image from hub

sudo docker pull <image name>

//list all images

sudo docker images

//run the image

sudo docker run -it -d <imagename> --will get a long name used to access container using exec

//remove image

sudo docker rmi <imageid>

//list the container running

sudo docker ps

//list all containers

sudo docker ps -a

//stop container

sudo stop <containerid>

//login and access container

sudo docker exec -it <containerid> bash

//update container

apt-get update

//exit container

exit

//remove all containers

sudo docker rm -f $(sudo docker ps -a -q)

//create a directory

mkdir app

//save changes in container

sudo docker commit <containerid> <newimagename>

//kill container

sudo docker kill<containerid>

//remove container from sys

sudo docker rm <containerid>
sudo docker rm -f <containerid>

//list folders inside container

ll
