# ToDo-list
We all forget to do things, so we can all use a todo list

# About:
This site will help you be more organized, organized,
and responsible by allowing you to keep track of your assignments.

<img width="500" alt="Screenshot 2023-11-23 180608" src="https://github.com/EliyaRabia/ToDo-list/assets/87569799/21c954b3-7c3f-4f76-ab5f-00aa357e60ef">


# Download:
- Installing a vscode workspace https://code.visualstudio.com/
- Installing pgAdmin:
- for Windows: https://sbp.enterprisedb.com/getfile.jsp?fileid=1258649
- for Mac: https://sbp.enterprisedb.com/getfile.jsp?fileid=1258653
- Continue clicking Next until you reach this screen. Your superuser username is postgres and you need to set a password.
  Make sure you write this password down. We will need this later to access our database.
- Grouping all the files above into one folder.
- index.js in vscode and change the password in the client to your password from pgAdmin download.

# DataBase:
- open paAdmin create a DataBase called "permalist" then, click on "Query Tool".
- and write the following command:
- 
  DROP TABLE IF EXISTS items;
  
  CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL

);

# Make your own ToDo list
- open the terminal and write the following orders:
- cd space and drag the folder that you made and enter.
- npm i 
- nodemon index.js
  After that open your Chrome and write in the URL: localhost:3000
  enjoy:)

