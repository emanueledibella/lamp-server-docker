# lamp-server-docker
Lamp server with Docker
# File
There are 2 files: 
  - php.Dockerfile: The Dockerfile installs some php extensions in apache
  - docker-compose.yaml: this file creates and configures the containers
# Folder
The html folder is a volume linked to /var/www/html folder of the apache web server configured in container
# Install
To install the containers just type: docker-compose up -d
At this moment docker will install images and will create the volumes
