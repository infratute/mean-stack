# Mean Stack - Customer Contact List Application

This Customer Store Contact is a very basic Mean Stack application developed using MongoDB, Express, Angular and Node.js.
This application demonstrates the MEAN stack deployment and CRUD operations on MongoDB using RestAPI.

## Prerequisites

- In order to run this app, you need Node.js, which is javascript runtime installed on our machine. Follow the instructions given by your instructor for installing the node.js during your course delivery, for installing the node.js application on you rlocal machine.

- we also need to have MongoDB. We can with choose to have mongodb-CE(Community Edition) installed on your local machine

OR

- Choose to use the MongoDB free tier service. Follow the instructions from your course.

## Getting Started

You may choose to either fork the entire project and test it or build the project from the scratch using the specific files only.

### Setup server

Open the command window in the folder where you have unzip the mean-stack-application repository.

Rename **.env_example** file to **.env** and add following code in the file in case you are using local MongoDB.

`DB_CONNECTION=mongodb://localhost:27017/customerDb`

Otherwise, if you are using cloud based MongoDB service then you the connection string you get from there instead of local one.

Now run following command to install all the package dependencies.

```
npm install
```

### Setup Client application

Now move to client folder.

```
cd client
```

Now run following command to install all the package dependencies for client.

```
npm install
```

### Run Client & Server

Run following command to start the client application and server concurrently.

```
npm run dev
```

> Server will listen at URL - `http://localhost:3000/Customers`
> Navigate to `http://localhost:4200/`to access the client application.

## Docker Support

Docker image of this app is available at my docker Hub registory. You can pull the image from [meanstack-app](https://hub.docker.com/repository/docker/sanjaysaini2000/meanstack_frontend) repository.

## Built With

- [Node.js v10.15.1](https://nodejs.org/en/) - The .Net Core framework used
- [Angular CLI v7.3.1](https://cli.angular.io/) - This project was generated with
- [VS Code](https://code.visualstudio.com/download) - The Code editor used

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
