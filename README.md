# e-commerce-back-end [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This application serves as the back-end for an e-commerce website. This back-end uses the latest technologies to make the website competitive with other e-commerce companies.

This application allows users to create, retrieve, update and delete product data. Since there is no front-end, users will need to use a REST API testing platform such as Insomnia to make these changes on the back-end.

This application was created with Node.js, Express.js, mySQL, Sequelize, and JavaScript.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

Clone the repo by running the following in your command-line interface:

    git@github.com:pham-tracy/e-commerce-back-end.git

Install NPM packages:

     npm install

## Usage

Run the following command in your command line interface to connect to mySQL:

    mysql -u root

Connect to the database by running the following command:

     source ./db/schema.sql

Exit out of mySQL and return to your command line interface. Run the seeds by running:

     npm run seed

Proceed with connecting to the server by running:

     npm start

Connect to the server using an API testing platform such as Insomnia.

Video demo on how to use this application can be viewed here:

### Screenshots

Get Products:
![GET Products](images/GET%20products.png)

Get Products by ID:
![GET Products by id](images/GET%20product%20by%20id.png)

Create new product:
![CREATE new product](images/CREATE%20new%20product.png)

## Credits

Starter code was provided by UW Coding Bootcamp: https://github.com/coding-boot-camp/fantastic-umbrella.

## License

MIT License is used for this project. Please refer to the following link for more information: https://opensource.org/licenses/MIT.

## Contributing

Please free to contribute to this project.

## Questions

If you have any questions about this project, please visit my GitHub here: https://www.github.com/pham-tracy.

For further questions, please email me at phamtracy95@gmail.com.
