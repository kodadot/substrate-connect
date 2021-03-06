## One single local Polkadot node

Docker compose file to run a docker container of the latest Polkadot master branch.

Before you can run this script, you need to install Docker and 'Docker Compose' on your machine.
Please follow the steps described here (including the prerequisites): https://docs.docker.com/compose/install/

### Usage:
**1. BUILD:** Run `docker-compose pull && docker-compose up` to pull the latest docker imaged and run the Docker image of the latest Polkadot master.
**2. INFO:** Run `docker ps` to get a list of Docker containers running in the background including their mapped ports on localhost
**3. QUIT:** Run `docker-compose down` to stop and remove all running containers.

Provided endpoint for localhost: Development version of Polkadot Master on
**ws://127.0.0.1:9944/**

Find more Docker images of Polkadot https://hub.docker.com/r/parity/polkadot/tags