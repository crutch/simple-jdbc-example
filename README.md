simple-jdbc-example
===================

Simple example of creating, retrieving and updating tuples in relational database using JDBC.

It uses Table Gateway pattern and Template method to show one approach how to DRY your code when doing selects (beware, the code is not completely DRY, e.g., connection related stuff should go into Properties etc.)

Just look on Runner's main method to see what's going on.

With-ORM branch shows basic usage of Hibernate ORM.
