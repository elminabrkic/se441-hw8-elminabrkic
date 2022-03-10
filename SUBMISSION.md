**TODO:** Elmina Brkic #1979681

DOCKER


-Your dockerfile. Please provide a link to this file rather than a screen capture. 

[Dockerfile](Dockerfile)

  
Your running docker instance as shown by a ps command.

![](screenshots/docker-2.jpg)

Your browser accessing the main page of the website from your local container.

![](screenshots/docker-3.jpg)


DOCKER COMPOSE - MYSQL ONLY

The output from the docker-compose up command.

![](screenshots/docker-compose-up-mysql-only.jpg)

Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.

![](screenshots/dockerCopose-2.jpg)


A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.

![](screenshots/docker-compose-stack-trace.jpg)


DOCKER COMPOSE - APP SERVER AND MYSQL

Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.

[docker-compose.yml](docker-compose.yml)

Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.

[application-mysql.properties](src/main/resources/application-mysql.properties)


The output from the docker-compose up command.

![](screenshots/docker-composer-compose-up.jpg)


Your browser accessing the “Veterinarians” page of the website from your local container.

![](screenshots/docker-compose-app-4.jpg)