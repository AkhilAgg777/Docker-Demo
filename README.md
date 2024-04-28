# docker commands
     1.)To check version
      docker --version

     2.)To check list of images
      docker images

     3.)To build container for image
     docker run <imagename>

     4.)List of all container
     docker ps -a
  
     5.)For active container
     docker ps

     6.)To remove image
     docker rmi <imageid>

     7.)To remove container
     docker rm <containerID>

     8)Force delete
     docker rmi <iamgeid> -f

     9)To build image from docker file
      docker build -t <ImageNameInLowerCase> <imagelocation> 

     10)To run container
      docker run --name <sample-web-app-container(containerName)> -p 9000:80 <sample-web-app:1.0.0(imageName)>
