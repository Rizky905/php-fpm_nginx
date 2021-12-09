## how to create docker volume in command and using it in docker-compose

- docker volume create name_volumes

- using the volume you can see in docker-compose.yml file

## how to add network docker in command and using it in docker-compose

- docker network create name_network

- using the network you can see in docker-compose.yml file

## how to copy data into volumes 
- docker container create --name dummy -v myvolume:/root hello-world
- docker cp c:\myfolder\myfile.txt dummy:/root/myfile.txt
- docker rm dummy
