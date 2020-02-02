# macaroni
A framework for formed based commercial / accounting applications.

Note - First commit is a "placeholder" only.  Code coming soon!

A "three layer" application stack for accounting or commercial based software.

The front end runs in an HTML5 browser, and is primarily written in Javascript.
This communicates using a stateless RESTful API with the middle tear.
The middle tear is written using Python, using a "Flask" type methodology to deal
with communications from the ftont end.
The back end is the SQL datatbase.  SQLite, MySQL and PostgreSQL are supported, but
PostgreSQL is preferred here because it most fits the type of applications this is designed for. 
