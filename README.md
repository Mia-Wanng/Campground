# TexasLife
TexasLife is web application where users can create and review outdoor palces in Texas. In order to review or create a post, you must have an account. This project was edited based on part of Colt Steele's web dev course on udemy.
This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.


## Run it locally
Install mongodb<br />
Create a cloudinary account to get an API key and secret code<br />
Create a Mapbox account and get a token<br />

npm install<br />
Create a .env file in the root of the project and add the following:<br />
MAPBOX_TOKEN=""<br />
DATABASEURL='<url>'<br />
API_KEY=''<key><br />
API_SECRET='<secret>'<br />
Run mongod in another terminal and nodemon app.js in the terminal with the project.<br />

Then go to localhost:3000.

