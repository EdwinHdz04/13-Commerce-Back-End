13 Object-Relational Mapping (ORM): E-Commerce Back End

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

## Table Of Content
* [General Info](#general-info)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## General Info
A manager at an internet retail company wants a back end for my e-commerce website that uses the latest technologies to that my company can compete with other e-commerce companies.

## Technologies
Project is created with

Javascript
Node.js
Sequelize
MySQL2
Express
Dotenv

## Installation
To get started clone this repository using

git clone git@github.com:EdwinHdz04/13-Commerce-Back-End.git
Both Node.js and MySQL must be installed on your computer.

Install dependencies

npm init --y
npm install express sequelize mysql2
Open up MySQL shell and input

source db/schema.sql
and use ecommerce_db
Then quit MySQL shell and input the following in your terminal

npm run seed
to start running application simply input

node server.js
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage
The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.

## License
License: MIT
This repository is licensed under the MIT license.

## Questions
Questions about this repository? Please contact me at EdwinHernandez80@icloud.com