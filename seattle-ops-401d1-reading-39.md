David Armstrong 11-30-2020

SQL injection, the use of DB queries in a malicious manner in order to retrieve data, is one of 
the most common types of cyber attacks. These attacks, while targeted at the SQL server, can 
be used not only to retrieve data immediately but also to reset passwords and obtain user 
credentials for far reaching effects. As the article points out, it is helpful to think of SQL queries 
as commands since they act in rather the same way as commands to an operating system. 

Some of the common queries (commands) include:
--INSERT; which allows the user in put new data into the table
--UPDATE;  to change current data to a different value
--SELECT; to view data in a specified range
--DELETE; remove data from the table

In addition to these there are any number of qualifying commands which can be added to create more 
specific queries.

The good news is that this sort of attack can be prevented! One of the key means is to put in place 
input sanitization. This includes removal of NULL characters, line breaks, single quotes, and most special 
characters. In addition, a syntax framework can be provided to test the input against to ensure the input 
is in the correct format.
