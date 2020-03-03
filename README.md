# Installing-docker-compose-on-ubuntu

Download the latest version of Docker Compose:

sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
Apply executable permissions:

sudo chmod +x /usr/local/bin/docker-compose
Test Docker Compose:

docker-compose --version
