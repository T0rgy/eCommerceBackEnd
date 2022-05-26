# E-Commerce Backend (Object-Relational Mapping)

## Description 
This application is a back-end e-commerce site that displays a mySQL database. It uses Express, Sequelize and mySQL2 as its core dependencies. Once set up you are able to display API Routes through you're localhost to perform REST CRUD operations.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)

![Screenshot](/assets/Untitled.png)
![Screenshot](/assets/screencapture-localhost-3001-api-tags.png)

## Installation 
The user should clone the repository from GitHub. This application requires Node.js, Express.js, and Sequelize. To connect to the database run `mysql -u root -p` and enter password from .env file. Then source the schema.sql. To seed the file run `npm run seed`. Finally to connect to the server run `npm start`. 

Once the repository is cloned make sure to create a .gitignore and .env file to store your mysql login credentials and tie them to the config/connection.js file. Download the following dependencies `node init` then `npm i express sequelize mysql2 dotenv`. To connect to the database run `mysql -u root -p` and enter you're password. When connected `source db/schema.sql` then exit mysql. You will need to seed the files in the seeds folder so run `npm run seed`. Finally run `npm start` to connect to the server. 

## Usage 
This application will allow users to view, add, edit, and delete categories, products, and tags through Insomnia or any other cross-platfrom desktop application.

## License 
N/A

## Contributing 
UW Coding Bootcamp 

## Questions
GitHub: [Torgy](https://github.com/T0rgy)
Email: JCTORGE@gmail.com