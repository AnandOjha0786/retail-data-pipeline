## MySQL - Cheatsheet

* Login into MySQL (using MySQL Client) `mysql -u retail_user -h localhost -p`
* List Databases `SHOW databases`
* Switch Database `USE retail_db`
* List Tables `SHOW tables`
* Describe Table `DESCRIBE departments`

## Postgres - Cheatsheet

* Login into Postgres 
```shell script
psql -U retail_user \
  -h 127.0.0.1 \
  -d retail_dw -W
```
* List Databases `\l`
* Switch Database `\c retail_dw`
* List Tables `\d`
* Describe Table `\d departments`
* Getting help `\?`
* Running a script
```shell script
psql -U retail_user \
  -h 127.0.0.1 \
  -d retail_dw \
  -f /retail_db/create_db.sql
```
