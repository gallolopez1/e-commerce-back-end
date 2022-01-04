# Challenge 13: E-Commerce Back End

# Activity Instructions:

Build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Links

<!-- * 🌎 [Live Github Page](https://gallolopez1.github.io/.../) -->
* 💾 [Repo](https://github.com/gallolopez1/e-commerce-back-end)

## <u>Team Profile Generator Preview:</u>

### App Usage
[Recording Link](https://watch.screencastify.com/v/3OuZ8RIZF8IRr8roHjPF)

![App Usage Recording](./assets/e-commerce-walkthrough.gif)

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## References:
https://nodejs.org/api/fs.html

https://www.npmjs.com/package/mysql2

https://www.npmjs.com/package/sequelize

https://www.npmjs.com/package/dotenv
