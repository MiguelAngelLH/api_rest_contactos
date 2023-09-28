# api_rest_contactos

API REST para gestionar contactos en una DB UTILIZANDO FASTApi
## 1.Descripcion
ejomplo de una API REST gestionar contactos en una DB utilizando FastAPI

## 2.OBJETIVO
Realizar un ejemplo de diseño de una  API REST de tipo CURD y su posterior codifcacion utilizando al famesword  [FASTAPI](https://fastapi.tiangolo.com/).

## 3. diseño de la BD
para este ejemplo se utilizara el gestor de bases de datos[SQLITE3](https://sqlite.org). con las siguientes tablas:;
|no.|campo|tipo|resticciones|descripcion|
|--|--|--|--|--|
|1|id_contacto|int|PRIMARY|Llave primaria de la tabla|
|2|nombre|varchar|50|tipo texto|
3|primer_apellido|varchar|50|tipo texto|
4|segundo_apellido|varchar|50|tipo texto|
5|email|varchar|50|tipo texto|
6|telefono|varchar|13|tipo texto|

## 3.2 Script
CREATE TABLE contactos (
id_contacto INT PRIMARY KEY,

nombre VARCHAR (100) NOT NULL,

primer_apellido VARCHAR (50) NOT NULL,


## 4. Desing Document
|--|--|
|4.1 Metodo PUT|
|Propiedad|Detalle|
|Descripción|EndPoint para actualizar algun contacto de la API|
|Summary	|EndPoint para actualizar datos de los contactos|
|Metodo	PUT|
|EndPoint|	https://localhost:8000/contactos/{id}|

segundo_apellido VARCHAR (50) NOT NULL,

email VARCHAR (100) NOT NULL,

telefono VARCHAR (13) NOT NULL
);
