# ecommerce-back-end
This e-commerce database back end is built with Express.js API and configured with Sequelize to interact with a MySQL database. This back end allows user to open API GET routes to see one or all categories, products and tags in json format. Users are also able to POST, PUT and DELETE categories, products and tags in Insomnia.

# Built With
* NODE.js
* Express.js
* Sequelize
* Dotenv

# Installation
- clone and download the repo
- Node.js framework and mySQL is required to run the application
- Use command ``npm install`` to install the required npm packages
- Insomnia is required to test "POST, PUT and DELETE" routes

# Usage
- Open MySQL in shell with mysql -u root -p and enter password
- Run mySQL command ``SOURCE db/schema.sql`` to create database
- Run ``node seeds/index.js`` to seed the database
- The application can be invoked by ``npm start``
- Go to Insomnia 'http://localhost:3001/api/' to test all routes

# Walk through video
[walk-through](https://watch.screencastify.com/v/dxDrRKVgPgkSYmXwUDYO)

# Demo
![demo](assets/tag_demo.gif)
![demo](assets/category_demo.gif)
![demo](assets/product_demo.gif)

# License
MIT License

Copyright (c) 2021 Grace Liu
