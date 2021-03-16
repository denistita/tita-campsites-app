# tita-campsites
## Task
Build a website where users can create and review campgrounds. In order to review or create a campground, you must have an account.

## Run Locally
- Install mongodb
- Create a cloudinary account to get an API key and secret code
- Run this command git clone https://github.com/denistita/tita-campgrounds.git
- cd v11Deployed
- Run npm install
- Double check your ports...that can usually cause errors
- Create a .env file (or just export manually in the terminal) in the root of the project and add the following: DATABASEURL='<url>', API_KEY=''<key>, API_SECRET='<secret>'

  
- Run mongod in another terminal and node app.js in the terminal with the project.
- Then go to localhost:3000.
- run npm run start -dev
- You are now in the dev enviroment and can play around.
## Tech Stack
* HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
* Node & Express: Web API, Body Parser
* MongoDB: Mongoose, Aggregation
* Development: ESLint, Babel, Git, Github,
* Deployment: Heroku   
## Website : https://tita-campgrounds.herokuapp.com/

## Features

* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
* Search campground by name or location
* Sort campgrounds by highest rating, most reviewed, lowest price, or highest price









Tita-Campgrounds app is a Yelp-like clone for campgrounds, campsites, and other outdoor activities. You can create campgrounds, leave comments and photos.  It has user login authentication/authorization.  Tita-Campgrounds is built from restful routing concepts and the semantic ui framework.  The app is connected to MongoDB which is a non-relational database.
