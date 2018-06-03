# mywebhost

This is a LAMP (Linux, Apache, MySQL (MariaDb is used here), PHP) stack setup using Docker.

### Pre-requisites: 

* Docker
* Docker-Compose

### How to install?

Clone this repo and inside this repo's directory, run ```
docker-compose up -d```.

That's it!

If you manually want to add a previously developed project, then just move the files into codiad/workspaces (this is the path).

After running ```docker-compose up -d``` command, the Codiad IDE will be available at ```localhost:8080```, phpMyAdmin will be available at ```localhost:8000```.

If you want to connect to database from your php, use 'db' as the server name, 'root' as the username for root and 'root' as the password for root user.
