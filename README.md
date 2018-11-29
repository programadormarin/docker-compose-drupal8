# Development environment for Drupal 8 build with Docker Compose

## Dependencies

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## How to use

### Download this repository

	$ git clone git@github.com:programadormarin/docker-compose-drupal8.git Drupal8-Docker
	$ cd Drupal8-Docker

### Copy drupal code into /app folder

Start a new terminal (because the other one is running our containers) and copy the Drupal 8 code into the ./app folder.

	$ git clone --branch 8.6.x http://git.drupal.org/project/drupal.git app

### Start the docker containers

This command will build the containers and start the servers. All logging will be outputted on the screen.

	$ docker-compose up -d

