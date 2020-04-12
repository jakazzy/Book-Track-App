# Book Tracker App

Personalize your reading habit and reach your reading goals by keeping track of it using the Book Tracker App.
Book Tracker App enables users to achieve the following:
<br> Add books to be read to the App
<br> Get all the books added to the app
<br> Update the books by adding images of the book cover
<br> Delete books when done reading


# Functionality of the application
<br> This project, involves creation of a simple crud application using AWS Lambda and Serverless framework. 
<br> This application will allow creating/removing/updating/fetching book names. 
<br> Each Book item can optionally have an attachment image. 
<br> Each user only has access to books that he/she has created.

# Get all Books 

The application should stores books items, with the fields:

* `Id` (string) - a unique id for an item
* `createdAt` (string) - date and time when an item was created
* `name` (string) - name of a TODO item (e.g. "Change a light bulb")
* `dueDate` (string) - date and time by which an item should be completed
* `done` (boolean) - true if an item was completed, false otherwise
* `attachmentUrl` (string) (optional) - a URL pointing to an image attached to a TODO item


All functions are already connected to appropriate events from API Gateway.


## Authentication

Authentication is implemented by creating an  Auth0 application 



# How to run the application


## Frontend
The `client` folder contains a web application that uses  the API that  developed in the project.

This frontend works with your serverless application .

To run a client application first edit the `client/src/config.ts` file to set correct parameters. And then run the following commands:

```
cd client
npm install
npm run start
```

This should start a development server with the React application that will interact with the serverless Book application.

# Postman collection

An alternative way to test your API, you can use the Postman collection that contains sample requests. You can find a Postman collection in this project. 

# Tech Stack
<br> AWS Lambda
<br> Serverless Framework
<br> API Gateway
<br> Cloud Watch
<br> Autho
<br> Dynamo DB
<br> React
<br> NodeJS
<br> AWS S3 bucket
<br> CloudFormation
<br> AWS Secrets Manager
