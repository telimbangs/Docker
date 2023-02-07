# check version
docker version

# list out the docker containers
docker ps

# pulling and running an nginx host
docker run -it -p 80:80 nginx

# output/review 
localhost:80

# list all containers and their various states
docker ps -a