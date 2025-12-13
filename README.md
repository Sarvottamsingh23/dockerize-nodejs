## How to use this repo

1. Built your docker image using below command:
 $ docker build . my_custom_image:1.0    -> . represemt current directory, my custom image is name of image and 1.0 is tag

2. Then run container based on your imagge using below command:
 $ docker run -p 3000:3000 my_custom_image:1.0  -> first port is local pot and 2nd port is inside container. It will start a conatiner based on your specified image and it will map your container 3000 port to your localhost 3000 port.

3. This a good project example if you are begineer and want to dive in to Docker's world. This is an example of Dockerizing NodeJS app.