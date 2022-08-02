**[setting local environment- `@vanessa-cooper`]:**
# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Setting up docker environment
**step1** _Please open the repository Navi invited you to (https://github.com/ObelusFamily/Anythink-Market-2u0og) clone it to your local machine, and let me know when you're done :)

**step 2** _Create a branch,makee some changes in codeowner file and push changes in github and eventually pull request to merge it

**step 3** Install docker from https://docs.docker.com/get-docker/ 
**step 4**-  you will be prompted to update kernel linux, do it with the given  link
**step 5**-  Great! You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
Then, run docker-compose up (can do it from vs code terminal) from the project root directory to load Anythink's backend and frontend

**step 6**-If Docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping

**step 7**-Now, it’s time to check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.