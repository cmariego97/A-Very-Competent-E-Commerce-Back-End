# A Very Competent E-Commerce-Back-End
A back end for an e-commerce site using Express.js API, Sequelize, and MySQL database

## Description

This project utilizes Sequelize and the GET, POST, PUT, and DELETE methods to build the back-end of a retail web application to allow database interaction.

During this project, I became more comfortable with writing back-end code for API routes and using Insomnia.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Badges](#badges)
- [Contributing](#how-to-contribute)
- [Credits](#credits)
- [Tests](#tests)
- [Author](#about-the-author)

## Mock-Up

App demonstration video is available [♡ here ♡](https://streamable.com/47d79r):

![application demo video](./assets/demonstration/e-commerce%20back-end%20demo.gif)

## Installation

This application requires the following applications to run:
* express
* dotenv
* mysql2
* sequelize

Run the following command in the command line to initialize a new package:
~~~
npm init
~~~

Run this command to install the express package:
~~~
npm install express
~~~

Run this command to install the dotenv package:
~~~
npm install dotenv --save
~~~

Run this command to install the mysql2 package:
~~~
npm i mysql2
~~~

Finally, run this command to install the sequelize package:
~~~
npm install --save sequelize
~~~

Additionally, the MySQL shell and the Insomnia application are required on the user's machine to run this application.

- For MySQL installation instructions, click [♡ here ♡](https://dev.mysql.com/doc/refman/8.0/en/installing.html).

- For Insomnia installation instructions, click [♡ here ♡](https://docs.insomnia.rest/insomnia/install).

## Usage

When starting the application, the user must create a database schema and seed the database. 

Firstly, connect to the MySQL shell by entering the following command in the command line:
~~~
mysql -u <username-goes-here> -p
~~~

To create database a schema, enter the following command in the MySQL shell:
~~~
source db/schema.sql
~~~

Next, open a new terminal.

Then, seed the database by entering the following command in the terminal:
~~~
npm run seed
~~~

Finally, to run the application, enter the following command in the command line:
~~~
node server
~~~

When all these steps are done correctly, you should see the following line in the terminal:
~~~
App listening on port 3001!
~~~

Once the application is up and running, the user can now use the Insomnia application to view, add, modify, or delete data from the database.

Here is a demo of the application: [insert demo here]

If the video is not working [♡ here ♡](https://app.castify.com/view/8d899e0c-4a1d-4180-a0c6-5c10e9c3479f) is a link to the demo video.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This application is covered under the MIT license.
To view a description of this license type, refer to the repository or click [♡ here ♡](https://opensource.org/licenses/MIT).

## Badges

This application was made with JavaScript:

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)

## How to Contribute

Ways to contribute include suggesting bug fixes.

## Credits

I received assistance for this project from a tutor, institution instructors, and a study group ♡

## Tests

N/A

## About the Author

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)

My name is Claire and I am a student learning Web Development.
