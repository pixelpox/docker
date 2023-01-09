# docker


## install docker 

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

#add non root as a docker user
sudo usermod -aG docker simon

# check version
docker version

```

## troubleshoot

if you recieve the following error

```
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
```
https://appuals.com/cannot-connect-to-the-docker-daemon-at-unix-var-run-docker-sock/

## install docker-compose

https://docs.linuxserver.io/general/docker-compose
https://dev.to/elalemanyo/how-to-install-docker-and-docker-compose-on-raspberry-pi-1mo
