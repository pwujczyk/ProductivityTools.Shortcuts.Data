## Maintanance
show databases;
use mysql;
show tables;
CREATE DATABASE wordpress;
CREATE USER wordpress IDENTIFIED BY 'password'
GRANT ALL PRIVILEGES ON wordpress.* to wordpress;
FLUSH PRIVILEGES
Select * from wp_options where option_name IN('siteurl','home'); 
update wp_options set option_value='http://34.72.241.225' where option_name='siteurl'