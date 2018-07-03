# Introduction To Structured Query Language

## What is SQL?

SQL (Structured Query Language) is a language for managing data in a database. Unlike some other programming languages, it's only used for one thing: talking to databases. Thus, you might hear it referred to as a "special purpose", or "domain specific" programming language. This means that you won't be using SQL to write the next big web app, but you might use it to interact with the database that powers it.

Even though SQL has just one purpose, it is used by many different database systems such as MySQL, PostgreSQL, or the system we'll be using in this course: SQLite. There are a handful of things other SQL systems like Postgres, or MySQL can do that are not supported by SQLite. Every database system has its own strengths and weaknesses, and as you learn more about them you should evaluate them thoughtfully when deciding which to use for what purpose. For us, SQLite provides a low barrier to entry, and is simple to get up and running.

## Data Scientists <3 Databases

Why do we need to master SQL? Whether you're a Data Scientist, Machine Learning Engineer, Data Analyst or Data Engineer, you'll frequently be working with databases to store, retrieve, and manipulate data. Most companies store their data in databases, and before you can build any cool predictive models with machine learning, you're going to need to access this data. Interacting with a database is usually the first component of a data pipeline.

Facebook saves user data and stores––or persists––your associations to your friends. Amazon has an enormous database of items for sale. The New York Times has a storage system for all of their articles. Most of the sites and companies you interact with everyday need databases to persist data.

We've already seen how we can build Python programs that model real-world objects and environments. With database management skills, we'll learn to store representations of the Python objects our programs create and retrieve them at the appropriate time. We’ll also learn how to connect our Python applications to our databases.

For example, a basic web application might have many users. So far, we've learned how to build a Python `User` class that produces user objects. But, we don't yet know how to store those users and their details. If a user signs up for our app and we proceed to lose all their information immediately, how will we know if an existing user is signing back into our app? We need a way to take our Python objects, store them in a database and retrieve them at the appropriate time.

## In This Topic

This topic will cover how to use and navigate databases based on SQL. By the end of this topic, you’ll be able to:

* Create SQLite3 databases.
* Create, update, select, and delete data from database tables.
* Relate data within a given database.
* Write SQL code in both your command line and your text editor and execute the code against a database.
* Write Python programs that talk to and save data to your databases.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/sql-topic-introduction' title='Introduction To Structured Query Language'>Introduction To Structured Query Language</a> on Learn.co and start learning to code for free.</p>

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/sql-topic-introduction'>What is SQL </a> on Learn.co and start learning to code for free.</p>
