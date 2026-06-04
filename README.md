# Automated Node.js Deployment Pipeline

A simple Node.js and Express application created to demonstrate the fundamentals of web application deployment and CI/CD automation. This project serves as an introductory example of building, running, and deploying a web service using modern DevOps practices.

## Overview

The application hosts a basic web server that responds to HTTP requests with a custom message. While simple in functionality, the primary purpose of the project was to gain hands-on experience with:

* Node.js application development
* Express.js web framework
* Git version control
* GitHub repository management
* Automated deployment workflows
* Basic CI/CD concepts

## Features

* Lightweight Express web server
* HTTP GET endpoint
* Configurable application port
* Easy deployment and testing
* Beginner-friendly code structure

## Technologies Used

* Node.js
* Express.js
* Git
* GitHub

## Application Code

```javascript
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('Hello, World! This is an automated deployment pipeline.');
});

app.listen(port, () => {
  console.log(`App running on http://localhost:${port}`);
});
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/automated-deployment-pipeline.git
```

Navigate to the project directory:

```bash
cd automated-deployment-pipeline
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
node app.js
```

## Testing

Open your browser and navigate to:

```text
http://localhost:3000
```

You should see:

```text
Hello, World! This is an automated deployment pipeline.
```

## Learning Objectives

This project was created to build foundational experience in:

* Backend web development
* Application deployment
* Source control workflows
* CI/CD pipeline concepts
* Node.js server management

## Author

Ronny Early
