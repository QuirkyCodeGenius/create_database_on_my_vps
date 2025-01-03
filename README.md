# create_database_on_my_vps
<h1 align="center">Julian Arley Paez Silva</h1><br>

This repository show how you can create a database in your vps with mysql ubuntu and apache

<h1>first step</h1>

install mysql in your vps if you yet dont have 

```bash
sudo apt install mysql-server
```
now enter to mysql with this command

```bash
mysql -u root -p
```
the password is the same of your vps 

now you need create your first database with the next steps


first step
```
CREATE DATABASE primer_database;
```
second step 
```
USE primer_database;
```
third step
```
CREATE TABLE mi_tabla (
    nombre VARCHAR(100),
    cantidad VARCHAR(100),
    telefono VARCHAR(100), 
    fecha VARCHAR(100),
    referencia VARCHAR(100)
    );
```
use this command to see how look your table

```
DESCRIBE mi_tabla;
```

![Texto alternativo](table.png)