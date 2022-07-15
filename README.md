# Postgres

```bash
psql -U postgres

List of databases
\l


connect to database
\c postgres


list all tables
\d


describe table 
\d api_gateway_keyset


show all tables 
select * from api_gateway_keyset


CREATE DATABASE test;
\c test
CREATE TABLE test_table(something int);
INSERT INTO test_table VALUES (123);
SELECT * FROM test_table;
\q


DELETE FROM api_gateway_keyset


TRUNCATE api_gateway_keyset RESTART IDENTITY CASCADE;

```
