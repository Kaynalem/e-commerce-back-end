
  # E-Commerce Back End
  ![License](https://img.shields.io/badge/License-MIT-blue.svg)

  ## Description
  Back end built for an e-commerce site using  working Express.js API and configuring it to use Sequelize to interact with a MySQL database.  
  Follow along with this [video](https://github.com/Kaynalem/e-commerce-back-end/blob/master/utils/demo.mp4)  
  ![mockup](https://raw.githubusercontent.com/Kaynalem/e-commerce-back-end/master/utils/mockup.PNG)
  ## Table of Contents
  * [Demo](#demo)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Questions](#questions)

  ## Demo
  ![demo](https://raw.githubusercontent.com/Kaynalem/e-commerce-back-end/master/utils/demo.gif)  
  ## Installation
  To install necessary dependencies, run the following command in your terminal:
  ```
  npm install 
  ```
  ## Usage
  * Be sure to create the .env file in your root directory with your MySQL user/password information.  
  ```
  DB_NAME='ecommerce_db'
  DB_USER='root'
  DB_PW='your password'  
  ```
  * To initiate the MySQL command line, type: `mysql -u root -p` in your command line and then your MySQL password.
  * To execute the `schema.sql` file, type into the MySQL command line: `source db/schema.sql`
  * To exit the MySQL command line, type `quit;` or `exit;`
  * Once updated, run `npm run seed` and `npm start` in your terminal to get started!
  ## License
  This project is licensed under the MIT license.
  ## Contributing
  If you would like to contribute please file an issue
  ## Questions
  If you have any questions about the repo, open an issue or contact me directly at [kaynalem@gmail.com](mailto:kaynalem@gmail.com).  
  You can find more of my work at my [Github](https://github.com/kaynalem) page.
