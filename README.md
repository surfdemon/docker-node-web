# Base Docker Image Container with Node.js and Express
This is a simple Dockerfile that sets up a base image for a Node.js application using Express. It includes the necessary steps to install Node.js, copy the application files, install dependencies, and expose the application on port 3000.

## Usage 
To use this make sure you have Docker install on your machine. 

Then to build run the following command in your terminal:
```bash
docker build -t my-nodejs-app .
```

Then to run the container use the following command:
```bash
docker run -p 3000:3000 -d my-nodejs-app
```

You should then be able to view http://localhost:3000 in your browser or use the following command to check it is running 
```bash
curl http://localhost:3000
```

