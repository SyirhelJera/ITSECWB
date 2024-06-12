1. Run XAMPP Start Apache and MySQL
2. Open http://localhost/phpmyadmin/index.php
3. Press SQL and Execute the Query Below
-- Create the database
CREATE DATABASE userDB;

-- Use the newly created database
USE userDB;

-- Create the users table
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    fullName VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    phone VARCHAR(15) NOT NULL,
    profilePhoto LONGBLOB NOT NULL
);


4. NOTE THAT THE DEFAULT CREDENTIALS OF THE DB IS:
User = "root"
password = ""