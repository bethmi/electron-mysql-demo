Electron-Mysql-Demo
---

## Introduction
This is a sample desktop app created with Electron js and mysql.


## Requirements

- Git
- npm
- Mysql 5.7 or latest


### Database connection settings

1. Create a new database.
2. Inside that database, create a new table as `user_profile`



| Field        | Type         | Null | Key | Default | Extra          |
---------------|--------------|------|-----|---------|----------------|
| id           | bigint(20)   | NO   | PRI | NULL    | auto_increment |
| city         | varchar(255) | YES  |     | NULL    |                |
| display_name | varchar(255) | YES  |     | NULL    |                |

### Steps

1. Clone the repository

2. Go into the repository

3. Install dependencies

        $ npm install

4. Update the database configurations given in `db-config.json`

5. Run the app

        npm start





---
References:

- https://electronjs.org/docs/tutorial/first-app#trying-this-example
- https://www.slideshare.net/bethmigunasekara/electron-js-114413534