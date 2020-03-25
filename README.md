# _NMP

This `docker-compose.yml` file will provision nginx, PHP, and MySQL containers
suitable for local development.

    # copy the example env file and edit the values as necessary
    cp env.example .env
    vi .env

    # then provision and run the containers
    docker-compose up -d

    # stop the containers
    docker-compose stop

    # delete the containers (include -v to also delete data volume)
    docker-compose down

