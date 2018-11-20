# SQL
course SQL

*Crear database*  
CREATE DATABASE "NAME";  

*Crear table* 
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

$conexion= **mysqli_connect**(db_host,db_usuario,db_password,db_nombre);  
$consulta=" SELECT *FROM "DATA NAME" ";  
$resultados=**mysqli_query**($conexion,$consulta);  
$fila = **mysqli_fetch_row**($resultados);

*Caso de no conectar a base de datos*

if (mysqli_connect_errno())  {  
		echo "Fallo pappi"  
	exit  
		
		}

*Consultar la bd*  
conecta pero no la encuentra;
	mysqli_select_db($conexion,$db_nombre) or die ("No se encuentra La BBDD");  

pasar datos por pantalla  

while(($fila=mysqli_fetch_row($resultados))==true){  
	
	
	echo $fila[0];  
	echo $fila[1];  
	echo $fila[2];  
	echo $fila[3];  
	echo "<br>";  
	}  


mysqli_close(conexion);  

*Consultas*  
{

SELECT * FROM "TABLE NAME" WHERE "NOMBREFILA" LIKE '%CABALLERO'


}


