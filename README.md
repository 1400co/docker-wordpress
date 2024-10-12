git clone https://github.com/1400co/docker-wordpress.git
cd docker-wordpress
docker-compose up -d

Permisos
- docker ps
- docker exec -it <nombre_del_contenedor_wordpress> /bin/bash

- chmod -R 775 /var/www/html/wp-content/uploads
- chown -R www-data:www-data /var/www/html/wp-content/uploads
