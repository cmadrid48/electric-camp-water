## E-commerce Backend✨

This project is a backend for an e-commerce website using the latest technologies, designed to help an internet retail company compete with other e-commerce companies.

![video](./Assets/Untitled_%20Mar%2023%2C%202023%209_22%20PM.webm)
![screenshot](./Assets/13-orm-homework-demo-01.gif)
![screenshot](./Assets/13-orm-homework-demo-02.gif)
![screenshot](./Assets/13-orm-homework-demo-03.gif)

## Installation & Technologies✨

Clone the repository to your local machine

```sh
Copy code
git clone https://github.com/cmadrid48/electric-camp-water.git

Install the required npm packages
This project uses the following technologies:

Node.js
Express.js
MySQL
Sequelize

Set up the database using the provided schema.sql and node seeds/indexjs

mysql -u <username> -p < db/schema.sql

Note: You will need to have MySQL installed on your machine and have access to a MySQL server in order to set up the database.
```

> make sure to replace your password, and user on .ENV!

```sh
DB_NAME='ecommerce_db'
DB_USER='<USER>'
DB_PW='<YOURPASSWORD>'
```

## Usage

To use this project, follow these steps:

- Run npm run seed to create a development database and seed it with test data.
- Run npm start to start the server and sync the Sequelize models to the MySQL database.
- Open your preferred API client, such as Insomnia.
- Use the API routes to interact with the database, including GET routes for categories, products, and tags, and POST, PUT, and DELETE routes to create, update, and delete data.

### Contributing:✨

If you would like to contribute to this project, please follow these guidelines:

- Fork this repository.
- Create a new branch with your changes: git checkout -b my-feature-branch
- Commit your changes: git commit -m "Add some feature"
- Push to the branch: git push origin my-feature-branch
- Submit a pull request.

## Credits✨

This application was built using Node.js and utilizes the following npm packages:
| Plugin | README |
| ------ | ------ |
Nodejs - https://nodejs.org/en
mysql - https://www.npmjs.com/package/mysql2
express.js - https://www.npmjs.com/package/express
Sequelize - https://www.npmjs.com/package/sequelize

## License✨

This project is licensed under the terms of the MIT license.
