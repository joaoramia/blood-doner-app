You need to have Node.js and Mongodb installed to run this application. Please see https://nodejs.org/en/download/ and https://docs.mongodb.com/manual/installation/ as a reference

Please make sure you have the Mongodb service running. Note that the mongoose.connect method is pointing to 'mongodb://localhost:27017/blood-donor-jramia' for this application - make sure to change it however you prefer

Steps:
run commands (once inside of /Code):
$npm install
$webpack (if you don’t already have it locally installed, simply run npm install webpack -g) Webpack will generate/update bundle.js
$npm test
$npm start

Go to http://localhost:8080 and see the application running (check port on /Code/server/main.js if you want/need to change it)