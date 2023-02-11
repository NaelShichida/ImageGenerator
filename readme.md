#Initial setup

Get your OpenAI key and paste it in an .env file

##Running locally

Essentially to run the website we have two command lines we run to make our pages live. 

node server.js -  'activates' the backend of our code, in this case its the text prompt and sending that over to OpenAI.

npm run dev - runs a build process for our frontend code and only after its run it will set up a localhost:5173 to be able to interact with our pretty HTML

the 8080 port is specific to where the app is listening for the backend and has nothing to do with what URL we use to navigate, in this case localhost:8080 you will see the message 'Cannot GET /'

Hope this helps anyone looking around is just starting out.