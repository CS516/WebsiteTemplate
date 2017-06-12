# Homework 7: Database Design
In the last assignment, you retrieved, validated, and sanitized user input. You
persisted data across requests using sessions, but you still need to store the
data in a database on the server.

## Learning Objectives

* Design database tables that correspond to your website's data.
* Design CRUD operation queries that you will need to Create, Retrieve, Update,
  and/or Delete data from your tables.
		
## Requirements

### Database Design
				
- [ ] Your website project is required to use your MySQL database. 
  You must design any tables your project will need. These tables will be used 
  for inserting, selecting, updating, and deleting all dynamic data on your website.
  Among these tables will include a “user” table for storing users, passwords,
  permissions, etc.
- [ ] Create a `create-tables.sql` file and add the necessary SQL statements for
  creating your tables. (Similar to what we did in the Databases, SQL, and PDO
  Activity).
- [ ] Create a `queries.sql` file and add the necessary SQL statements for querying
  your tables.

## Resources
* Don't forget about the [Learn SQL Tutorial](https://www.codecademy.com/courses/learn-sql).
This can be helpful when designing your tables.
* You may also want to look at some of the examples in the [GitHub
Repository](https://github.com/BoiseState/CS401-resources/tree/master/php/pdo).
There are examples of multiple tables linked together using "foreign keys"
(e.g. if you want to keep track of a list of posts/messages/etc for each user).
