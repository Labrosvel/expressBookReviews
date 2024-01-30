# Project Scenario

In this project I assumed the role of a back-end developer working for an online retailer selling books. I have been tasked with developing a server-side application that stores, retrieves and manages book ratings and reviews.

My server-side application provides the following features and capabilities to allow users to:
- Retrieve a list of all books available in the bookshop
- Search for specific books and retrieve their details based on the book’s ISBN code, author names and titles
- Retrieve reviews/comments for specified books
- Register as a new user of the application
- Login to the application
- Add a new review for a book (logged in users only)
- Modify a book review (logged in users can modify only their own reviews)
- Delete a book review (logged in users can delete only their own reviews)
- (Multiple users) Access the application at the same time to view and manage different book reviews simultaneously

As is the case with most software development projects, different people in the team work on different parts of the application. Another front-end developer in my team is working on the web-based client-side application that will communicate with my server-side application using REST. Therefore my job was to implement my server-side application as a RESTful web service. A software architect on my team has written the skeleton code for my server-side application using Node.js and Express.js.

I complete the project by forking the skeleton code into my own repo, clone it locally into my development environment, and develop the code further to implement the CRUD capabilities listed above as HTTP methods in my Express server and test them using Postman. I also implement Session and JWT authentication to allow only logged in users to perform certain operations.

Furthermore I enhance my code using Promises, Callbacks or Async/Await functions to allow multiple users to interact with the application simultaneously and not have to wait for each other’s operations to complete.

# Project Breakdown
* Forked the Git repository to have the server side application code I needed to start
* npm install the necessary packages and Postman Login to test the API endpoints
* Implemented Authentication for using the Book Review application
* Accessed the book review application as general purpose user and register user
* Used Async/Await - Promises with Axios in Node.js for each of the four CRUD Operations

# Book Review Application
In this project, I built a server-side online book review application and integrated it with a secure REST API server which used authentication at the session level using JWT. I then tested my application using Async-Await functions.

# Objectives
1. Create APIs and perform CRUD operations on an Express server using Session & JWT authentication.
2. Use Async/Await or Promises with Axios in Node.js.
3. Create REST API endpoints and test them using Postman.
