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

