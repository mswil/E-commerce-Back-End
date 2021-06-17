# E-commerce-Back-End
## Description
E-commerce-Back-End is an exercise in creating the back end of an e-commerce website. Utilizing Express.js and Sequelize, API calls are made and corresponding responses are given from a MySQL database.

## Installation
Make sure you have node.js and mySQL v8.0.25+ installed on your device. Then run `npm install`.

## Usage
1. Open a terminal in the root directory
2. Connect to your local mySQL instance using command line
3. Run command `source db/schema.sql` to setup the database
4. Disconnect from your mySQL instance or open another terminal and run command `node seeds/index.js`. This will create the necessary tables for this project, establish their associations, and populate them with dummy data.
5. Run command `node server` or `npm start` to start the server
6. Use Postman, Insomnia, or your API testing environment of choice to test the following endpoints:
  - Categories
    - GET /api/categories
    - GET /api/categories/:id
    - POST /api/categories
    - PUT /api/categories/:id
    - DELETE /api/categories/:id
  - Products
    - GET /api/products
    - GET /api/products/:id
    - POST /api/products
    - PUT /api/products/:id
    - DELETE /api/products/:id
  - Tags
    - GET /api/tags
    - GET /api/tags/:id
    - POST /api/tags
    - PUT /api/tags/:id
    - DELETE /api/tags/:id


## Demo
### Setup
![Setup walkthrough Gif](/E-Commerce-Setup.gif)
***
### Category Endpoints
![Categories walkthrough Gif](/E-Commerce-category.gif)
***
### Product Endpoints
![Productss walkthrough Gif](/E-Commerce-product.gif)
***
### Tag Endpoints
![Tag walkthrough Gif](/E-Commerce-tag.gif)


