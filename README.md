# docker

## Clone the repository 
git clone https://github.com/singam123/docker.git

## Run the build command 
cd docker
docker build . --tag flask:latest

## Run the container
docker run -p 5000:5000 flask

## Run the container in detached mode
docker run -p 5000:5000 -d flask
