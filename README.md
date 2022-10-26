# E-Commerce_Back_End

## Description

The goal of the project was to build routes and requests for a simulated backend of an e-commerce website in order to get practice creating and running such routes and requests. The created program is a limited simulation of an e-commerce site backend. During this assignment I learned how to create routes and requests that interact with a SQL database and how to define relationships between routes.

## Installation

The modules Express, Dotenv, Sequelize, and MySQL2 must be installed using npm and the runtime Node.js must be installed. A SQL dialect and workbench must be installed, and it is recommended that MySQL be used as this was the version testing was performed with. An API client will also need to be installed in order to make use of the requests this program performs, with Insomnia being the one used during program testing.

## Usage

This program acts as a simulated backend of a e-commerce website. Before running the program the user must seed the database by typing the command "node seeds/index.js" into the terminal. After this the user may run the program on a localhost port by typing "node server.js" into the terminal. The user may then go to their API cilent of choice and can run get, put, post, or delete requests by either catergory (called by using "/api/categroies" as the query), tag (called by using "/api/tags" as the query), or product (called by using "/api/products" as the query). Get requests may either be made on all items stored in the categroy, tag, or proudct databases or by using an item's categroy, tag, or proudct ID number. Put and delete requests and get requests that are done by ID number will display status 404 and throw the error message "No category/tag/product with that ID found" if the given ID number is not found.

## Credits

N/A

## License

Please refer to the license in the repo

## Links and Images
Github Repo URL: https://github.com/fortu038/E-Commerce_Back_End