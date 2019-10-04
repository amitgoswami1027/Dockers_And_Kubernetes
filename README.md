# Dockers_And_Kubernetes
Understanding Dockers and Kubernetes

### WHY USE DOCKERS: Dockers make it really easy to install and run softwares without worrying about setup or dependencies.
### WHAT IS DOCKER: Image : Single file with all the dependencies and configration required to run a program. 

### DOCKER INSTALLATION
* Windows User : Windows Home users will need to install Docker Toolbox which uses VirtualBox. 
* Docs and setup info available here: https://docs.docker.com/toolbox/toolbox_install_windows/
* Release downloads available here: https://github.com/docker/toolbox/releases
* Toolbox will install everything you need including VirtualBox.
* Check your install, In the Docker QuickStart terminal
  *docker run hello-world (This should pull down the test container and print hello-world to your screen.)

*Note*
A major difference between the course lecture using Docker Desktop vs. Docker Toolbox is that you will not be able to use localhost anymore. Instead, you will need to access your machine with the IP address 192.168.99.100

### Commands
### Docker run <<image>> : Docker create <<image>> : Docker run -a <<id of image>>
### Docker log <<id of container>> : Emitt the logs and not going to start the container.
### Docker exec it <<id of contianer>> <<command>>
 
### Installing Docker on Windows 10 Home from scratch (If you dont have Windows Pro verions :) )
### Setting up the Virtual Box: https://golb.hplar.ch/2019/01/docker-on-windows10-home-scratch.html


