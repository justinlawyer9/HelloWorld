## HelloWorld React Docker Project
This project is a containerized React application that displays a custom styled "Hello World" message. It was bootstrapped with Create React App.

## Docker Commands
In the project directory, you can run the following commands to manage the container:

docker build -t username/helloworld .
Builds the Docker image for the application.

It uses the node:18 base image and packages the app for production.

docker run -dp 2000:8080 justinlawyer9/helloworld
Runs the container in detached mode.

Open http://localhost:2000 to view it in your browser.

The app runs internally on port 8080, but we map it to port 2000 on your local machine.

## Available Scripts
In the project directory, you can also run the standard Node commands:

## npm start
Runs the app in the development mode (without Docker).

Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.

You may also see any lint errors in the console.

## npm test
Launches the test runner in the interactive watch mode.

See the section about running tests for more information.

## npm run build
Builds the app for production to the build folder.

It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed!


## Learn More
You can learn more in the Create React App documentation.

To learn React, check out the React documentation.

## Deployment
This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

## Docker Documentation
For more on Docker, visit: https://docs.docker.com/
