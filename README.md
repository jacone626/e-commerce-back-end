# Ecommerce Backened App

## Description
This application is an employee tracker. It was built using mysql, node, and javscript. 

## Installation
Ensure that you have node, dotenv, sequelize and mysql2 installed. Then, clone the repository into VSCode or some other coding application. Once inside the cloned repository, navigate into the db folder and run "SOURCE schema.sql;" and press enter. You can then quit mysql and then run "npm run seed" and press enter again. After that, run "npm start" and navigate to Insomnia.

## Usage
A user must clone the repository and navigate to the correct folder within the terminal. Once the sql commands have been run, type in "npm start". The user will then be shown the below in the console to indicate that the server is connected and listening. 

![command line with all commands up to npm start shown]()

Once in Insomnia or another software of your choice, you can run the GET, POST, PUT and DELETE routes for products, categories and tags. The below image shows the output for a GET route for all products.

![GET route in Insomnia that shows products on preview side]()

There are also options to view just a specific product, category or tag by entering /:id after the name. The below image shows that example with a GET route for the tags with an id of 4

![shows GET route for tag with id of 4, the product is a baseball hat]()

Additionally, the user can update or delete a speciific product, tag or category. The below image shows that a 1 will be logged inside the brackets when you update a category. 

![shows PUT route for category with a 1 inside brackets to indicate it was successful]()

Finally, the user has the option to create a new tag, product or id. The below image shows us creating a new product. 

![shows CREATE route for new product called "hiking boots"]()

Walkthrough video:

[E-commerce Back-end]()

## Credits



## License
Please refer to the license in the repo.
