## Maintanance

use mysql;
show tables;
CREATE DATABASE wordpress;
CREATE USER wordpress IDENTIFIED BY 'password'
GRANT ALL PRIVILEGES ON wordpress.* to wordpress;