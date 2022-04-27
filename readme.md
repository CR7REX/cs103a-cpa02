# Soccer Player Database

## How to use

### Register

![register](/Users/rex/Desktop/cs103a-cpa02/Screenshots/register.png)

### Login

![login](/Users/rex/Desktop/cs103a-cpa02/Screenshots/login.png)

### Main Page

![main](/Users/rex/Desktop/cs103a-cpa02/Screenshots/main.png)

### Search

![search](/Users/rex/Desktop/cs103a-cpa02/Screenshots/search.png)

## How to Setup

Both [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/try/download/community) are required for the application to run so make sure you have these installed. 

*Versions*

* Node.js - v12.18.0 or higher
* MongoDB - v4.4.1 or higher

Clone the repository to your local system then in the terminal at the root folder run: 

```bash
npm install
```

to acquire the node_Modules and dependencies for this project.

### Usage

*If Node.js and MongoDB are installed locally...*

In the terminal go to the drive where MongoDB is installed and run this command

```bash
mongod
```

then naviagte back to the project root folder and run:

```bash
node app.js
```

The Express server should then start on port 3000 and the website can be viewed on your LocalHost.
