# Ecommerce Back End Development

## License:
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
1. [Description](#description)

2. [Installation](#installation)

3. [Usage](#usage)

4. [Testing](#testing)

5. [Contribution](#contribution)

6. [Questions](#questions)



## Description <a name='description'></a>
In this project, I developed the api routes for this mock-up e-commerce store. This application uses Express.js, Node.js, Sequelize, and dotenv to securely run this back-end application. Furthermore, this application's RESTful API routes were tested using Insomia Core. A link to the video can be found [here](#usage)

## Installation <a name='installation'></a>
This project requires users to have MySQL installed on the workbench. Then, the user must find the correct foler, log into MySQL, and run "SOURCE schema.sql" to create the database. The schema is nested in the db folder, so you must run MySQL there.

![image](./assets/images/running-schema.png)

After that, you must configure your .env file with the following parameters and their values without any punctuation or organizational syntax: DB_USER=YourUser and DB_PW= YourPassword and DB_NAME=databasename_db (make sure it matches the schema.sql). After this is complete, you should right click the server.js file, open the integrated terminal, and run the following commands: 

1. "npm i install"
2. "npm run seeds"
3. "node server.js"

You should now have a live server and if using Visual Studio Code, the following logs:

![image](./assets/images/application-install.png)

Congrats! You have a live server. Due to the lack of a front-end, the video below will show how the database can be searched and modified.

## Usage <a name='usage'></a>
API Routes Tested with insomnia: https://drive.google.com/file/d/1aCtz2NMyc9oiqoOhpmmWI6F0NlYUvMiB/view?usp=sharing

This product can be used as to generate, track, and analyze revenues, costs, and inventory levels of any business. Furthermore, it is a template for setting up a fully-functional back end that can be easily deployed when a front-end is developd.

## Testing <a name='testing'></a>
This application has no tests.

## Contribution <a name='contribution'></a>
This project's front-end code is a work in progress, so any input or suggestions will be reviewed and implemented if appropriate. The project is expected to be expanded upon following the graduation of the Coding Bootcamp at UT Austin in December of 2021.

## Questions <a name='questions'></a>
Feel free to email me at: alexis.gonzalez07@gmail.com

Visit my Github profile at: [Alex Gonzalez Github](https://www.github.com/AlexisGonzalez07)