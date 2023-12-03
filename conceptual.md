### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
	- It is an open source relational database management system.

- What is the difference between SQL and PostgreSQL?
	- SQL is structured query language where it is human readable that is used to interact with relational database. SQL is the language and PostgreSQL is the interface. 

- In `psql`, how do you connect to a database?
	- psql "database_name"

- What is the difference between `HAVING` and `WHERE`?
	- 'WHERE' decides which rows to use and 'HAVING' decides which grouped results to keep.

- What is the difference between an `INNER` and `OUTER` join?
	- 'INNER' join takes the overlapped data of left and right table where all data is present. 'OUTER'includes either right, left or both tables even if some data is not present. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
	- 'LEFT OUTER' join takes the left table and the overlaping with the right table. 'RIGHT OUTER' takes the right table and the overlaping with the left table.

- What is an ORM? What do they do?
	- ORM is object- relational mapping. It is a way to align programming code with database structures. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
	-Client requests with AJAX don't have to involve flask in the api and can be faster as it browser can talk directly with the api. Server-side requests avoids same-origin policy that may prevent browser requests and easier for server to store/process data from database. Server-side requests also makes it harder for others to read the passwords that access the api.

- What is CSRF? What is the purpose of the CSRF token?
	- CSRF is cross-site request forgery. CSRF token prevents hidden inputs that can be submitted to any other site by specifying that this form comes from our server.

- What is the purpose of `form.hidden_tag()`?
	- to include hidden token in the form
