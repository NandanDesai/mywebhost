# mywebhost

This is a LAMP (Linux, Apache, MySQL (MariaDb is used here), PHP) stack setup using Docker.

### Pre-requisites: 

* Docker
* Docker-Compose

### How to install?

Clone this repo and inside this repo's directory, run ```
docker-compose up```.

That's it!

After running ```docker-compose up``` command, the Apache web server will be available at ```localhost:8080```, phpMyAdmin will be available at ```localhost:8000```.

If you want to connect to database from your php, use 'db' as the server name, 'root' as the username for root and 'root' as the password for root user.

Note: Apache and PHP will be running in one container, MySQL on a separate container and phpMyAdmin will be running on another separate container. Check out docker-compose.yml file and edit it if required.
