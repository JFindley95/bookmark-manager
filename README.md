## User Stories
```

As a user
So that I can go to web sites I saved
I would like to see a list of bookmarks
```

```
As a user
So I can store bookmark data for later retrieval
I want to add a bookmark to Bookmark Manager
```

## Domain Model

![Bookmark Manager domain model](./domain_model.jpg)


## How to use

### To set up the project

Clone this repository and then run:

```
bundle
```


## How to set up the database

 ```
Connect to psql
Create the databases using the psql command CREATE DATABASE bookmark_manager; and CREATE DATABASE bookmark_manager_test;
Connect to the databases using the pqsl command \c bookmark_manager; and \c bookmark_manager_test;
Run the query we have saved in the file 01_create_bookmarks_table.sql for both databases
```
