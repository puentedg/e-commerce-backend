# E-commerce backend

## Description
   
  - This application shows the back end of an e-commerce. It gets all categories, products and tags, and it's able to make selection by id. The user can also post new categories, products or tags, or delete them.

   
   ## Table of Contents 
   
   - [Installation](#installation)
   - [Usage](#usage)
   - [Questions](#questions)
   - [License](#license)
   
   ## Installation
   
To access the application, `git clone` the repo down to your local so you have the Node project on your local.

Run `npm install` in order to install the following npm package dependencies as specified in the `package.json`:

  * "dotenv": "^8.6.0",
  * "express": "^4.18.2",
  * "mysql2": "^2.3.3",
  * "sequelize": "^5.22.5"

Then run `mysql -uroot -p` and source the `schema.sql` database. Quit mysql and seed the application `node seeds`. 
The application will start by running `node server.js` in the command line.




   ## Usage

*Link to the video: https://drive.google.com/file/d/1uH1oHrzkM8TuvYI2oOQR2Cc4djirOsiD/view

When you run `node server.js`, the application uses the installed packages to initialize in the command line and then you can use an application like `insomnia` to use GET, POST, PUT and DELETE routes..
   

   ## Questions
   
   In case you have any additional questions, please contact me:
   
<a href="https://github.com/puentedg">GitHub</a>

   
Email: puentedg@gmail.com

   
   ## License
   
   No license