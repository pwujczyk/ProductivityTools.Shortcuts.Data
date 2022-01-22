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


I am not sure if needed
```
sudo apt-get isntall mysql-client - this is no needed I think
sudo apt-get install default-mysql-server
```

This command allows to connect to db without adding the network
```
gcloud sql connect pwujczykmysql1 --user=root --quiet
```

If you add network between VM and SQL you can use this command 
```
mysql -h 34.132.169.140 -u root -p
```