# Personal Blog Description Updater
## Description
Blog Description Updater is basically a REST API written in JavaScript using NodeJS that can perform CRUD (CREATE, READ, UPDATE, DELETE) Operations.
Initially you have to create user using the public route, once logged in with user credentials you will get a JWT Token as a return. With that token you can access private routes where you can perform the CRUD Operations.
## Manuals
### Prerequisites:

 1. NodeJS must be install in your system. If you don't have NodeJS installed, download it from `https://nodejs.org/en/download/`.

 2. A MongoDB database in your local system or in cloud. Create free database in cloud at MongoDB Atlas `https://www.mongodb.com/cloud/atlas`

 3. POSTMAN an API Testing Tool. You can download POSTMAN from `https://www.postman.com/downloads/`.
### Instructions
* Navigate to project directory
`  cd /Blog-Description-Updater `.
* Next open terminal in this directory and run `npm install`. This will download all the required packages from npm.
* Create a `.env` file in the project directory. Inside that create three variables named `DB_CONNECT , PORT , TOKEN`. Assign Database URI to `DB_CONNECT` , Port Number to `PORT` else it will run at port 3000 and `TOKEN_SECRET` to any secret. 
* Once you are done with the above steps run `npm start` to start the app.
* Finally open up POSTMAN to test the API.

***


That's all. Hope you understand. 
