# Support Desk Backend in nodeJS

> API Developed as the first part of a larger backend API for a support desk system.
> Single model `user` as a starter backend.

# Table of Contents

- [Support Desk Backend in nodeJS](#support-desk-backend-in-nodejs)
- [Table of Contents](#table-of-contents)
- [Instructions](#instructions)

# Instructions

- Run `npm install` to install dependencies in the support-desk directory
- Modify the `dotenv_example` file
  - Rename to .env
  - Assign Port Number to run server on
  - Set up a MongoDB Database on [MongoDB Atlas Cloud Database](https://www.mongodb.com/cloud/atlas)
    - Enter the connection string in the `.env` file
  - Enter your JWT Secret
  - While in the support-desk directory, run `npm run start` to start the server
  - Import the routes into Postman from the `` attached file exported from Postman
  - Use [Postman](https://www.postman.com/) to test the routes
  - Import the `node backend authentication API.postman_collection.json` file into postman to test routes
