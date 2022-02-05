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

On your VS Code, Open the command window in the folder where you have unzipped the mean-stack application repository.

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
Open a terminal and ensure that you are in the directory within which your entire project is contained. Now run

```
node server.js
```
Open another terminal and ensure that you are in the client directory. Now run
```
ng serve --open
```
> Server will listen at URL - `http://localhost:3000/Customers`
> Navigate to `http://localhost:4200/`to access the client application.
