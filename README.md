# AI-Recognition with Clarifai AI
# Web Scraping with Node.js Puppeteer


## This Node.js app allows Register feature

<img alt="Register" src="./images/ai-fullstack-register.jpeg" style="aspect-ratio: 16/9; margin: 0 auto; max-width: 20vw;">

## REST API for Login & bcrypt password hashes

<img alt="REST-API" src="./images/ai-fullstack-nodeapi.jpeg" style="aspect-ratio: 16/9; margin: 0 auto; max-width: 20vw;">

## Live server: https://ai-recognition-backend.onrender.com/

## Server-side Node.js + Postgres15

# 1. Download this fun AI Node.js app
```bash
git clone https://github.com/PhoenixYork166/AI-Recognition-Nodejs-Puppeteer.git;
```

# 2. Start using this Node app
```bash
npm install;
```

```bash
npm start;
```

# 3. What if you do not have all the necessary Dev dependencies on your mac OS to start this Node app?

# 4. Go to ./install-postgresql
## Read through ./install-postgresql/0_postgresql_docs.txt

# 5. Installing mac OS Node.js dev dependencies
## i. Start installing necessary dependencies 'brew' command on your mac OS
```bash
bash ./install-postgresql/1_install-brew.sh;
```

## ii. Start installing 'wget' command on your mac OS
```bash
bash ./install-postgresql/2_install-wget.sh;
```

## iii. Adding 'psql' to your Bash env on your mac OS
```bash
bash ./install-postgresql/3_add-psql-to-bash.sh;
```

## iv. Downloading PSequel GUI (PSequel GUI is still crashing in 2024)...
```bash
bash ./install-postgresql/4_download-psequel-gui.sh;
```

## v. Installing PostgreSQL on your mac OS
```bash
bash ./install-postgresql/5_install-postgres.sh;
```

## vi. Creating a database call 'test' using PostgreSQL on your mac OS
```bash
bash ./install-postgresql/6_createdb-test.sh;
```

# 6. Start re-creating database & tables necessary for starting up this Node app

## i. Start by re-creating database
```bash
bash ./database-recreation/0_create_database_smart-brain.sh;
```

## ii. Re-creating a table called 'users' in our database using Bash
```bash
bash ./database-recreation/1_create_table-users.sh;
```
## or you may run SQL statements declared in 2_create_table-users.sql
```bash
2_create_table-users.sql
```

## iii. Manually re-creating postgres table 'users' in our database for storing bcrypt password hashes => run PostgreSQL inside rootDir/install-postgresql/db-recreation-SQL
```bash
1_create-users.SQL
```

## table 'login'
```bash
2_create_table-login.sql
```

## Follow through all the .SQL files for Postgres db re-creation
## except 15_drop-FUNCTION-and-TRIGGERS

## iv. Verify that we've successfully created a table named 'users' in our database
```bash
bash ./database-recreation/5_verify_schema-users.sh;
```
## Hit 'q' key to exit when we're done verifying

## v. Verify that we've successfully created a table named 'login' in our database
```bash
bash ./database-recreation/6_verify_schema-login.sh;
```
## Hit 'q' key to exit when we're done verifying