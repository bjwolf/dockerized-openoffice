# Dockerized OpenOffice

![](openoffice_and_docker.png)

## Introduction

Run OpenOffice in docker container? Awesome :+1: 

From Docker Index
docker pull bjwolf/ dockerized-openoffice:v1
or Build yourself
git clone https://github.com/bjwolf/dockerized-openoffice.git
docker build --rm -t bjwolf/ dockerized-openoffice:v1 .
Run
Interactive mode:
docker run -i -t -p 6080:6080 bjwolf/ ockerized-openoffice:v1
Daemon mode:
docker run -d -t -p 6080:6080 bjwolf/ desockerized-openoffice:v1



![](screenshot.png)

## Usage

```
docker run -d -p 6080:6080 tobegit3hub/dockerized-openoffice
```

Then go to <http://127.0.0.1:6080/vnc.html> for OpenOffice.

## Reference

* <https://github.com/fcwu/docker-ubuntu-vnc-desktop>
* <https://www.liberiangeek.net/2013/08/apache-openoffice-4-0-releasedheres-how-to-install-it-in-ubuntu/>
* <http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/>
* <http://stackoverflow.com/questions/16296753/can-you-run-gui-apps-in-a-docker-container>
