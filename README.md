# E-commerce_Backend
DESCRIPTION
User Story: AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


Acceptance Criteria: GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

Project Description: This was a great learning experience getting comfortable with models and routes.  The focus of this project was to add functionality to make all the routes, models, and associations working properly to cover the CRUD as it relates to an E-commerce site selling various items that have associations.  Using SQL in association with Sequalize allows a E-commerce site manager to easily view, add, update, and delete products, tags, and categories.

Installation: this is not an installed app, but simply a backend.  One can test by first navigating to SQL shell, runnign "source db/schema.sql" to create the DB.  Exit the shell and seed your data by running "NPM run seed"...this will insert data into your tables.  A user can then run "NPM run watch" in order to start your server with NodeMon.  Your backend is installed and ready to test.

Usage: Intended to be connected to a front end of some sort, for our purposes, were simply testing the backend functionality using Insomnia.  Open Insomnia, create the approriate route based on CRUD, include the proper localhost path in the url.  Select JSON for body and include data there as needed to see the routes work approriately.

Technology: this project used MySQL2 in conjunction with Sequalize for the DB, Tables, and Seed Data.  DOTENV was used for environment variables to proect sensative user and password info.  SQL Ace was used for testing the DB and Insomnia was used for testing the routes.

Licenses / Certs: no licenses or certs

Collaboration: Fellow classmates, Ted, Kris, and Casey were instrumental in completing this project.

Repo Link - https://github.com/PeterBookmyer/E-commerce_Backend

Screencastify Link - https://drive.google.com/file/d/1dklh-7Sf_nofKE4q_Qsk7eaO-0KqkzXk/view