# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Having Docker installed makes it easier for us to run things locally.
To verify that Docker is ready by running the following commands in your terminal:

`
  docker -v 
`


`
  docker-compose -v
`

Then run `docker-compose up` from the project root directory to load the Anythink backend and frontend.

If the docker is working properly, the backend should be running and able to connect to your local database.

Probemos esto apuntando su navegador a http://localhost:3000/api/ping



Now, it's time to check the frontend and make sure it's connected to the backend.

If everything works fine, you will be able to create a new user at http://localhost:3001/register

It looks like your environment is ready! 😀

