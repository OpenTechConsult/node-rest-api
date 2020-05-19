# Products - Listing : A Node.js REST API using Node.js, Express.js Mongoose and MongoDB

In this application, we build a products listing app using [**Node.js**](https://www.nodejs.org/),  **Express.js**,  **Mongoose** and **MongoDB**. These technologies work well together to easily create performant REST API.  

The reason this combination of technology stack makes a fast and performant REST API application is because Node.js

Node.js is an asynchronous event-driven, non-blocking I/O JavaScript runtime. It is designed to build scalable network applications and support great number of concurrent connections as well as a great number of I/O operations.

In this project, we will build step by step a REST API application that list products information from a database. The database we will be using is MongoDB.

The database used is also an important factor of efficiency of this combination of tech stack. MongoDB is a document database designed for ease of development and scaling.


## Create Express.js Project and Install Required Modules

To start off we will use **express-generator** to rapidly create our application structure. In your terminal window, type the following command

> **npx express-generator node-rest-api**

For earlier versions of Node.js (prior to 8.2.0) **express-generator** needs to be install as a global npm package. It is then launched by calling the **express** command.

> **express node-rest-api -e**

This will create an express project skeleton with **EJS** view template instead of JADE (the default). The EJS view template is used here because we use `-e` option.

Next, cd into the newly generated project and install the dependency modules generated in the `package.json` file.

> **cd node-rest-api && npm install**

After the npm modules were installed, run the command below to launch the server.

> DEBUG=node-rest-api:* npm start

You will see in the terminal a log like this

> node-rest-api@0.0.0 start /OpenTechConsult/sandbox/node-rest-api
> node ./bin/www

Then open your browser at the address http://localhost:3000. If you see the image below it works all fine and the server is ready.

