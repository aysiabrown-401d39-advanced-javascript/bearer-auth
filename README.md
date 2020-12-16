# Class 07: Lab
## Bearer-Auth
### Aysia Brown
### Collaborated with: Tahmina Ringer, Garrett Cintron, Ashley Moore

### Links & Resources
- [CI/CD](https://github.com/aysiabrown-401d39-advanced-javascript/bearer-auth/actions/new)
- [Backend Server](https://aysiab-bearer-auth.herokuapp.com/)
- [Code Fellows Frontend](https://javascript-401.netlify.app/)
*Note*: for the front end provided by CodeFellows you will either need to set the url to your running localhost instance or the published backend url for the server.

### Setup

**`.env` variables**
- `PORT` = port number to host your server
- `MONGODB_URI` = the url to run your mongodb instance
- `SECRET` = your secret code used for your JWT

**Installing Dependencies**
- run `npm i` from within the cloned repo in your terminal to install package.json required dependencies

**Initializing & Start**
- run `nodemon` or `node index.js` to start the server from within your cloned repo in your terminal
- run `mongo` in your terminal to access your databases
    - `show dbs` will show all of your databases within mongo 

**Tests**
- 19/22 of the provided tests are currently passing 
    - the specific user ones "admin" "editor" "user" are the tests that are failing


**Additonal Information**
- Still working on adding another level of security for JWT
