# Final Project
Name: Peter Serrano

Overview of Project: 
This site lets users ask questions and allows other users to vote on questions they like and give answers to the questions. 

Details: 
The user first starts off by either loging in or creating a new account. The Home page will show all created questions in order of vote count. To ask a new question, click the "Ask" button that appears at the bottom of the side navigation throughout the site. The Explore page shows all categories filtered for question that only fall into that category and sorted by vote count decending. Users can edit a specific question to create a new answer by clicking on the question card itself, or by clicking the "Answer" button on a question card. Once inside a question, the question will appear at the top, and all answers will appear in a list below sorted by created date decending. The user who created the question will be able to click on the question card to bring it to the Edit page. The user can then click the Edit button to open an input box to update the question or click the Delete button to permanetly delete the question.

Technologies Used: 
HTML5, CSS, Bootstrap, MaterialUI, JavaScript, React, Redux, NodeJS, Express, Passport

Ideas for future improvement: 
I would like to add both a positive and negative voting for answers similar to Yahoo Answers. I would also want to let users modify the title of a question for more freedom of use. 

# Setup Instructions:
To setup, run all required client and server scripts below. Create a database with the database information found in the Server > Data > db.js file. Create the database schema using the database create and insert statements found in Server > Data > sql.db

## Client Setup:
* Required
** Optional

npm install -g create-react-app   *only once on machine
npx create-react-app [appName]    *create new react app template
npm install axios                 *allow API requests to server

### Client Scripts:

npm start                         *Starts app server in full mode
npm run build                     *Create production build
npm test                          **Starts in debug mode


## Server Setup:
* Required
** Optional

npm install -g npm                 *latest node and npm
node -v                            *confirm newest version
npm -v                             *confirm newest version
npm init                           *create node server
npm init -y                        **create node server all defaults
npm install --save express         *adds express module
npx express-generator [name]       **create express server template
npm install --save-dev nodemon     **adds nodemon module
npm install --save uuid            *adds uuid module
npm install --save ejs             **adds ejs express template engine
npm install express-promise-router *adds express promise router
npm install --save cors            *handles client requests
npm install bcrypt                 *hash passwords
npm install express-session        *initializes session state
npm install express-flash          *
npm install passport passport-local *keeps user session

### Server Scripts:

npm start                           *starts server


# HTTP Request Types:

HTTP Requests:

GET  /users         finds all users
POST /users         creates a user
GET  /users/:id     finds user details
DELETE /users/:id   deletes a user
PATCH /users/:id    updates portion of a user
PUT /users/:id      updates a user

