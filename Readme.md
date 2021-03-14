# Employee Manager - Editable

## What is this?
This is a project created to showcase basic data maintenance using a .json file.

## What can this project do?
Currently you can edit/delete any user contained in [users.json](/server/data/users.json). 


You can login as any registered user, however there is no route protection.

## How to run this project
Run the following commands in the root directory

1. `npm install`
2. `npm run server` (development) OR `npm run start` (production)

## Packages
This project makes use of the following packages

- [EJS](https://ejs.co/)
- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/)

__Data Reset__. 
There is an api route /api/departments/reset that will copy the original data back to the employee.json file. You can run this command locally from the browser by running ```http://localhost:5000/api/departments/reset```

