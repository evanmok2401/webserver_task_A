# Simple Web Server

A web server using Nginx running in a Docker container. Nginx runs as a reverse proxy for two other web servers running on different ports. 

One page can be found at `/` while the other at `/singlish`.

## To Set Up
1. `docker-compose up -d`
2. Visit [localhost](http://localhost)