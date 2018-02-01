# AI_ChatBot

## STEPS:- 

### Branch 1 - setup the folder and design web interface

1. Download the folder from the branch.
2. Install Nodejs and VSCode
3. Open the folder in VSCode
4. Open the in built terminal from the view option and type the following commands 

   1. cd /path/to/your/folder
   2. npm init -f
   3. npm install express socket.io apiai --save
  
  
### Branch 2 - configure the project for speech recognition

1. copy the contents of the script.js file to the /public/js/scipt.js file in your folder


### Branch 3 - Set up your account in API.AI and configure the project to interact with the api

1. copy the index.js to the index.js in the folder.
2. Visit [API.AI](https://dialogflow.com/) to sign up and create an account
3. Create an agent , import a pre-built agent (small talk) and get the client access token by clicking on the settings for your agent.
4. Add the token in the index.js file and an arbitary string for your session id.

### Branch 4 - configure the project for speech synthesis

1. copy the contents of the script.js and append it to the /public/js/scipt.js file in your folder

### Execute and run the web app

1. execute the app : node --inspect /path/to/your/folder/index.js
2. open a browser and type 127.0.0.1:5000 to run the app.

### Use webhook with API.AI to get current weather status of a city

1. Sign up for heroku
2. Click [here](https://github.com/dialogflow/fulfillment-webhook-weather-python) to get the app and click on deploy to heroku
3. get the URL and enter in the fulfillment section of the agent in API.AI
4. Go to the intents , check the box for use webhook under the fulfillment section




   
