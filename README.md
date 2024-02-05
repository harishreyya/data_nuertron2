# Data Nuetron Assignment

## Introduction
A mern stack application for managing tasks along with resizing boxes. You create, view, update, and delete tasks.

## Features
The key features of the application.

- Resizing the box size with curser
- APIs for retrieving task statistics Adding new tasks and editing them

## Deployed link
[link](https://resize-dataneutron.vercel.app/)

## DEMO VIDEO LINK
[link](https://drive.google.com/file/d/1Qa3yw_YwoBNul3eDbAxkxfGTj19P77Wl/view?usp=sharing)

## Installation or How to run the app
I created a cloud database using MongoDB Atlas. So, if you want to run our code then please read the instructions below :
- Clone our repository `https://github.com/harishreyya/data_nuertron2.git`
- Open the code in your VS code and open the terminal
- Now run `npm install` or `npm i` which will install all the required packages of node
- After installation, now run `npm run server` and  you will see `server is listening on 5090` 
- Simultaneously, open a new terminal and run `cd frontend` by which you get into the frontend folder
- Now here, run `npm install` or `npm i` which will install all the required packages of react as well
- After installation, now run `npm start` and  you will see a new window opening in the default browser which is running on port `http://localhost:3000`
- Open MongoDb compass and URL `mongodb://localhost:27017/DataNuetron` which will create a database collection named DataNuetron
- Now you see the app running, where you can create tasks and explore.


## API Endpoints
Backend Applications provide a list of API endpoints
- GET /tasks - retrieve all tasks
- POST /tasks/add - create a new task
- PATCH /tasks/update/:id - editing task's description
- DELETE /tasks/delete/:id - deleting a task
- GET /apiCallsCount - count of times you added or edited task

## Technology Stack
 Brief overview of the technologies used in the project.

- MongoDB
- Express JS
- React JS
- Node JS
 
 ### Dependencies and packages

#### Backend
- `mongoose`<br/>
  connecting MongoDB to the Node js server
- `nodemon`<br/>
  It monitors your project and automatically restarts when it detects any changes.
- `cors`<br/>
  allowing any browser to permit the loading of resources

#### Frontend
- `Axios`<br/>
  JavaScript library to make HTTP requests or fetch data

#### Cloud Deployment

- `Render`<br/>
used Render for deploying the APIs in Node JS (Backend)
- `Vercel`<br/>
used Vercel for deploying React JS (frontend)
