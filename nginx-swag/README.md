# [Setup guide](https://docs.linuxserver.io/general/swag)

Once you've set up your files & folders similar to the example above and templates in this repository, in the root folder of `docker-compose.yaml` run 

 - `sudo docker-compose build` -> builds the projects you want to run along the server
 - `sudo docker-compose up -d` -> starts the server
 - `sudo docker ps` -> checks running docker containers
 - `sudo docker logs swag` -> checks the server's logs if everything went fine or not

 `default.conf` is the default nginx server file, if you'd like to have multiple domains point to different servers yet host them with the same nginx instance, you can define multiple virtual servers in the file and manage traffic accordingly.