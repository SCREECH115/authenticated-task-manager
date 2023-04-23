# Authenticated Task Manager

The project is dedicated to the task manager, which is written in React technology and uses many other dependencies. The project uses an authenticator, databases, anyone can set up an account and manage their tasks. Sensitive data in the form of a password is hashed.

## Tech stack

The project was created using various technologies such as:
- React
- Node.js
- PostGresSQL
- CSS

## Dependencies:
- Express
- uuid v4
- cors
- pool
- bcrypt
- jsonwebtoken

## Installation Guide
1. Clone repository `https://github.com/SCREECH115/authenticated-task-manager`
2. Open project/terminal and go to `client` folder and run it by `npm start`
3. The same way go to `server` folder and run it by `npm start`
4. The server should be located at `localhost:8000` and the Task Manager page at `localhost:3000`
5. Download and install PostGreSQL or another database program, then import commands from the [data.sql](https://github.com/SCREECH115/authenticated-task-manager/blob/main/server/data.sql) file from the repository. (todoapp database and two tables `users` and `todos`)
6. That's it, the app should be running and fetching data from the database

## Node.js
The repository does not have `node_modules`. To do this, in the `client`, `server` and `depoyed-to-do-app` directories, create these folders using the terminal and the `npm install` command.
Node is necessary to run the application.

## Instructions For Use
After successfully installing the project, you can go to the local page `localhost:3000`, where you will see the login menu.
In order to create an account, go to the `Sign up` tab and then create an account with new data.
You will automatically be redirected to the Task Manager where you can manage your tasks.

### Additional information
As of the application deployment day, I'm just learning technologies like React and Node.js, I'm glad that along with the documentation and tutorials on the internet, I was able to learn a lot of things thanks to this application.

### Screens
![alt text](https://i.imgur.com/xIMhOra.png)
---
![alt text](https://i.imgur.com/OjKWdrv.png)
---
![alt text](https://i.imgur.com/SrXsEhE.png)
---
![alt text](https://i.imgur.com/iGFo87T.png)
---
![alt text](https://i.imgur.com/r2pftoW.png)
