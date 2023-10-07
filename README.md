# Infra
This repo is responsible for managing the infrastructure and orchestration of all of the project repos, including services and their associated databases. 
It is a fundamental part of our E-commerce platform within the [Distributed Playground](https://github.com/DistributedPlayground) project. See the [project description](https://github.com/DistributedPlayground/project-description) for more details.

## Architecture
As of now, *infra* is only set up to manage containers in a local environment. In the future, this will be updated to include terraform definitions of infrastructure for a cloud dev environment.

## Running the Services:
* Start the services: `docker compose up --build`
* Stop the services: `docker compose down`
* Reset the services: `docker system prune && docker volume prune`