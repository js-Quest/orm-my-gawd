
  # orm-my-gawd
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This project demonstrates the use of Express.js API and Sequelize interacting with a MySQL database as the back-end for an e-commerce site.  It utilizes starter code, as evidenced in the initial commits.

  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [License](#license)
  - [Questions](#questions)

  ## Installation
  Clone the repo, open it up in your chosen code editor, then open up a terminal from the root folder.  
  
  - Install the dependent packages by running the command: **npm i**

  - make sure you have also separately input your **mysql password into a .env file** to access the db.  Create the file and name it '.env' if it does not already exist.  
  - ![Screenshot 2023-05-11 at 9 48 02 AM](https://github.com/js-Quest/orm-my-gawd/assets/128349503/f5f8275c-4e06-4d3c-990d-f0a8d3c84750)

  - to get to the mysql command line and initiate the database, run command: **mysql -u root -p**  
  - and then run: **source ./db/schema.sql**  
  - and then to exit the mysql command line run: **quit**  


  - now that you have returned to the regular terminal, seed the database by running command: **npm run seed**  
  - to connect the application to your local host 3001, run command: **npm start**  

  - then go to your insomnia app and submit your requests on http://localhost:3001/api/  

  - root endpoints:  /products   /tags   /categories
  - check out the available requests in each routes folder.


  [Walkthrough Video of initial CLI steps](https://drive.google.com/file/d/1zmzdo90xGtkmqfjWGbbKl4Ve4ez7950F/view)

  
  ## Usage
  This project tracks products and their related data in a database for a proposed e-commerce site.   
    
  
  [Walkthrough Video of Requests](https://drive.google.com/file/d/1WZbH10fRAVTGMvlrApJT3TQXpaWbCBtL/view)  


  
  ## Contributing
  [Sequelize docs](https://sequelize.org/docs/v6/core-concepts/assocs/)  

  [Medium](https://medium.com/@sarahdherr/sequelizes-update-method-example-included-39dfed6821d)  

  [Stack Overflow](https://stackoverflow.com/questions/14169655/sequelize-js-foreign-key)


  ## Tests
  N/A

  ## License
  This project retains the MIT license.

  ## Questions
  For additional information, please check out my [github](https://github.com/js-Quest)  
  
  
