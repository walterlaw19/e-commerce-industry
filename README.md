# e-commerce-industry

[![License: Artistic-2.0](https://img.shields.io/badge/License-Perl-0298c3.svg)](https://opensource.org/licenses/Artistic-2.0)

## Description
An application to GET, POST, PUT, and DELETE data using MySQLDatabase. Using dependencies such as dotenv, express, mysql2, and sequelize, you can input data to the database such as products and sort the by category, product and tags which you can modified as needed.  A great platform to utilize on your commercial enterprise.


## Table of Contents

* [Installation](#installation)
* [Demo](#demo)
* [Usage](#usage)
* [License](#license)
* [Contribution](#contribution)
* [Questions](#questions)


## Installation

1. You must download and install Node.js click on link: https://nodejs.org/en/download/

2. Download and install MySQL Community Server from this link: https://dev.mysql.com/downloads/mysql/. For a complete guide on how to install it properly depending on your operating system (Windows, macOS, Linux), review this link: https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide 

3. copy or clone this repo into the folder where you want the application to be created by entering the following command in your terminal (mac) or gitbash (windows):
    * git clone git@github.com:walterlaw19/e-commerce-industry.git   (<---- Copy, Paste, Enter this command in your terminal)

4. Open the e-commerce-industry folder from your your VS Code (make sure you are in the right folder) or you can use the integrated terminal, go to the directory where the e-commerce-industry folder was installed: e.g. "cd e-commerce-industry"

5. Once you are in the e-commerce-industry folder, open a new file where you will put your credentials.  In the terminal type: 'touch .env'  Then navigate to .env file and open it and put this information 

```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='ThisIsMySQLPW'
```

*** You should enter your SQL username in DB_USER and your SQL password in DB_PW. Save the changes.

6. Back in the e-commerce-industry root directory, open your integrated terminal in VS Code and install the dependencies by entering the command: 'npm i'.  Wait for the installation to be completed.

7. After the installation has be completed, you must login to MySQL shell. Enter "msyql -u 'your SQL username' -p" and press Enter. Now you will be prompted to enter your SQL Password. Once you are logged in, enter the following commands in this order to clear/seed the MySQL database properly. 

```
A. source db/schema.sql
B. quit
```
8. First we must seed the database by entering the following command in the terminal: "npm run seed"

8. Once this is done, type "npm start" to run the application.

7. Use Insomnia to get all categories, tags and produces using the correct path

```
http://localhost:3001/api/products        http://localhost:3001/api/categories         http://localhost:3001/api/tags
```

9. Once you are done, you can press CTRL + C in the terminal to stop the application.


## Demo

[Click here to see a demo video](https://drive.google.com/file/d/14zrXCw2QGi4mYtQebITtj_reYo03Uobr/view?usp=sharing)

![](Readme-images/screenshot1.PNG) "GET all Categories"
![](Readme-images/screenshot2.PNG) "POST a Product"
![](Readme-images/screenshot3.PNG) "PUT a Product"
![](Readme-images/screenshot4.PNG) "GET all Tags"



## Usage

You can use this application to view, create, update and delete products, categories, and tags for your business.
 
## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## contribution

Please send me an email if you can want to contribute or submit any suggestions: walterlaw19@gmail.com

## Questions

If you have any questions or concerns, you can reach me at: walterlaw19@gmail.com

or visit my GitHub: https://github.com/walterlaw19



```
Made by by Walter G
```

---
##### © 2021 WG.








