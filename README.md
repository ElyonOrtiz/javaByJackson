# JavaByJackson 

this is a repository of studies of java. here I have else some case use of docker and postgresql  

## Attention  

In case of use of docker-desktop in linux the follow code should be add in script "user: "${UID}:${GID}".just discomment the code in script 

## Docker Engine x Docker Desktop

Docker desktop use a virtual machine same in environment linux. So if you installed Docker desktop probably you are have difficulty of to execute the command above.
I had he some problems. To resolve this problem I had uninstall Docker desktop, although the environment variable that map the daemon yet are set with docker desktop.
You can resolve your problem by running the following command:

### export DOCKER_HOST=unix:///var/run/docker.sock

docker info

Client: Docker Engine - Community  

 Version:    26.0.1  

 **Context:    default**  

 Debug Mode: false  

 Plugins:  
  buildx: Docker Buildx (Docker Inc.)  

    Version:  v0.13.1  

    Path:     /usr/libexec/docker/cli-plugins/docker-buildx  

  compose: Docker Compose (Docker Inc.)  

    Version:  v2.26.1  

    Path:     /usr/libexec/docker/cli-plugins/docker-compose  
    


