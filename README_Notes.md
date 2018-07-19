# three way database for Node.js:
## raw connector : SQL Injection
## query builder
## ORM: Object Relational Mapper: bookeshelf.js; sequelizejs.com;

Database 
 - tables
  - rows
   - columns

1. install knex globally : *npm i -g knex* 
2. add knex to our project, install knex locally: npm install knex
3. create a knex configuration file using knex init: *knex init* --create knexfile.js
4. add sqlite3 to the project: *npm install --save sqlite3*
5. create migration tables: knex migrate:make file_name
6. 


## Install SQLite on Windows

* install python 2.7
* add PYTHON environment variable pointing to C:/Python27/Python.exe or wherever
 it was isntalled.
* yarn global add windows-build-tools
* may required yarn add node-gyp and node-pre-gyp on project
* download shell tools for sqlite and drop them on windows system 32 folder