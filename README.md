# This is my docker cheatsheet

Basically I created this repo just to remember better the docker commands instead of saving them in only one place I have decided to leave it here on github.

## Docker basic commands: 

``docker system prune`` Deletes images, networks and all stopped containers
<br/>
``docker top <container-name>`` You can check some information about the container
<br/>
``docker push <image>`` You can push image into docker hub
<br/>
``docker pull <image>`` You can download an image
<br/>
``docker login`` You can Login



| Parameter | Command | Short description |
| ------------- | ------------- | ------------- |
| ------------- | ``docker ps`` | You can see all images  |
| ------------- | ``docker build <directory>`` | you can build an image |
| ```-it```|  ------------- | Interactive mode, basically you go inside the container or image  |
|  ------------- | ``docker run <image> -p 3000:3000``|  Run an image and expose port 3000 to 3000  |
| -------------  | ``docker run <image> -d`` | hides the terminal
|  ------------- | ``docker rmi <image>`` | removes an image |
|  ------------- | ``docker rmi <image>`` | removes an image |
|  ------------- | ``docker rmi <image>`` | removes an image |
|  ------------- | ``docker rmi <image>`` | removes an image |
|  ------------- | ``docker rmi <image>`` | removes an image |
