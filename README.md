# Challenge 13: Object-Relational Mapping E-Commerce Back End
![License badge](https://img.shields.io/badge/license-MIT_License-blue)

## Description

For this project, we were given starter code and had to add in the models, model relationships, API routes, and sync sequelize. Taking all the information we learned from MySql, we then had to convert everything to work with sequelize so our javascript files can do the work for us vs. interacting directly with the MySql database. Then testing the routes in Insomnia to make sure everything connected correctly and works when certain statuses are ran. Here were the User Story and Acceptance Criteria.

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Walkthrough Video
[ORM E-Commerce Back End Walkthrough Video]()

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)

## Installation

Once this repo has been cloned to your local system and opened in VS Code, you will need to install the dotenv, express, mysql2, and sequelize packages. In your terminal, run `npm i` and it will install the necessary packages. You'll also need to update your user and password in the .env file so the mysql database will be able to connect. Run the schema.sql file in the db folder and then install the seeds by entering `npm run seed` in the terminal.

## Usage

To start the database, run `npm start` in the terminal. Take the localhost link into Insomnia and play with the GET, POST, PUT, and DELETE statuses within the api routes folder. 

## Contributing

N/A

## Tests

N/A

## License
MIT License

---

## Questions

Any questions you may have, please feel free to reach out to me using either contact.<br>
GitHub Profile: https://github.com/ashpfander<br>
Email: ashmpfander@gmail.com