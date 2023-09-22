# Desing Document: API REST CONTACTOS

## 1. Descripción
Ejemplo de una API REST para gestionar contactos en una DB utilizando FastAPI

## 2. Objetivo
Realizar un ejemplo de deseño de una API REST de tipo CRUD y su posterior codificación utilizando el framework [FastAPI](https://fastapi.tiangolo.com/).

## 3. Diseño de la BD
Para este ejemplo se utilizará el gestor de bases de datos [SQLite](https://www.sqlite.org/) con las siguientes tablas:

### 3.1 Tabla: contactos

|No.|Campos|Tipo|Restrincciones|Descripción|Tamaño|
|--|--|--|--|--|--|
|1|id_contactos|int|PRIMARY KEY|Llave primaria de la tabla|AUTOINCREMENT|
|2|nombre|varchar|Not Null|Campo que almacena el nombre del contacto|100|
|3|Apellido Paterno|varchar|Not Null|Campo que almacena el apellido paterno del contacto|50|
|4|Apellido Materno|varchar|Not Null|Campo que almacena el apellido paterno del contacto|50|
|5|Email|varchar|Not Null|Campo que almacena el correo electronico del contacto|50|
|6|Teléfono|varchar|Not Null|Campo que almacena el teléfono del contacto|50|

## 4 Script de SQLite

```sql
CREATE TABLE IF NOT EXISTS  personas(
	id_contactos INTEGER PRIMARY KEY AUTOINCREMENT,
	nombre TEXT NOT NULL,
	primer_apellido TEXT NOT NULL,
	segundo_apellido TEXT NOT NULL,
  	email TEXT NOT NULL,
	email TEXT NOT NULL);

