# Email-Web-App

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
