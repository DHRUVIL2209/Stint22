# Stint22

**Stint22** is a web-based task management system developed as an academic project. It provides a centralized platform for managing personal tasks, teams, team members, and assigned work.

The project was developed and tested using the **WAMP (Windows, Apache, MySQL, PHP) environment**, with MySQL used for database management.

## Features

* User registration and authentication
* User login and logout
* Personal task management
* Create, update, and manage tasks
* Team creation and management
* Add and manage team members
* Assign tasks to teams
* User profile management
* Profile image support
* Password change and recovery functionality
* MySQL-based data storage

## Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **PHP**
* **MySQL**
* **Apache**
* **WampServer**
* **phpMyAdmin**

## System Requirements

The project was originally designed to run in a **WAMP environment**.

### Minimum Requirements

* Windows operating system
* **PHP 5.0 or newer**
* Apache HTTP Server
* MySQL
* WampServer
* Modern web browser

### Recommended Environment

For the best compatibility, security, and performance, it is recommended to use the latest stable versions of:

* **WampServer**
* **PHP**
* **MySQL**
* **Apache**
* **phpMyAdmin**

PHP versions older than **PHP 5** are not recommended or supported for this project.

## Installation and Setup

### 1. Install WampServer

Download and install WampServer if it is not already installed.

WampServer provides the required local development environment, including:

* Apache
* PHP
* MySQL
* phpMyAdmin

Start WampServer and ensure that both **Apache** and **MySQL** services are running.

### 2. Copy the Project

Copy the `Project_sem-iv` folder into the WampServer `www` directory.

For example:

```text
C:\wamp64\www\Project_sem-iv
```

Depending on your WampServer installation, the location may also be:

```text
C:\wamp\www\Project_sem-iv
```

### 3. Create the Database

Open phpMyAdmin from WampServer or visit:

```text
http://localhost/phpmyadmin/
```

Create a new database named:

```text
stint22
```

### 4. Import the Database

Import the supplied SQL database file:

```text
Project_sem-iv/stint22.sql
```

This creates the tables and database structure required by the application.

### 5. Database Configuration

Make sure the database connection settings used by the PHP project match your local MySQL configuration.

A typical default WampServer configuration uses:

```text
Host: localhost
Username: root
Password: [empty]
Database: stint22
```

If your MySQL installation uses a different username or password, update the project's database connection configuration accordingly.

### 6. Run the Project

Once Apache and MySQL are running, open:

```text
http://localhost/Project_sem-iv/
```

The Stint22 application should now be available in your browser.

## Database

The application uses **MySQL** for persistent data storage.

The repository includes:

```text
stint22.sql
```

which contains the database structure required for the application.

An additional migration file may also be present for compatibility with older versions of the project's database.

## Important Notes

* The project is intended to run through a web server and should not be opened directly as local HTML files.
* Apache and MySQL must be running before accessing the application.
* The password-recovery email functionality requires appropriate PHP mail/SMTP configuration.
* Database credentials may need to be changed depending on your local WampServer/MySQL configuration.
* The original project folder name `Project_sem-iv` has been preserved to avoid breaking existing file paths and application references.

## Project Background

Stint22 was developed as an academic web-development project using PHP and MySQL.

The repository contains a cleaned and repaired version of the original project while preserving its original structure, design, and core application logic.

## Repository Structure

```text
Stint22/
│
├── README.md
├── .gitignore
│
└── Project_sem-iv/
    ├── index.html
    ├── PHP files
    ├── CSS files
    ├── JavaScript files
    ├── Images and assets
    └── stint22.sql
```

## Status

**Completed / Academic Project**

The project is maintained primarily as part of a software-development portfolio.
