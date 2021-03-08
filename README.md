Installation using Docker
------------

1. Install [Git](https://git-scm.com/downloads)
2. Install [Docker](https://docker.com)
4. Copy `docker/.env.template` file to `docker/.env`
6. Run following command
    ```bash
   docker network create jenkins
   docker-compose up -d
    ```   
Usual Access URL: http://localhost:8085
