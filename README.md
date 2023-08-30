# ECommerceBackEnd

## Description 

This e-commerce back end application allows the user to interact with the database provided through end points in insomnia. Users can view all categories, products, and tags, update them, create new categories, products, and tags, as well as delete any they choose. The user must hit the correct end points in insomnia, and if they are updating or creating, they must pass the correct parameters in json. The categories, products and tags are tied together through keys where products belong to categories, categories have many products, products belong to many tags and tags belong to many products. 

## Installation
To use this application make sure you have insomnia and mysql workbench installed. Once you clone down the code, copy the schema.sql file into your workbench and run it. Then open your terminal where you have the repo and run "npm run seed" to seed the database. Once this is done you can run nodemon server.js or npm start to begin listening on the port. You can now use insomnia to hit your desired end points to create, read, update, or delete items in the database.

[Here is a link to the walkthrough video](https://drive.google.com/file/d/1djJNGpXdRfmABMV8rFXT23NwziBUVBty/view?usp=drive_link)