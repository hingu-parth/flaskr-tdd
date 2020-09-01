# Flaskr - Intro to Flask, Test-Driven Development, and JavaScript

If you are completely new to Flask and/or web development in general, it's important to grasp these basic fundamental concepts:

1. The difference between GET and POST requests and how functions within the app handle each.
1. What "requests" and "responses" are.
1. How HTML pages are rendered and/or returned to the end user.

> **NOTE**: This project is powered by **[TestDriven.io](https://testdriven.io/)**. Please support this open source project by purchasing one of Flask courses. Learn how to build, test, and deploy microservices powered by Docker, Flask, and React!

## What is built

![flaskr app](/flaskr-app.png)

## Requirements

This project utilizes the following requirements:

1. Python v3.8.0
1. Flask v1.1.1
1. Flask-SQLAlchemy v2.4.1
1. Gunicorn v19.9.0
1. Psycopg2 v2.8.4
1. Flake8 v3.7.9
1. Black v19.10b0

## Test Driven Development?

![tdd](https://raw.githubusercontent.com/mjhea0/flaskr-tdd/master/tdd.png)

Test-Driven Development (TDD) is an iterative development cycle that emphasizes writing automated tests before writing the actual feature or function. Put another way, TDD combines building and testing. This process not only helps ensure correctness of the code -- but also helps to indirectly evolve the design and architecture of the project at hand.

TDD usually follows the "Red-Green-Refactor" cycle, as shown in the image above:

1. Write a test
1. Run the test (it should fail)
1. Write just enough code for the test to pass
2. Refactor code and retest, again and again (if necessary)

> For more, check out [What is Test-Driven Development?](https://testdriven.io/test-driven-development/).
