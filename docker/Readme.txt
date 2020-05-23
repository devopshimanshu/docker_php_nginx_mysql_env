Details of docker hub images for LAMP container

PHP Image URL : https://hub.docker.com/_/php

NGINX Image: https://hub.docker.com/_/nginx

MYSQL Image : https://hub.docker.com/_/mysql

In this docker-compose file we have used all the offical customisable images.

Directory structure must be properly followed as described below



There two sample php.ini files which you can configure at docker-compose to get the desired result but our first prefrence must be production php ini.
.env will have the crest for the database but infutre we will use vault to store and get from there.
