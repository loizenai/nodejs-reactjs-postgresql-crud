# Reactjs Nodejs PostgreSQL Example

![reactjs nodejs postgresql](https://loizenai.com/wp-content/uploads/2020/11/Reactjs-Nodejs-PostgreSQL-CRUD-Example.png)

Link tutorial: https://loizenai.com/reactjs-nodejs-postgresql-example/

In the tutorial, I introduce how to build an “React.js Nodejs CRUD PostgreSQL Example” project with the help of Ajax to POST/GET/PUT/DELETE requests with step by step coding examples:

– Nodejs project produces CRUD RestAPIs with PostgreSQL database using the supporting of Sequelize ORM.
– React.js project will consume the Nodejs CRUD RestAPIs by Ajax then show up on Reactjs component’s views.

List to do:

– I draw a fullstack overview Diagram Architecture from React.js Frontend to PostgreSQL database through Nodejs RestAPI backend.
– Develop Nodejs CRUD RestAPIs with the supporting of Sequelize ORM.
– Implement Reactjs CRUD application with Ajax fetching APIs to do CRUD request (Post/Get/Put/Delete) to Nodejs Backend APIs.
– I create a testsuite with a number of integrative testcases with CRUD RestAPI requests from Reactjs to do CRUD requests to Nodejs RestAPIs Server and save/retrieve data to PostgreSQL database.

## Overall Architecture System: Reactjs + Nodejs + PostgreSQL

![Overall Architecture System: Reactjs + Nodejs + PostgreSQL]https://loizenai.com/wp-content/uploads/2020/11/React.js-Nodejs-PostgreSQL-Diagram-Architecture.png

- We build a backend: Nodejs CRUD Application with PostgreSQL that provides RestAPIs for POST/GET/PUT/DELETE data entities and store them in PostgreSQL database.
- We implement React.js CRUD Application that use Ajax to interact (call/receive requests) with Nodejs CRUD application and display corresponding data in Reactjs Component.

## Nodejs PostgreSQL CRUD Design Application

![Nodejs PostgreSQL CRUD Design](https://loizenai.com/wp-content/uploads/2020/11/Nodejs-Build-CRUD-MySQL-Architecture-Overview-1.png)

We have 4 main blocks for the application:

- For building RestAPIs in Nodejs application, we use Express framework.
- For interacting with database PostgreSQL, we use Sequelize ORM.
- We define APIs URL in router.js file
- We implement how to process each API URL in controller.js file
- We use Bootstrap and JQuery Ajax to implement frontend client.

## Reactjs CRUD Application Design

[Reactjs CRUD Application design](https://loizenai.com/wp-content/uploads/2020/11/Reactjs-CRUD-RestAPI-Application-Frontend-Architecture-Diagram-2.png)

– Reactjs CRUD Application is designed with 2 main layers:

React.js components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
Ajax is used by Reactjs component to fetch (post/put/get/delete) data from remote restapi by http request

Reactjs CRUD Application defines 5 components:

- Home.js is used serve as the landing page for your app.
- AppNavbar.js is used to establish a common UI feature between components.
- CustomerList.js is used to show all customers in the web-page
- CustomerEdit.js is used to modify the existed customer
- App.js uses React Router to navigate between components.

## Integrative Project Goal

![Integrative Project Goal](https://loizenai.com/wp-content/uploads/2020/11/Reactjs-application-show-list-data-after-update-a-customer.png)

Tutorial Link: [Reactjs Nodejs PostgreSQL Example](https://loizenai.com/reactjs-nodejs-postgresql-example/)

Nodejs Reactjs Tutorial:
- [How to Integrate Reactjs with Nodejs Tutorial](https://loizenai.com/integrate-reactjs-nodejs-tutorial/)
- [Reactjs Node.js MySQL CRUD Example](https://loizenai.com/reactjs-nodejs-crud-mysql/)
- [Reactjs Nodejs PostgreSQL Example](https://loizenai.com/reactjs-nodejs-postgresql-example/)
- [Reactjs Nodejs MongoDB CRUD Example – MERN Stack Application](https://loizenai.com/reactjs-nodejs-mongodb-crud/)
