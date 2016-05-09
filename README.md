# Module_6

Week 6

1. Fork this repository.

2. Initialize your project directory and create a **package.json** file that will include all your project's dependencies.

3. Import the data from foodTrucksJSON.js using the following steps:

  1. Make sure you've installed MongoDB by following the instructions either here: 

     https://canvas.uw.edu/courses/985046/pages/installing-mongodb-on-macos?module_item_id=5993493  (for Mac users)

     or here: 

     https://canvas.uw.edu/courses/985046/pages/installing-mongodb-on-windows?module_item_id=5993494 (for Windows users)

  2. Make sure MongoDB is running by typing mongod - you should see it start up and output:
  
    *waiting for connections on port 27017*

  3. From the command line inside the project directory, type:
  
    `mongo foodTruckAPI < foodTrucksJSON.js`

4. Use the Express server code you wrote in Module_5 as the basis for your Express server for Module_6.

5. Use the Express router module you wrote in Module_5 as the basis for your Express router module for Module_6, only this time, refactor the code in each of your routes to use the mongoose module to create, read, update, and delete in your MongoDB collection.

6. Include your **.eslintrc** file as part of your repo. Your code should be lint-free based on your lint configuration.

7. Use a **.gitignore** file in your project locally, adding 'node_modules' to the file to prevent the inclusion of node_modules in your repo.
