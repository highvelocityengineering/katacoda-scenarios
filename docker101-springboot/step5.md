To create a docker container, run the following command: `docker run --port 8080:8080 --name docker101_springboot_api docker101_springboot_api`{{execute}} 

To view the running container: `docker ps`{{execute}}

To open the application in browser: https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/

To stop the container: `docker stop docker101_springboot_api`{{execute}}

Now `docker ps` will not show the container since it is stopped. To view the stopped container: `docker ps -a`{{execute}}