# MyOwnSpace
Lets share our thought.

Description
Build an API for a social network web application using MongoDB, Express.js, and Mongoose. This project demonstrates how to manage large amounts of unstructured data, allowing users to share thoughts, react to friends’ thoughts, and create a friend list.

What was your motivation?
To gain practical experience with NoSQL databases and develop an API for a social network application.
Why did you build this project?
To understand the underlying architecture and operations of social networking platforms.
What problem does it solve?
It provides a scalable and flexible back-end solution for managing user interactions and data in a social network.
What did you learn?
Learned how to integrate MongoDB with Express.js using Mongoose, and how to implement CRUD operations for complex data relationships.
What makes your project stand out?
The project efficiently handles unstructured data and provides a comprehensive API for a social network, demonstrated through a detailed walkthrough video.


Table of Contents
Installation
Usage
Credits
License
Badges
Features
How to Contribute
Tests
Installation
Clone the repository:

git clone git@github.com:MagsZavala/MyOwnSpace.git
Navigate to the project directory:
cd social-network-api
Install NPM packages:
npm install
Ensure MongoDB is installed and running on your machine. Follow the MongoDB installation guide if necessary.
Start the server:
npm start


Usage
Start the server and open API GET routes in Insomnia for users and thoughts to display the data in a formatted JSON.
Test API POST, PUT, and DELETE routes in Insomnia to create, update, and delete users and thoughts.
Test API POST and DELETE routes in Insomnia to create and delete reactions to thoughts and add and remove friends from a user’s friend list.

Credits
Packages:
Express.js
Mongoose
dotenv

License
This project is licensed under the MIT License. See the LICENSE file for details.

Features
Full CRUD operations for users and thoughts.
Schema settings for virtuals and getters to format queried data.
Efficient management of reactions and friend lists.
How to Contribute
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows best practices and includes descriptive commit messages.

Tests
Currently, there are no automated tests for this application. However, future improvements will include unit tests for key functionalities.