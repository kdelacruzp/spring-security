# Spring Security

# prerequisites

- MySQL -> https://dev.mysql.com/downloads/installer/ (installer-web)
- MySQL Workbench -> https://dev.mysql.com/downloads/workbench/
- Postman -> https://www.postman.com/downloads/
- Intellij -> https://www.jetbrains.com/idea/download/?section=windows

```
use mydb;

create table product(
id int AUTO_INCREMENT PRIMARY KEY,
name varchar(20),
description varchar(100),
price decimal(8,3) 
);

create table coupon(
id int AUTO_INCREMENT PRIMARY KEY,
code varchar(20) UNIQUE,
discount decimal(8,3),
exp_date varchar(100) 
);
```
