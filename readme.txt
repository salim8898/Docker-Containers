

compose command > docker-compose build
To bring up all stack        > docker-compose up -d
TP bring up single service   > docker-compose up -d jenkins
To bring down all service    > docker-compose down

Dockerfile build command > docker build -t new_image_name . (. is the location for Dockerfile)
Delete running container > docker rm -vf container_name
Clean cache and unused images and stopped container > docker system prune

Stop all containers at once > docker stop $(docker ps -q)
Delete all exited containers > docker rm $(docker ps -aq)



              
  
