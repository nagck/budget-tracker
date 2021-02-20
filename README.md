# Budget-Tracker
## Description
The Budget Tracker application allows users to add expenses and deposits to their budget with or without a data/internet connection.
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

As part of U of T SCS Coding Bootcamp Homework assignment, code that works online only was was already provided. The assignment was to add functionality to existing Budget Tracker application to allow for offline access and functionality. This was accomplished using IndexedDB, PWA manifest, and service worker. The application has been deployed on Heroku using MongoDB Atlas as the database.

- Link to the application on Heroku: https://infinite-falls-67891.herokuapp.com/
- Link to the GitHub repository: https://github.com/nagck/budget-tracker/

## User Story
* AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

When brought back online:
  * Offline entries should be added to tracker.

## Technologies Used: 
* Node.js, Express
* MongoDB NoSQL database
* Mongoose Object Data Modeling (ODM) library for MongoDB and Node.js
* JavaScript, CSS, HTML
* npm
* IndexedDB, PWA, service worker


## Installation

1. To install this code, download the zip file and extract the files to a designated directory on your node.js server without changing the directory/folder structure, or use GitHub's guidelines to clone the repository. 
2. Once the code is extracted, navigate to the project directory and execute 'run npm install' command to install node.js and related dependencies.
3. Update MongoDB connection information to point to your instance of MongoDB.

Also, the application is currently hosted on Heroku and you can access it at 
https://infinite-falls-67891.herokuapp.com/

## Usage 
The application can be invoked by using the following command and follow the instructions after that:

```bash
node server.js
```
Point your browser to http://localhost:3000/ to start using the application.  
## Screenshots of the application:

![image](assets/budget-tracker01.png)


## Link to functional application deployed on Heroku:

https://infinite-falls-67891.herokuapp.com/

## Credits

- The application has been developed using JavaScript, Node.js, Express, MongoDB, Mongoose, PWA, IndexedDB, service worker. 

- Sincere thanks to my course instructors Ed (Edward Apostol), Herman (German Arcila) and Anas (Anas Qazi) for teaching and helping me in acquiring HTML/CSS/JavaScript/Node.js/MongoDB/Mongoose skills. And of course thanks to my fellow students for sharing valuable tips and tricks on Slack study groups.

- Here are some websites that I referred to develop the code:
* https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API/Using_IndexedDB#open
* https://developers.google.com/web/ilt/pwa/introduction-to-service-worker
* https://web.dev/add-manifest/
* https://www.mongodb.com/
* https://mongoosejs.com/
* https://www.npmjs.com/
* https://www.npmjs.com/package/express
* https://www.w3schools.com/nodejs/
* https://developer.mozilla.org/en-US/docs/Web/JavaScript
* https://www.w3schools.com/js/default.asp

## License
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.<br>
![badge](https://img.shields.io/badge/license-mit-brightgreen)<br />
## Feedback
Feedback is always appreciated. If you are interested in fixing any issues and contributing directly to the code base, please provide at:
- GitHub Pull Requests: [https://github.com/nagck/budget-tracker/pulls](https://github.com/nagck/budget-tracker/pulls)
- GitHub: [https://github.com/nagck](https://github.com/nagck)

---
