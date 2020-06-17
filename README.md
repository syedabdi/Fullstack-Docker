[![Build Status](https://travis-ci.org/syedabdi/EventBus-Starter.svg?branch=master)](https://travis-ci.org/github/syedabdi/EventBus-Starter)

## Fullstack-Docker
Full stack React/Express/MongoDB app using Docker. Using Travis for CI

## Objectives
The objective is to give you a practical guide of how to containerize this simple Full-Stack App, to be used as a starting point, for you to build your own apps.

## Docker?

Docker is simply one of the most important technologies at the moment. It lets you run apps inside containers that are mostly isolated from “everything”.
Each container is like an individual virtual machine stripped out of everything that is not needed to run your app. This makes containers very light, fast and secure.
Containers are also meant to be disposable. If one goes rogue, you can kill it and make another just like it with no effort thanks to the container images system.
Another thing that makes Docker great is that the app inside containers will run the same in every system (Windows, Mac, or Linux). This is awesome if you are developing in your machine and then you want to deploy it to some cloud provider like GCP or AWS.
If you are curious about anything else Docker related then please head over to: www.docker.com 

## Getting Ready
Make sure you have Node and Docker running on your machine.

- Containerize your Client
- Containerize your API
- Add a MongoDB database
- Get your containers running
- Continuous Integration with Travis
- Application deployment with Docker

## Terminal Commands
- Backend
docker-compose build
docker-compose up -d [ContainerName]
docker-compose up -d mongo
docker-compose config
docker logs [containerName]
docker logs mongo
docker-compose stop
- Client
docker build -t syedabdi/client  
 ${MONGO_HOST_DATA}\database\db