edit .nav
MYSQL_ROOT_PASSWORD=ROOT_PASSWORD
MYSQL_USER=admin
MYSQL_PASSWORD=ROOT_PASSWORD
MYSQL_DATABASE=magento2

1). Download Magento 2 version 2.31 you wish to dockerize and upload it in directory magento2 in parallel docker-compose.yml.

Go to https://magento.com/tech-resources/download? .

2). Build the docker image.

docker-compose build

3). Check the built image as:

docker images

4). Run the containers from built image as:

docker-compose up -d

5). Check the running docker containers by command:

docker-compose ps

docker ps
