# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

First, [install Docker](https://docs.docker.com/get-docker/).

Verify docker is running by running the following commands in your terminal:

```shell
docker -v
```

```shell
docker-compose -v
```

Run the following command to load Anythink's backend and frontend.

```shell
docker-compose up
```

If Docker is working correctly, the backend should be running and able to connect to your local database. Test this by pointing your browser to http://localhost:3000/api/ping.

Now, check the frontend and make sure it's connected to the backend. If everything is working properly, you'll be able to create a new user at http://localhost:3001/register.