# API_Docker
Sample_Restful_API  with docker file

Setting up your development environment on your local machine :
```
$ git clone https://github.com/sanchai-wp/API_Docker.git
$ cd API_Docker
$ git clone https://github.com/sanchai-wp/Sample_Restful_API.git
$ cd Sample_Restful_API
$ composer install
$ cd ..
$ docker-compose up -d
```
Folder structure :
```
<repo_folder>
    Sample_Restful_API/
    docker/
        vhost.conf
        web.docker
    docker-compose.yml 
```
