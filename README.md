- before you copy these files into your project folder please to build docker images first in this link
  https://github.com/Rizky905/php-fpm_nginx/tree/php73

- in your project file copy these files
- after that you just need to mount your file project into docker container, you can see the example in docker-compose.yml file in volumes
- the webroot file in the images phpfpm-nginx is /usr/share/nginx/html
- if you curious about the folder inside container you can see in docker extension for vs code or you can run the container inside command line " docker container exec -it container_name bash "
