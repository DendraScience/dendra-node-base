# Dendra Node Base

Dendra Node base image with NPM dependencies for job scripts.

## Instructions

## To build and publish the Docker image

1. Make this project directory the current directory, i.e. `cd dendra-node-base`.

2. Build the project `docker build -t dendra:dendra-node-base .`.

3. Tag the desired image, e.g. `docker tag f0ec409b5194 dendra/dendra-node-base:latest`.

4. Push it via `docker push dendra/dendra-node-base`.
