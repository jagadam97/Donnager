# Donnager - Personal Server
## _Donnager virtually means "Thunderer"_

[![Donnager.jpg](media/Donnagermd.jpg)](https://expanse.fandom.com/wiki/Donnager)

Donnager is my personal server with following use cases

- Personal Media Server
- Personal Downloader
- Personal Web IDE
- Few VM for testing

## Why are you creating a Repo for your personal server?

As this is experimental server this documentation will be helpful for me when needs be. Rather than sitting like this kid

<img src="media/frustratedkid.webp"  width=40% height=40%>

# Containers & VMs
## [Maintainarr](Maintainarr/)
Built on [alpine](https://alpinelinux.org) Container with [Docker](https://www.docker.com/) running with [Portainer](https://www.portainer.io/). Contains following Docker Containers

| Container | Website |
| ------ | ------ |
| Sonarr | https://sonarr.tv |
| Radarr | https://radarr.video|
| Bazarr | https://bazarr.media|

## [Downloadarr](Downloadarr/)
Built on [alpine](https://alpinelinux.org/) Container with [Docker](https://www.docker.com/) running with [Portainer](https://www.portainer.io/). Contains following Docker Containers

| Container | Website |
| ------ | ------ |
| Qbittorrent | https://qbittorrent.org |
| FloodUI | https://flood.js.org|
| Qbitmanage | [StuffAnThings/qbit_manage](https://github.com/StuffAnThings/qbit_manage)|
| Jdownloader | https://jdownloader.org|

## [Indexarr](Indexarr/)
Built on [alpine](https://alpinelinux.org/) Container with [Docker](https://www.docker.com/) running with [Portainer](https://www.portainer.io/). Contains following Docker Containers

| Container | Website |
| ------ | ------ |
| Jackett | [Jackett/Jackett](https://github.com/Jackett/Jackett) |
| Prowlarr | [Prowlarr/Prowlarr](https://github.com/Prowlarr/Prowlarr)|
| FlareSolver | [FlareSolverr/FlareSolverr](https://github.com/FlareSolverr/FlareSolverr)|
  
# Steps to install Docker Engine & Compose on Alpine Linux

## 1. Run Alpine update  
First, on the command line of this Linux, run the system update command to refresh the repository cache.
```sh
apk update
```
## 2. Install Docker Engine and Compose
The packages to install Docker are already in the repository of Alpine Linux, hence we don’t need to add anything. Just use the APK package manager and install the required packages.
```sh
apk add docker docker-compose
```
## 3. Start and enable Docker Service
By default, the Docker service is not activated to run by the system automatically with every boot. Hence we have to do that manually, here are the commands to follow.
```sh
rc-update add docker boot
service docker start
```



```YAML:Maintainarr/Sonarr-Dockercompose.yml

```