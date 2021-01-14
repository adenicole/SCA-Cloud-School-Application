# SCA Cloud School Technical Assessment #

## Exercise 1 Solution ##
The following steps can be carried out to test this project on your local environment:
_Steps tested on an Ubuntu 20.04 server deployed on an AWS EC2 instance: should work on most Unix based OSes_

# Got to https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04 to install docker or google for your specific OS
 
- Clone the repo using `git clone https://github.com/adenicole/SCA-Cloud-School-Application.git`
- Change into working directory using `cd SCA-Cloud-School-Application`
- Change branch into `stable` using `git checkout stable`
- Change into directory `docker` using `cd docker`
- To build the docker image from the Dockerfile, run `sudo docker build -t <image-name>:<tag> .` (Do not forget the '.')
- To start up the docker container and make it accessible on a preferred port, run `sudo docker run -p <preffered-localhost-port>:1234 -d <image-name>:<tag>`
- Go to `localhost:<preffered-localhost-port>` to access the webpage


## Docker Hub Link ##
https://hub.docker.com/repository/docker/adenicole/adenicole-sca-cloud
