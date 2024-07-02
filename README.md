                     Htcdoc Directory

This project is an online bookstore created as a personal class project. The objective was to develop a website where users can browse and purchase different books online. This website allows users to view available books, check book details, see remaining stock on the design end, and get notifications if books are sold out when attempting to purchase them. The website is built using HTML, CSS, JavaScript, and PHP, with XAMPP used for database management.


The `htdocs` directory contains all the HTML files necessary for the web application. Below is a brief overview of its contents and setup instructions:

Contents
- HTML Files: The directory includes various HTML files that constitute the different pages of the web application.
- Home Page: The main entry point of the application is `store_index.html`. This file serves as the home page.

Setup Instructions

To properly view and test the web application locally, follow these steps:

1. Install XAMPP: Ensure that XAMPP is installed on your computer. XAMPP is a free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages.

   You can download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

2. Place `htdocs` in XAMPP Directory:
   - Locate the `htdocs` folder in your XAMPP installation directory. On most systems, this is typically found at `C:\xampp\htdocs` (Windows) or `/Applications/XAMPP/htdocs` (macOS).
   - Copy the contents of your project’s `htdocs` directory into the XAMPP `htdocs` directory.

3. Start XAMPP:
   - Open the XAMPP Control Panel.
   - Start the Apache server by clicking the "Start" button next to "Apache".

4. Access the Application:
   - Open a web browser and navigate to `http://localhost/store_index.html`.
   - This will load the home page of your web application.

Database Configuration
For the application to function correctly, it may require database support. Ensure that:

Connect MySQL: Make sure your MySQL database is properly connected with your project. You can configure the database settings in your application to match the database setup in XAMPP.
Import Database: Import any necessary database files or scripts (e.g., SQL dump files) into your local MySQL database using phpMyAdmin or the command-line tools provided by XAMPP.
