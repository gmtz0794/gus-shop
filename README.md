# Gus Shop App

This project is designed to set up the back end for an e-commerce website using Express.js, Sequelize, and MySQL. It allows users to manage categories, products, and tags, performing operations like creating, updating, retrieving, and deleting these entities through RESTful API routes.

## Installation

Clone the repository into your local machine: 

- git clone git@github.com:gmtz0794/gus-shop.git

Navigate to Develop in project folder and install dependencies using the following command:

- cd gus-shop
- cd Develop
- npm install

Set up your MySQL database by creating a new database for the application. Use the provided schema.sql file to create the necessary tables in your database. Create a .env file in the root directory and add your MySQL database credetials:

- DB_NAME=<your_database_name>
- DB_USER=<your_mysql_username>
- DB_PASSWORD=<your_mysql_password>

Seed the database(optional, but recommended for testing):

- npm run seed

## Usage

Start the server:

- npm start

This will start your Express.js server and sync Sequelize models with the MySQL database. Test API Routes using Insomnia/Postman: Test the GET, POST, PUT, and DELETE routes for categories. Seeding the database will insert test data for categories, products, and tags into your database using:

- npm run seed

## License

MIT License
