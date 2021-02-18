# Mongo BI Connector

## Setup

Follow <https://docs.mongodb.com/bi-connector/current/connect/powerbi>. When setting up the ODBC Connector in window it is important to select the database otherwise PowerBI is not able to handle it.

I had to restart the containers to see the my test DB appear in PowerBI

## Ports

- <http://localhost:3307>: BI Connector
- <http://localhost:8081>: mongo-express (UI to work with the DB)

## Run it

Be sure docker is installed and running and execute `docker-compose up` or `docker-compose start` in this folder.

## Thanks

- Ryanhs for the container and the initial docker compose file <https://github.com/ryanhs/mongodb-bi-connector-docker>