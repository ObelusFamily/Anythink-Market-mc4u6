# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Fist you need to clone the repo by typing:

git clone "url to the repo"

Next you need to install docker

To try that docker works, you can run the following command:

docker -v
docker-compose -v

Next move to the project directory and run:

docker-compose up 

the backend will start and the frontend will start.

to test the backend go to 'http://localhost:3000/api/ping'

to test the fronend go to 'http://localhost:3001/register'
