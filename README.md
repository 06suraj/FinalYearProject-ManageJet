ManageJet


ManageJet is a project management site where users can create new projects, add tasks, and update their progress as the work.

Problem

When we work in team on a project , such as open source project, production project, or project in events like Hackathons, We always face one issue that is an dividing tasks among people for a project.
So if you face the same problem we are here to help you! 🤩

Solution

OpTask web-app helps the user to store projects he want along with tasks for each project.
So project can be devided in tasks and can be assigned to individuals.
These projects and tasks can be added, updated and deleted as people work on them.


How to Start

Download or clone this repository. Then in both the OpTask folder and frontend folder use:

npm install
in order to download the dev tools and packages used in this application. We used Prettier to format this code and the project was linted with ESLint. In order to get the MongoDB working, create a ".env" file in your project folder. Create variables in the .env file called MONGO_URL and SESSION_SECRET and set it equal to your Mongo connection string and secret phrase respectively. To run this program open up terminal to the main folder and another terminal window then cd frontend. In main use:

npm test
In frontend use:


Folders
auth: contains Passport.js set up/config files
db: contains a js file that connects the functionality established in the routes to respective collections in MongoDB
frontend: contains all frontend material
public: houses index.js
src: contains javascripts and corresponding stylesheets used to build the site pages (organized by page/component)
routes: contains the js files that run the express routing

npm start
