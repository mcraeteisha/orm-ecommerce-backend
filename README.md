# orm-ecommerce-backend
The back end for an e-commerce site, created using an Express.js API, Sequelize, and a MySQL database.

## Link to Walkthrough Video
[View my E-Commerce Backend here!](https://www.loom.com/share/a0d61918b5a647ce91e7179a47d7d1fa)

## User Story
As a manager at an internet retail company:
* I want a back end for my e-commerce website that uses the latest technologies
so that my company can compete with other e-commerce companies

## Technologies Used
* Express.js API
* MySQL
* Sequelize
* Insomnia Core
 
## Work Completed

Using VS Code, MySQL, Sequelize, and Insomnia Core, I completed the following:

* Used the MySQL2 and Sequelize packages to connect my Express.js API to a MySQL database and the dotenv package to use environment variables to store sensitive data.
* Used the `schema.sql` file in the `db` folder to create my database with MySQL shell commands. Used environment variables to store sensitive data like your MySQL username, password, and database name.
* Set up database models and associations
* Created API routes to perform RESTFUL CRUD operations
 
## Learnings and Issues
Some of the learnings I'm taking away from this project are:
1. The biggest issue I had with this assignment was and issue with my CREATE Product route. It turns out that the issue was largely due to a typo. Sequelize was giving me a validation error for Price when I was attempting to create a new product. It turned out that in my post route for Products, I had typed 'req.body_price' for prices instead of 'req.body.price'. I overlooked this several times and spent at least an hour trying to figure out the issue. Takeaway: Try the rubber duckie method sooner. (I caught the error as soon as I started to explain it to my tutor. So, if I'd spoken it out loud sooner, I probably would've saved myself some time.)

## Contributors
Teisha McRae


