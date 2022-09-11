# This is my docker cheatsheet

Basically I created this repo just to remember better the docker commands instead of saving them in only one place I have decided to leave it here on github.

## Docker basic commands: 



| Parameter | Command | Short description |
| ------------- | ------------- | ------------- |
| ------------- | ``docker ps`` | You can see all images  |
| ------------- | ``docker build <directory>`` | you can build an image |
| ```-it```|  ------------- | Interactive mode, basically you go inside the container or image  |
|  ------------- | ``docker run <image> -p 3000:3000``|  Run an image and expose port 3000 to 3000  |
| -------------  | ``docker run <image> -d`` | run the image and hides the internal terminal
|  ------------- | ``docker system prune`` | Deletes images, networks and all stopped containers|
|  ------------- | ``docker top <container-name>`` | You can check some information about the container |
|  ------------- | ``docker push <image>``  | You can push image into docker hub|
|  ------------- | ``docker pull <image>``| You can download an image into your pc or server or cluster wherever docker is |
|  ------------- | ``docker login``| You can Login into docker hub |


## Docker-compose

Command | Short description |
------------- | ------------- |
``docker-compose up``  |  start and run an entire app on a standalone host that contains multiple services |
``docker-compose down``  |  stop running an entire app|


## Docker-compose parameters

Command | Parameter | Short Parameter description |
| ------------- | ------------- | ------------- |
 ``docker-compose down --remove-orphans`` | ``--remove-orphans`` | delete stopped containers |
