# Expekt NGINX

Reverse proxy for accessing Expekt.

## Structure

This project is using NGINX, in order to add some rules or redirect requests.
It is delivered as a docker image.

## Build

To build the docker image: `docker build -t expekt-nginx .`

## Execution

To run the reverse proxy: `docker run --name my-nginx -p 80:80 -d expekt-nginx`

## Usage

Simply run the docker container, and access the environment: http://localhost
