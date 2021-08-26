# E-commerce-Backend



## Table of Contents
* [Description](#description)
* [Technologies](#technologies)
* [Deployment](#deployment)
* [Usage](#usage)
* [Built With](#built-with)
* [Future Development](#future-development)



## Description:
Ecommerce-Backend utlizes an Express.js API which was configured to use the Sequelize ORM to interact with a MySQL relational database. The Express.js API was provided by UW Madison Extended Bootcamp. The CRUD methods were created in accordance to RESTFUL API practices. The functionality was designed to allow an internet retail company to keep track of their inventory using Product, Tag, and Category models. A user can view all products, categories, and tags, or view a single product, category, or tag. They can also update, delete, and add a category, product, or tag.



## Technologies
The Express.js framework was used for the API. The Sequelize ORM was used to ease the communication between the javascript app logic and the sql database querying (mysql2). Dotenv was used to protect login info on Github. Testing was done using insomnia core.



## Deployment:
Not deployable. Please clone the files and install dependencies to test out the app.




## Usage
The user can enact CRUD methods on any of the three models to view, update, create, or delete data as they see fit. See testing of the routes below.
Demo video: 




![Demo Video](Walkthrough.gif)






## Built With
 - Javascript
 - Node.js
 - Express.js
 - Mysql
 - Mysql2
 - Sequelize



## Future Development
Implementing a front-end would be a good exercise to improve my full-stack capabilities and reinforce how the moodel (data) layer is manipulated by the controller to change the view (MVC). Currently there is really no view to complete the MVC paradigm.
 
