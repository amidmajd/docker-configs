# My Docker Config Files

## Docker Compose For PostgresDB

1. Run `docker-compose up` to start the container
2. Go to `127.0.0.1:5050`
3. Login to PgAdmin :
   - **Email** : `mail@gmail.com`
   - **password** : `password`
4. Add server in Admin panel:
   - Name : `anything`
   - Host name/address : `postgres`
   - Username : `admin`
   - Password : `password`
- Accessing DataBase:
    - Address : `localhost`
    - Port : `5432`
    - Username : `admin`
    - Password : `password`

<br>


## Docker Compose For MongoDB
### Credentials:
   - username: `admin`
   - password: `password`

<br>


## Docker Compose For Redis & RedisInsights
### Credentials:
   - username: `admin`
   - password: `password`

<br>

## Wordpress + MySQL + PHPmyAdmin

## SQL Server
* Install ODBC for sql-server connection to work:
[Download ODBC 18](https://learn.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-ver16&tabs=ubuntu18-install%2Calpine17-install%2Cdebian8-install%2Credhat7-13-install%2Crhel7-offline)

* Fix permission issue on mssql-data host volume files:
`sudo chown 10001 mssql-data` [more details](https://stackoverflow.com/questions/65601077/unable-to-run-sql-server-2019-docker-with-volumes-and-get-error-setup-failed-co)

