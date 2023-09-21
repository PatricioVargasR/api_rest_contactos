# Designg Document: API RST CONTACTOS

## 1. Descripción
Ejemplo de una API REST para gestionar contactos en una DB utilizando FastAPI

## 2. Objetivo
Realizar un ejemplo de deseño de una API REST de tipo CRUD y su posterior codificación utilizando el framework [FastAPI](https://fastapi.tiangolo.com/).

## 3. Diseño de la BD
Para este ejemplo se utilizará el gestor de bases de datos [SQLite](https://www.sqlite.org/) con las siguientes tablas:

### 3.1 Tabla: contactos

|No.|Campos|Tipo|Restrincciones|Descripción|
|--|--|--|--|--|
|1|id_contactos|int|PRIMARY KEY|Llave primaria de la tabla|
