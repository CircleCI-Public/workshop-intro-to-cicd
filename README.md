# Workshop: CI/CD with CircleCI

This repo hosts the codebase for the workshop - CI/CD with CircleCI.

To follow along, checkout the `main` branch.

For the finished solution, checkout the `complete` branch.

## The application

The application is a minimal Node.JS app with two tests and a Dockerfile to build a Docker image out of it.

### To run locally

- `npm install`
- `npm run test`
- `npm run start` 
- Visit https://localhost:5000 in your browser.

#### Setting up the Complete project on CircleCI

- For the project :) 
- Login to [CircleCI](https://app.circleci.com) 
- configure the new project with CircleCI, keeping the config as is
- Set up environment variables with your Docker Hub credentials: `DOCKER_LOGIN` and `DOCKER_PWD` for your username and password.