# Getting Started with Create React App
HelloWorld React App with Docker
This is a containerized React application that displays a custom styled "Hello World" message. It demonstrates how to package a React frontend into a Docker image and run it on a specific port.

Project Details
Tech Stack: React.js, Node.js

Containerization: Docker

Author: Justin Lawyer

How to Run with Docker
## 1. Build the Image
Run this command from the root of the project to package the application:
docker build -t justinlawyer9/helloworld .

## 2. Run the Container
Start the container in detached mode. 
This example maps the container's internal port 8080 to your machine's port 2000.
docker run -dp 2000:8080 justinlawyer9/helloworld

## 3. View the App
Open your web browser and go to: http://localhost:2000

How to Run Locally (Node.js)
If you prefer to run the application without Docker:

Install Dependencies:
## npm install

Start the App:
## npm start
(Note: The local version usually runs on port 3000 by default)


