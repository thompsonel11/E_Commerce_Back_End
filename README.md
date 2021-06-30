# E-Commerce Back End

The purpose of this application is to build the back end for an e-commerce site.

## Project Link

The URL of the GitHub repo: https://github.com/thompsonel11/E_Commerce_Back_End

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
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
```

## Demos

* The following link demonstrates how to create the schema from the MySQL shell, how to seed the database from the command line, how to start the application’s server.

    https://drive.google.com/file/d/1lHYLu3EOOoR_3D_XxEHG6fh5P9W4O8fm/view

* The following link contains a demo of the application's GET routes to return all categories, all products, all tags, a single category, a single product, and a single tag being tested in Insomnia Core:

    https://drive.google.com/file/d/1hYAMcX6e-za19EFVULMxmKQW8_HLXBtw/view


* The following link contains a demo of the application's POST routes for categories being tested in Insomnia Core:

    https://drive.google.com/file/d/1PuCS8RxJK8LnN9bjNIfmJirHU6HRZbu8/view


* The following link contains a demo of the application's PUT routes for categories being tested in Insomnia Core:

  https://drive.google.com/file/d/1Dfw9nRxiLDdBAEZRhVUqO2Ql-yhFAifV/view


* The following link contains a demo of the application's DELETE routes for categories being tested in Insomnia Core:

    https://drive.google.com/file/d/1IK67B_ZmuXF2U9n9JgKMW9bIBLwvGHC9/view


## Usage

### Packages 

[MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages were used to connect Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package used environment variables to store sensitive data.


### Seed the Database

The `schema.sql` file in the `db` folder to creates the database with MySQL shell commands. Run `npm run seed` to seed data to the database.


### Sync Sequelize to the Database on Server Start

Use `server.js` to sync the Sequelize models to the MySQL database on server start.



