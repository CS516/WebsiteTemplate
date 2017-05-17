# Homework 8: Managing User Data and Login

## Learning Objectives

* Use PHP PDO to access your database.
* Write basic queries for retrieving, updating, and deleting database entries.
* Use sessions for login.
			
## Requirements
				
### Saving and Retrieving Form Data
				
Create a separate PHP class to contain all your prepared statements. Call it
`Dao.php`. Put every query/prepared statement in that class (I will expect this
when I am grading).

- [ ] Save form data. Using PHP and PDO prepared statements, save form data to the
tables you designed, as necessary (using INSERT, UPDATE, or DELETE).
- [ ] Encryption. Make sure to encrypt all sensitive data using a one-way hashing
algorithm. You must use a salt when hashing sensitive data.
- [ ] Retrieve form data. Using PHP and PDO prepared statements, get form data from the
tables you designed, as necessary (using SELECT and possibly JOIN). Display data on the pages you
designed in your mock-up. If you have any queries needing a WHERE clause, this is probably where
you will use values from a GET form using a prepared statement.
				
### Login

- [ ] The login portion should work.
- [ ] Your passwords should be stored as a hash digest. Use the password_verify function to compare the
digest of the input password to the digest stored in the database.
- [ ] Restrict URL Access Make sure all URLs requiring a valid login are restricted to only logged-in
users. This is done by add a permissions check to the top of every page as necessary.
