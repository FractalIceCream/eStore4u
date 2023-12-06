# eStore4u
  [![license-shield]][license-url]

  ## Description
  
  This application is a back-end app for e-commerce utilizing mysql server to perform CRUD operations. Utilizing express, sequelize, and mysql2, we can implement Models for our data and make CRUD associatedAPI calls. We connect to the mysql server and initialize the database. Then we can start by seeding the data and run the server. The Insomnia application allows us to make all CRUD http calls and perform operations for Product/Tag/Category tables. 

  ## Table of Contents
  
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Questions](#questions)

  ## Installation
  
  - source ./db/schema.sql (in mysql, log in and initialize the database through the schema) 
  - update env file with mysql credentials, in order to utilize sequelize.
  - npm i (installs the following, dotenv, express, sequelize, mysql2)
  - npm run seed (to build the database with provided seed data)
  - npm start (to start the server on CLI)

  <p align="right"><a href='#estore4u'>back to top</a></p>
  
  ## Usage

  [link video demo here](https://drive.google.com/file/d/10wVr8O_u5diYLnceGictFrR6jVJn2pHY/view)
  
  <p align="right"><a href='#estore4u'>back to top</a></p>

  ## License
  
  This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit)

  <p align="right"><a href='#estore4u'>back to top</a></p>

  ## How to Contribute
  
  Contribute as needed by forking the repo and making a pull request.
  
  <p align="right"><a href='#estore4u'>back to top</a></p>

  ## Questions

  [FractalIceCream's GitHub](https://github.com/FractalIceCream)

  If you have any questions or feedback, reach me @ [vroco86@gmail.com](mailto:vroco86@gmail.com).

  <p align="right"><a href='#estore4u'>back to top</a></p>

  [license-shield]: https://img.shields.io/badge/LICENSE-MIT-green
  [license-url]: https://choosealicense.com/licenses/mit



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

### Walkthrough Video: 37%

* A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your readme file.

* The walkthrough video must demonstrate how to create the schema from the MySQL shell.

* The walkthrough video must demonstrate how to seed the database from the command line.

* The walkthrough video must demonstrate how to start the application’s server.

* The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia.

* The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia.

* The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.


* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

