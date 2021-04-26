# HW4_Galetskaya_Anna

Basic part of the homework is done.

The task was to create web application, which can authenticate user with password:
1. Listen on localhost:5000
2. Render authentication form on http://localhost:5000/
3. Return static images and files on http://localhost:5000/static/<image_name> (there is only one image: 11.jpg)
4. Has secret page for authenticated users on http://localhost:5000/cabinet

Valid usernames and passwords are stored in MongoDB database. The database name is 'users', collection name is 'user'. There are two users in the database, with username and password "user":"123" and "one":"111".
