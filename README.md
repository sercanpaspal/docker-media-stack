# Jellyfin Docker Media Server Stack

This repository contains pre-made settings for setting up a media server with Docker Compose. Docker Compose is a tool that allows you to define and manage a set of Docker containers in a single file. In this case, the containers that make up the media server are Jellyfin, Sonarr, Radarr, Prowlarr, and Transmission.

### Jellyfin
Jellyfin is a media server that allows you to enjoy your media. You can store and play all of your media, including movies, TV shows, music, and photos. Jellyfin can be used on a variety of devices, including web browsers, smart TVs, game consoles, and mobile devices.

### Sonarr
Sonarr is a tool that helps you watch TV shows. Sonarr watches your watchlist for TV shows, and then downloads and transfers them to your storage location. Sonarr also allows you to select the quality and download time of TV shows.

### Radarr
Radarr is a tool that helps you watch movies. Radarr watches your watchlist for movies, and then downloads and transfers them to your storage location. Radarr also allows you to select the quality and download time of movies.

### Prowlarr
Prowlarr is a tracker aggregator for Sonarr, Radarr, and other download managers. Prowlarr helps you find new torrents for your download managers, and manage them. Prowlarr is compatible with a wide variety of download managers, and is easy to use.

### Transmission
Transmission is a torrent client. Torrents are a file-sharing protocol used to download and share files. Transmission is an easy-to-use torrent client that offers a variety of features.

## Installation
To install this media server, you will first need to install Docker and Docker Compose. Once you have installed Docker and Docker Compose, you can follow these steps:

- Clone this repository.
- Run the `docker-compose up -d` command.
- Your media server will be up and running in a few minutes.

## Usage
Once your media server is up and running, you can access the Jellyfin web interface. To access the Jellyfin web interface, open a web browser and go to http://localhost:8096.

In the Jellyfin web interface, select a storage location where you want to store your media. Once you have selected a storage location, you can add your media to Jellyfin.

Once you have added your media to Jellyfin, you can watch your media on a web browser, smart TV, game console, or mobile device.

## Customization
To customize Jellyfin, you can use the Settings page in the Jellyfin web interface. On the Settings page, you can change a variety of settings for your media server.

## Support
If you have any problems with this media server, please file an issue on the issue tracker: [https://github.com/sercanpaspal/docker-media-stack](https://github.com/sercanpaspal/docker-media-stack/issues)
