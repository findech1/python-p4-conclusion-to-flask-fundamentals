# Conclusion to Flask Fundamentals

## Learning Goals

- Describe the components of a web application framework.
- Build and run a Flask application on your computer.
- Manipulate and test the structure of a request object.
- Extend a Flask application to meet the unique requirements of different projects.

***

## Key Vocabulary

- **Web Framework**: software that is designed to support the development of
  web applications. Web frameworks provide built-in tools for generating web
  servers, turning Python objects into HTML, and more.
- **Extension**: a package or module that adds functionality to a Flask
  application that it does not have by default.
- **Request**: an attempt by one machine to contact another over the internet.
- **Client**: an application or machine that accesses services being provided
  by a server through the internet.
- **Web Server**: a combination of software and hardware that uses Hypertext
  Transfer Protocol (HTTP) and other protocols to respond to requests made
  over the internet.
- **Web Server Gateway Interface (WSGI)**: an interface between web servers
  and applications.
- **Template Engine**: software that takes in strings with tokenized
  values, replacing the tokens with their values as output in a web browser.

***

## Conclusion

Flask gives us the ability to take all of the Python and SQL code we built in
Phase 3 and serve it to users on the internet. In this module, we learned a
number of skills that will help us make flexible and powerful websites later
on:

- Configuring WSGIs and web servers.
- Routing to views at fixed and parameterized URLs.
- Using application and request context to deliver information from the
  internet to our views.
- Creating databases and integrating them with Flask applications with
  Flask-SQLAlchemy and Flask-Migrate.
- Combining these skills to pass information between our database, our
  application, and the internet.

Next, you'll learn about APIs: a tool for accessing information on the internet
efficiently and in an organized way.

## Resources

- [Flask Documentation][flask]
- [Armin Ronacher][armron]
- [Werkzeug Documentation][werk]
- [Jinja Documentation][jinja]
- [Click Documentation][click]
- [The Pallets Projects][pp]

[flask]: (https://flask.palletsprojects.com/en/2.2.x/)
[armron]: (https://lucumr.pocoo.org/)
[werk]: (https://palletsprojects.com/p/werkzeug/)
[jinja]: (https://palletsprojects.com/p/jinja/)
[click]: (https://palletsprojects.com/p/click/)
[pp]: (https://palletsprojects.com/)
