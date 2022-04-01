# CSE341 Lesson 4 Class Activity

## Steps to complete activity

- Clone this repository onto your computer
- Run `npm install` to install the dependencies
- Create a new database in your MongoDB account
- Add a .env file and assign your mongodb url to the variable `MONGODB_URI`
- Install swagger-autogen to the project
- If you wish, add a swagger-autogen script to your package.json to run `node ./swagger.js`
- Create a swagger.js file. Following the swagger-autogen documentation, add a constant for the document, output file, and an array of endpoints. (Hint: since this project uses express router, the only thing you'll need in the endpoint array is a path to the server.js file. )
- Run your swagger script: `npm run swagger-autogen`. You'll know it worked when the output json file appears populated with the project routes.


## Solution

[GitHub Repo](https://github.com/byui-cse/cse341-code-student/tree/L04-class-complete)