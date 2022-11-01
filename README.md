# Online Store: OpenCart

Docker image for running an online store based on Opencart.

# Install
1. `sudo apt install git make`
1. Clone a repository.
1. Go to repo's folder.
1. `make setup`
1. `make run`


# Commands
You can launch that commands by using `make <название команды>`
1. `setup` - installs Docker and required dependencies.
1. `run` - resolves all dependencies and starts the server.
1. `dockerstatus` - view information about downloaded Docker dependencies.
1. `dockerclean` - complete cleaning of Docker images and data downloaded through it.