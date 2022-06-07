# CS569 Final Project
## Data Structure
User schema
```javascript
{ 
   username: String,//should be unique 
   password: String, 
   role: String, //admin or user
}
```
Product schema
```javascript
{ 
   name: string,
   price: number,
   ingredients: [{
       name: string,
       price: number
   }]

}
```
## Backend Requirements
### Technology: NodeJS, MongoDB (mongodb or mongoose)
### Implement the product routes for CRUD (Create, Read, Update, Delete) products
  * Get all: GET localhost:3000/products
  * Get a specific product: GET localhost:3000/products/:id
  * Create a new product: POST localhost:3000/products
  * Update an existing product: PUT localhost:3000/products
  * Delete an existing product: DELETE localhost:3000/products
### Implement the user routes for CRUD (Create, Read, Update, Delete) users
  * Get all: GET localhost:3000/users
  * Get a specific user: GET localhost:3000/users/:id
  * Create a new user: POST localhost:3000/users
  * Update an existing user: PUT localhost:3000/users
  * Delete an existing user: DELETE localhost:3000/users
### An admin can access all routes (user & product)
### A user can only use GET methods (user & product)
### Assume that we always has a user (username: admin, role: admin) in the system

## Frontend Requirements
### Technology: Angular
### Design your modules, components, services...

## Coding requirement
* Push code every day
## Timeline
* Angular structure: Report on `Tuesday (06/07/2022)`. Each person will have `15 minutes` to discuss with me. I will send out the schedule
* Backend Code: Push the backend version with all routes (users and products) before `10:00 Wednesday (06/08/2022)`
* Final: Push the final version (Backend and Frontend) before `10:00 PM Monday (06/13/2022)`
* Presentation: Each person will have `20 minutes` to present your project (run the program, show the code, and QA) on `Tuesday (06/14/2022)`. I will send out the schedule

Good Luck

