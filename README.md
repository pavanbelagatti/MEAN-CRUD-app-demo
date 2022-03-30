# MEAN-CRUD-app-demo

## Pre-Requisites
Prerequisites
In order to run this app, you need Node.js, which is javascript runtime installed on our machine. So download and install the latest Node.js available from this [link](https://nodejs.org/en/).

we also need to have MongoDB installed on the machine. You can download and install MongoDB community edition free from this [link](https://www.mongodb.com/try/download/community).

OR

if you dont want to install MongoDB on your machine then you can use cloud hosted MongoDB service from this [link](https://cloud.mongodb.com/user#/atlas/login). You have to create account and use free tier to host your data.

In this app, we will connect our application to our local MongoDB database (localhost 27017 port) using Mongoose package, with connect() function referencing to mongoose, with MongoDB Database URI passed as argument to the function.

*localhost 27017 port is the default port the MongoDB database server listens to the commands*


## How to playaround?

### Clone the repository:
Clone the repository by using the command `git clone https://github.com/pavanbelagatti/MEAN-CRUD-app-demo.git`

### Install the dependencies
Use the command `npm install` on your terminal to install the required dependencies.

### Backend part:
Go to the backend folder with `cd backend`command on your terminal

Run `npm start` from the backend folder

You should see the message on your terminal as below,

> Connected to port 3000

> Database sucessfully connected:) 

### Frontend part:
Open a new terminal from and go to the frontend folder with the command `cd frontend` and run `ng serve` for a dev server. 
Navigate to http://localhost:4200/. 

### Install the dependencies
Use the command `npm install` on your terminal to install the required dependencies and packages.

Start the angular frontend with the command `ng serve` from your frontend folder.

The app will automatically reload if you change any of the source files.
