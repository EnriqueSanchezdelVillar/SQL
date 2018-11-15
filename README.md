# SQL
course SQL

*Crear database*  
CREATE DATABASE "NAME"; 
CREATE TABLE "NAME"("name campo" "tipo de dato","name campo2" "tipo de dato2");  
*Quitar campo*
ALTER TABLE "NAME TABLE" DROP "Name campo";  
*Añadir campo* 
ALTER TABLE "NAME TABLE" ADD "Name campo" "tipo de dato";  

*Insertar datos*
INSERT INTO "NAME TABLE"("name campo","name campo2","name campo3") VALUES ("value1","value2","valus3")  

*Consulta tablas*
SELECT "Name campo1,"name campo2" FROM "NAME TABLE"
SELECT * FROM "NAME TABLE"  todos los campos  

### Conexión base de datos con php  

$conexion=
```diff + this will be highlighted in green

