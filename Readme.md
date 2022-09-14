# Donnager - Personal Server
## _Donnager virtually means "Thunderer"_

[![Donnager.jpg](media/Donnagermd.jpg)](https://expanse.fandom.com/wiki/Donnager)

Donnager is my personal server with following use cases

- Personal Media Server
- Personal Downloader
- Personal Web IDE
- Few VM for testing

## Why are you creating a Repo for your personal server?

As this is experimental server and i would like to get back to documentation when needs be. Rather than sitting like this kid

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
