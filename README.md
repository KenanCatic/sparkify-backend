### sparkify-backend

### Setup 
To run this API on your computer:
-clone the repo 
-create database.config.js file in root of config folder with the following syntax:

module.exports = {
  url:
    "mongodb+srv://username:password@cluster0.ccdtr.mongodb.net/yourDatabaseName?retryWrites=true&w=majority",
};

-get your connection string from MongoDb Atlas
