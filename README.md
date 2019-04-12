Vendor web Application:

Software required: STS spring tool suite, XAMPP
Database used : PHPMyAdmin (mySQL)

Pre-Requisites:
Create vendor table using following query:

create table vendor(id int PRIMARY KEY,
code varchar(100),
name varchar(100),type varchar(100),
email varchar(100),
phone varchar(100),
address varchar(1000));

To Run the Application make sure mysql is up and running --> Go to browser : http://localhost:8080/vendorweb/showCreate
