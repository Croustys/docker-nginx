# [Setup guide](https://docs.linuxserver.io/general/swag)

Once you've set up your files & folders similar to the example above and templates in this repository, in the root folder of `docker-compose.yaml` run 

 - `sudo docker-compose build` -> builds the projects you want to run along the server
 - `sudo docker-compose up -d` -> starts the server
 - `sudo docker ps` -> checks running docker containers
 - `sudo docker logs swag` -> checks the server's logs if everything went fine or not