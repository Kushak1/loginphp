# Forgotten password system

 * Forgotten password system using php and mysqli

# Prerequisites

 * XAMPP - Apache web server
 
 * Code editor

 * Run tables.sql or code bellow to setup database for project
 
    CREATE TABLE pwdReset (
        pwdResetId int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
        pwdResetEmail TEXT NOT NULL,
        pwdResetSelector TEXT NOT NULL,
        pwdResetToken LONGTEXT NOT NULL,
        pwdResetExpires TEXT NOT NULL
    )
    

# Built With

 * XAMPP
 * mysql
 
# Authors
 * Tvelse
