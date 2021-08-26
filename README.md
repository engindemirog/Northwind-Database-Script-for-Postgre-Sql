*** Run SQL script on Linux ***

```
sudo -u postgres psql
```

```
create database mydb;
```

```
create user myuser with encrypted password 'mypass';
```

```
grant all privileges on database mydb to myuser;
```

```
CREATE DATABASE myDatabase WITH ENCODING 'UTF8' LC_COLLATE='en_US.UTF-8' LC_CTYPE='en_US.UTF-8';
```

```
\c databaseName
```

```
\i 'path/postgres.sql'
```


