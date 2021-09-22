# Email-Web-App

To write an Email System as a Single Page Full Stack Web Application using React, Node.js, Express, PostgreSQL, and Material-UI.

Note: This web app is highly functional in a mobile view.

More information about this project at https://www.claireruffingportfolio.com/post/email-web-application 

## Key Technologies

Frontend: React and Material-UI

Server: Node.js and Express

Storage Tier: PostgreSQL database

## Installation Requirements

To install node packages:

  $ npm install

To run the Web App: 

  $ npm start
  (need to run npm start from within the backend folder and within the frontend folder)

To run tests: 

  $ npm test

To run the linter: 

  $ npm run lint

To generate a Canvas submission ZIP: 

  $ npm run zip
  
To reset Docker (if you run into problems with database)

  $ docker stop $(docker ps -aq)
  $ docker rm $(docker ps -aq)
  
This is a desktop and mobile app. To view it as if you were on your phone, right click the page, click Inspect, and click the mobile view.

## Preview

![alt text](https://github.com/claireruffing/Email-Web-App/blob/main/photos/emailwebapp.png)


