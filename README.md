# Task Manager
## Typescript, Mysql with TypeORM, VueJs

### Prepares

1. Install mysql server. For more information visit `https://www.mysql.com`
2. Login mysql as root: `mysql -u root -p`
3. Create new mysql user with **\<username>** and **\<password>**: `CREATE USER '<username>'@'localhost'IDENTIFIED WITH mysql_native_password BY '<password>';`
4. Set priveleges for new mysql user: `GRANT ALL PRIVILEGES ON * . * TO '<username>'@'localhost';`
5. Flush priveleges: `FLUSH PRIVILEGES;`
6. Create database **\<database>**: `CREATE DATABASE <database>;`

### Start project

1. Run `npm i` command
2. Setup database settings inside `_ormconfig.json` file and rename it as `ormconfig.json`
3. Run `npm start` command
