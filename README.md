# Chitter Challenge
-------

This is my attempt to create a Twitter clone that satisfies the user stories below.

```
STRAIGHT UP

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a Maker
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```

# Database Set Up
1. Connect to <code>psql</code>
2. Create database like so: <code>CREATE DATABASE chitter;</code>
3. Connect to the database using <code>\c chitter;</code>
4. Run the SQL query in the file <code>db/migrations/01_create_peeps_table</code>
5. Create a users table according to the instructions in <code>db/migrations/02_create_users_table</code>
6. Link the two tables by using the SQL queries in <code>db/migrations/03_link_tables</code>
7. Using the above commands, create a separate database for testing purposes with the name <code>chitter_test</code>
