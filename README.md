NiFi Exercise 1
Rockstars G6

Deliverables:

- Create a NiFi Process Group named as your username. Inside that group:

Create a NiFi DBCP connection pool that points to the JDBC driver you downloaded. The JDBC Class Name
is: com.mysql.jdbc.Driver Please note you can mangle the JDBC URL to point to the employees
schema you created from the setup. The official documentation is https://dev.mysql.com/doc/connectorj/
8.0/en/connector-j-reference-jdbc-url-format.html. This will prevent you from having to run the use
schema ... statement.

- Create a flow that executes a query. The query will be the employees that worked in the Development department.

- Execute the query, get the data and deliver it to 3 destinations:

A JSON file located in any place of your choosing.
An AVRO file located in any place of your choosing.
A CSV file located in any place of your choosing.
Export your process group as a template and send it to Javier Z. via e-mail for