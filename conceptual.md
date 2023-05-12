### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a - object-relational database
- What is the difference between SQL and PostgreSQL?
PostgreSQL offers more support for OOP.
- In `psql`, how do you connect to a database?
\c database
- What is the difference between `HAVING` and `WHERE`?
`Having` selects group rows after groups and aggregates are computer. `WHERE` selects inpuit rows before.
- What is the difference between an `INNER` and `OUTER` join?
`INNER` will only result in shared columns between tables. `OUTER` will result in one table having columns that are not in the other.
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
`LEFT OUTER` will inlude unmatched rows from the left table. `RIGHT OUTER` does the same, but with the right table.
- What is an ORM? What do they do?
Object Relational  Mapping. ORM connects the OOP to a relational database. It's what allows database usage in python.
- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
An AJAX request can leave the window on the browser side unaffected. It's done on the client side and may not require the browser to change paths or reload.
`requests` on the server side will require the browser to redirect, load another page, or reload the same page.
- What is CSRF? What is the purpose of the CSRF token?
CSRF tokens are used to prefect CSRF attacks. Often submitted with a form, a CSRF insures the form being recieved is valid and coming from it's intended origin.
- What is the purpose of `form.hidden_tag()`?
to store and retrieve data needed by the server which front-end users shouldn't see.
