# tournament_results
This is a learning project for Udacity "INTRO TO RELATIONAL DATABASES" course.

It contains a file describing database schema and a simple python module to work with the database as well as a set of unit tests for it.

To run the project you'll need to have postgresql (including CLI) and python installed.
Start with creating a database. To do so run psql command to run postgresql CLI. Then you can do the following in either of two ways:

1. Paste each statement listed intournament.sql in to psql.
2. Use the command \i tournament.sql to import the whole file into psql at once.

To run tests use this command: python tournament_test.py.
