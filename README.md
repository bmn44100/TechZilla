![TechZilla](https://github.com/bmn44100/TechZilla/blob/main/TechZilla.jpg)


# TechZilla

The idea behind the project is TechZilla. An ecommerce platform for tech and electronics offering a wide range of brands to anyone looking for the best smartphone, laptop, TV, smart watch, home theatre, washing machine, fridge and a selection of other appliances across East Africa.


## Introduction

The ever-changing product innovations in the tech industry and the ecommerce industry itself is the motivation behind the project. TechZilla is optimized for a specific customer base; an ecommerce site geared towards a great customer experience by offering online shoppers value on site and giving consumers a reason to buy there.
From laptops, tablets, and smartphones to smartwatches, smart TV’s, and speakers, shoppers can browse and buy a wide variety of electronics on the extensive but easy-to-navigate ecommerce site.

[Here is a link to a Youtube video of a demo of the app](https://youtu.be/jvfRe6bTbXY)


## Installation/Deployment

### Prerequisites

These are the minimum requirements for getting the project up-and-running.

#### PHP

PHP is a server-side programming language that can be embedded into HTML and be used to create dynamic websites and interactive web applications. Since the project is developed in PHP you'll need to have PHP installed on your machine.

[Download and install PHP.](https://www.php.net/downloads.php)

#### Composer

Composer is the Dependency Manager for PHP. Install and configure Composer and use it to integrate third-party libraries into any PHP project.

[Download and install Composer.](https://getcomposer.org/)

#### XAMPP

XAMPP helps you create and develop your own applications using web server technologies. XAMPP is an open-source localhost-based server with packages that offer several functionalities. That includes the Apache web server, PHP and the MySQL database. This allows you to create the environment you need to run Sasa Travel on your local machine.

[Download and install XAMPP.](https://www.apachefriends.org/download.html)

Once the download has completed, go to your Downloads folder and double-click on the installer to start the installation. To get XAMPP running you also need to install Java SE Development Kit [(JDK)](https://www.oracle.com/java/technologies/downloads/).

#### MySQL

MySQL is a relational database management system (RDBMS) based on Structured Query Language (SQL) and is the primary relational data storage we interact with for data operations.

[Download and install MySQL.](https://dev.mysql.com/downloads/installer/)

#### Git

Git is used for version control and updating the code repository. To clone the project repository from GitHub you'll need to install Git.

[Download and install Git.](https://git-scm.com/downloads)

#### npm/Node.js

npm is the standard package manager for Node.js and JavaScript programming language and lets you develop applications and websites in JavaScript.

[Download and npm/Node.js](https://nodejs.org/en/download)

### Running the website locally

#### Using XAMPP

Once XAMPP has finished installing, in a terminal session:

Change the working directory to the root directory of XAMPP local repositories by entering the following command:

```shell
cd C:\Program Files\xampp\htdocs
```

Clone the project repository by entering the following command:

```shell
git clone https://github.com/bmn44100/TechZilla.git
```
Change to the root directory of the project repository:

```shell
cd C:\Program Files\xampp\htdocs\TechZilla\ecommerce_website
```

Open mysql and enter your password when prompted:

```shell
mysql -u username -p
```
Run a CREATE DATABASE command to create a new database and select the database as the current database:

```mysql
CREATE DATABASE IF NOT EXISTS ecommerce_db;

USE ecommerce_db;

exit
```
Load the project data from the SQL dump file (ecommerce_db.sql) to the database (ecommerce_db):

```shell
mysql ecommerce_db < ecommerce_db.sql
```
Start XAMPP (make sure to run as admin) and enable the service modules (Apache and MySQL). At this point, open a web browser and navigate to http://localhost/TechZilla/ecommerce_website/ to view the website running locally from your local copy of the repository or http://localhost/TechZilla/ecommerce_website/admin/dashboard.php to get to the admin panel.

#### On PHP

Start Git Bash.

```bash
cd /c/Program Files/xampp/htdocs/TechZilla/ecommerce_website
```

```bash
php -S localhost:8000
```

Load up the site by going to http://localhost:8000.

If you want to modify the project's source code, you’ll need a text editor/IDE like Visual Studio Code in order to test any changes you make to the website in your browser before committing them to the codebase.


## Authors

Bruno Njeru

[Bruno Njeru](https://www.linkedin.com/in/bruno-njeru/)
