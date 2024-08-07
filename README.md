# Project Setup Guide

## Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- [**XAMPP**](https://www.apachefriends.org/index.html) (or any other local server like WAMP, MAMP, etc.)

## Step-by-Step Instructions

### 1. Clone the Repository
First, download the source code or clone the repository using Git.

**To clone the repository:**
```bash
https://github.com/ABCText-IndianLanguages/test2.git


```
### Setup Instructions

### 2. Download the Source Code

- Download the source code as a ZIP file.
- Extract the ZIP file to your desired location.

### 3. Set Up the Database

1. Open phpMyAdmin by navigating to `http://localhost/phpmyadmin` in your web browser.

2. Download the Source Code
If you prefer not to use Git, you can also download the source code as a ZIP file and extract it to your desired location.
    - Open phpMyAdmin by navigating to http://localhost/phpmyadmin in your web browser
    - Create a new database named textABC.
    - Import the SQL files provided in the databases folder into the textABC database:
      Click on the textABC database, go to the Import tab, and select the nusers.sql file from the databases folder. Click Go to import the file.
    - Repeat the process by importing the studies.sql file into the same textABC database.
   
5. Configure the Project
If using XAMPP, store the project files in the htdocs directory:
- Ensure the project folder is located in the htdocs directory of your XAMPP installation.

6. Access the Project
Start the Apache and MySQL services in the XAMPP Control Panel.


**Open your web browser and navigate to http://localhost/ABCText**.
