# Aerodoc client

This is the angular Aerodoc client for the Aerodoc Node.js Microservices project. It will also work with the Aerodoc Node.js monolithic application.

Other services: 

https://github.com/cfoskin/lead-service

https://github.com/cfoskin/sales-agent-service

https://github.com/cfoskin/push-configuration-service

API Gateway on Dockerhub:

https://hub.docker.com/r/cfoskin/nginx-proxy-local/


## Running 

Docker Compose:

To run this client with all other  services use Docker Compose with the docker-compose.yaml file.

        docker-compose up

Http-server:

First install http-server: 

       npm install http-server -g

Run using http-server in route folder:
 
       http-server
       
