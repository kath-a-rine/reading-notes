# Data Modeling

## nosql v sql

***What type of database is the best fit for the complex query intensive environment?***

SQL databases are the best fit.

***What type of database is the best fit for hierarchical data storage?***

NoSQL databases are best for hierarchical data storage because they store data following a key-value pair system. 

***Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.***

A SQL database can handle an increased data load by enhancing a single server, increasing the CPU, RAM, SSD, etc. NoSQL requires more servers to be added in order to handle more traffic.

## sql modeling techniques

***Among data tables, what is a one-to-many relationship and how do we “relate” them?***

A one-to-many relationship means an entry on one table can apply to multiple entries on another table. The example cited in the reading included a database listing departments in a company, and another table listing all of the employees. Multiple employees could work in the same department meaning one entry on the department table applies to multiple entries on the employees table.

***Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.***

...create a diagram...

***Explain the difference between a primary and foreign key.***

A primary key uniquely identify each row of a table. A foreign key is a column or columns that match a primary key in another table.

## video - sql vs nosql

***How do we treat keywords and parameters differently in SQL syntax?***

A keyword says what you want to do in the query (SELECT, ADD, FROM, WHERE, etc) and the parameters identify the data that is manipulated by the keyword. Ex. SELECT Customers FROM Customer_data WHERE Orders = 10 (*Not sure if this is the correct way to put this*)

***Define normalization within the context of schemas and data.***

Normalizing data is formatting the data to meet the format of the schema, creating a consistency in the data format.

***Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.***

- one-to-one: a record in one table is related to a single entry on another table
- one-to-many: an entry on one table can apply to multiple entries on another table
- many-to-many: many entries on one table apply to many entries on another table