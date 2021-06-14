## description

In order to minimize the pain to deploy [myems](https://github.com/MyEMS/myems) project, this project is created to automaticly deploy myems project with docker for debug and demo purpose.

## prerequisites

-   docker
-   docker-compose

## steps to deploy this project

1. clone project and cd into the project folder
2. `chmod +x ./setup.sh `
3. `./setup.sh`
4. `docker-compose up`

## warning

This project is under develop and currently only works for the database and api part of the original project.

## TODOS

1. build web admin docker image
2. build web ui docker image
