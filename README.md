# E-commerce Back End

## Description
This project is was created to practice building the backend of an e-commerce site. This takes using an Exress.js API and configuring it to use Sequelize to interact with a MySQL database.
## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
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
## Installation
Dependencies needed:
* Node.js
* Express.js
* dotenv
* MYSQL2
* Sequelize

`npm install`
`mysql -u root -p`
`source Develop/db/schema.sql`
`npm run seed`
`npm run start`

Navigate to http://localhost:3001/ in your browser OR by using an API test program such as Insomnia

## Video Walk-through

To view a video on the usage of the application, [click here](https://app.castify.com/view/0f48ba7e-1841-4c6d-a082-dc23749f1163)

## License

This Project is under the ISC license

## Contact
For any questions, please contact me at jkjohnson673@gmail.com