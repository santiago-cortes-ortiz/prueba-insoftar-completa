# prueba-insoftar-completa
este es el proyecto del la prueba insoftar.

### Pre-requisitos 📋
tener instalador MySql, NodeJs, Angular( de ser posible ) y java.

## Repositorio para descargar 🛠️
por favor descargar o mirar los siguientes repositorios correspondientes al proyecto
* [Backend](https://github.com/santiago-cortes-ortiz/prueba-insoftar-backend) - El backend del proyecto
* [Frontend](https://github.com/santiago-cortes-ortiz/prueba-insoftar-frontend) - El frontend del proyecto

## Ejecutando scripts ⚙️
Muy importante ejecutar el script de la base de datos MySql,
a continuacion el script correspondiente.
```
create database Prueba;

use Prueba;

CREATE TABLE usuarios
 (
 id int  primary key not null auto_increment,
 nombres varchar (25),
 apellidos Varchar (25),
 cedula varchar (25) unique not null,
 correo varchar (255) unique not null,
 telefono varchar (16)
 );
```
