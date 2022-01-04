## how to create docker volume in command and using it in docker-compose

- docker volume create name_volumes

- using the volume you can see in docker-compose.yml file

## how to export and import database into mysql

- cat backup.sql | docker exec -i CONTAINER /usr/bin/mysql -u root --password=root DATABASE
- docker exec -i your_container_id mysql -u root -p(password) your_db_name < /your_project_folder/backup.sql (tergantung kalian naro filenya dimana)
  - - kalian nanti bisa lihat hasil dbnya di folder docker mysql = file > var > lib > mysql > nama db kalian

## how to add network docker in command and using it in docker-compose

- docker network create name_network

- using the network you can see in docker-compose.yml file

## how to copy data into volumes

- docker container create --name dummy -v myvolume:/root hello-world
- docker cp c:\myfolder\myfile.txt dummy:/root/myfile.txt
- docker rm dummy
