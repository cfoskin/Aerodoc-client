# Aerodoc client

This is the angular Aerodoc client for the Aerodoc Node.js Microservices project. 

Other services: 

Lead Service: https://github.com/cfoskin/lead-service

Sales Agent Service: https://github.com/cfoskin/sales-agent-service

Push Configuration Service: https://github.com/cfoskin/push-configuration-service


API Gateway on Dockerhub: https://hub.docker.com/r/cfoskin/nginx-proxy-local/

It will also work with the Aerodoc Node.js monolithic backend application:

https://github.com/cfoskin/Aerodoc-Node.js


## Running 

Docker Compose:

To run this client with all other  services use Docker Compose with the docker-compose.yaml file. Note: To seed the system with the sales agents data, run the application from the sales agent service, otherwise see swagger documentation for how to post sales agents to RESTful endpoints.

        docker-compose up

Http-server:

To run on its own using a http server:

First install http-server: 

       npm install http-server -g

Run using http-server in route folder:
 
       http-server
       
Application willbe reachable on default port of 8080
