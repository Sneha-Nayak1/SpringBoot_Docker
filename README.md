# SpringBoot_Docker
This is externalizing the docker by creating config folder.
Here I've moved application.properties file to new folder i.e. config.
Then changed the url in application.properties file from localhost to respective database service name.
Also created jar file for each service by runnung maven build.

Docker commands used are:
--> docker-compose up --build
