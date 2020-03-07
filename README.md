# JWT Authentication and Authorization in Nodejs/Express & MongoDB
simple REST API that will enable us to create a user, log in the registered user, 
get the user profile, log out a user from a single device,
and log out a user from multiple devices.

In this simple tutorial, we created a simple REST API that will enable us to create a user, log in the registered user,
get the user profile, log out a user from a single device, and log out a user from multiple devices. 

We will be using Node.js/Express and MongoDB. We shall use MongoDB Atlas, a cloud database service that hosts MongoDB databases to store our data. You can always set up a local MongoDB database however, I will not be talking about installing and configuring a MongoDB database locally in this tutorial.
If you’re mostly interested in the code.

Below is an outline of the steps we will take to accomplish this task. At the end of this tutorial, you should be able to easily include basic authentication and authorization in your Node.js projects.
Create a MongoDB database on MongoDB Atlas.

1. Setup a file structure for the project.
2. Install all the required npm packages.
3. Define the environment variables.
4. Create an express server.
5. Connect to the database.
6. Create the User Model.
7. Create the necessary routes.
8. Create the auth middleware and more routes.
