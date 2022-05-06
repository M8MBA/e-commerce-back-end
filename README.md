# E-Commerce Back End Challenge
  
  ## ![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)  

  ## Description
    Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites. Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. Because this application won’t be deployed, you’ll also need to create a walkthrough video that demonstrates its functionality and all of the following acceptance criteria being met. You’ll need to submit a link to the video and add it to the README of your project.
  

  ## Table of Contents:
  ###  * [Installation](#installation)
  ###  * [Usage](#usage)
  ###  * [License](#license)
  ###  * [Contributors](#contributors)
  ###  * [Tests](#tests)
  ###  * [Questions](#questions)

  ## Installation
    npm install (installs dependencies listed in package.json)

    In mysql shell run:
    source db/schema.sql
    USE ecommerce_db

    npm run seed (seeds the database using seed file)

    Walkthrough video - https://youtu.be/X9KoHwcz6_Q


  ## Usage
    GIVEN a functional Express.js API
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


  ## Contributors
    Inquirer.js https://github.com/SBoudrias/Inquirer.js
    mysql2 https://www.npmjs.com/package/mysql2
    dotenv https://www.npmjs.com/package/dotenv
    sequelize https://www.npmjs.com/package/sequelize
    express https://www.npmjs.com/package/express

  ## License MIT  
    https://choosealicense.com/licenses/mit/

  ## Tests
    Run the following commands in your terminal to test this app:

    Invoke the app by running the command: npm start

  ## Questions
  ### If you have any questions, please contact me at
  ### Github: https://github.com/m8mba
  ### or
  ### Email: sauce.ix@gmail.com