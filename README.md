# e-commerce
Object-Relational Mapping (ORM) project that sets up the back-end of an e-commerce site utilizing Express.js to use Sequelize to interact with a MySQL database. 

## User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Acceptance Criteria
```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment cariable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in the formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, adn delete data in my database
```
## Mock-up
The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:
![In Insomnia, the user tests "GET tags," "GET categories," and "GET All products.".](Assets\13-orm-homework-demo-01.gif)

The following animation shows the applilcation's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:
![In Insomnia, the user tests "GET tag by id," "GET category by id," and "GET one product."](Assets\13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories beign tested in Insomnia:
![In Insomnia, the user tests "DELETE category by id," "CREATE category," and "UPDATE category."](Assets\13-orm-homework-demo-03.gif)

## Getting Started
Use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create the database with MySQL shell commands. Use environment variables to store sensitive data like the MySQL username, password, and database name.


## Submission Links
[GitHub Repository](https://github.com/kristyvanatta/e-commerce)
[Video Link]()
