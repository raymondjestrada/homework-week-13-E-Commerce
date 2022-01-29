# 13 Object-Relational Mapping (ORM): E-Commerce Back End By: Raymond Estrada

# Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

Built a mysql database and application backend for the e-commerce site. Built using MySQL2, Express, and Sequelize.

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)


# User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

# Acceptance Criteria

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

# Installation
💾   

`npm install`
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
# Usage
💻   
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

Start a second terminal in the root of your project and run

`npm run seed`
  
`npm start`

# Testing

This application uses Insomnia Core as a testing method

# Walkthrough Video

For a quick example of the execution, here is a short video. 
<iframe src="https://drive.google.com/file/d/1zPCMVzpph5Yn9LcLImoT3Ho72fFJVtiy/preview" width="640" height="480"></iframe>


# Contributing


# Questions
✉️ Contact me with any questions: , [GitHub]https://github.com/raymondjestrada<br />
