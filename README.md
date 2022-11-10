# E-Commerce-Backend

## Description
This command-line application features the backend of an e-commerce site. The backend is built with Express.js, Sequelize, and MySQL2. These technologies allow the user to interact with a MySQL database which stores and retrieves the company's product information. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To use this application you will need to: 
1. Clone this repository into your local machine. 
2. Then, using the terminal you will need to run `npm install` to install the npm packages/dependencies. 
3. After installing the dependencies, you will need to create a file called `.env` in the root of the directory. The content of the file needs to be the following.
    - `DB_NAME='ecommerce_db'`
    - `DB_USER='root'`
    - `DB_PASSWORD='Your Password Here'`
4. In the terminal, type `mysql -u root -p`, enter your password and hit Enter.
5. Next, in the mysql shell type `source db/schema.sql`.
6. After the database is created, type `quit` in the mysql shell.
7. In the terminal, type `npm run seed` to seed the database.
8. After the database has been seeded, run `npm start` to start the server. 
9. Use Insomnia to test the functionality of the application. 

## Usage

Please follow [this video guide](https://drive.google.com/file/d/1SKIS28PlSHtyACdpsaUM3FUxSBWRqYV2/view?usp=sharing) for using the E-Commerce-Backend applcation or follow the steps above.

## Credits
Documentation used:
- [Express.js](https://expressjs.com/en/4x/api.html#express)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)

## License

[MIT](https://spdx.org/licenses/MIT.html)
