# Taller 3 Seguridad Base de Datos   


**Integrantes**  
Arango Garcia Jorge Mario   
Chacon Prieto Jose Alberto   
Gamez Ramirez Juan Carlos   
Sierra Nieto Joaquin   

**Docente**   
César Iván Rodríguez Sánchez   

UNIVERSIDAD PILOTO DE COLOMBIA   
FACULTAD DE INGENIERÍA DE SISTEMAS   
POSTGRADOS   
BOGOTÁ   
MAYO 03 DE 2019   



**Instale el cliente de oracle para linux**
Proceso de instalacion del cliente Oracle  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/accesoDB.PNG) 



Muestra de Oracle en ejecución  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/OracleInstalado.JPG)  
**Conéctese con el usuario hr y contraseña Pass704. A la base de datos Oracle identificada**
Se muestra la evidencia de la conexión realizada:  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Conexion.JPG) 
**Diseñe 3 roles con acceso a esta BD** 

**ROL RRHH**  
Este rol permite realizar las consultas sobre la base de datos, se utilizará para MOnitoreo y consulta, no tiene acceso a la tabla de salarios JOBS y tiene acceso completo a EMPLOYEES.

**ROL FINANCIERO**  
Este rol tiene acceso a las tablas JOBS.escritura y EMPLOYEES.lectura.  

**ROL AUDITOR**  
Este rol tiene la función de consulta general sobre las bases de datos. 

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Rolauditor.JPG)  

* Comprobando el rol asignado al usuario Auditor:  


**Cree los roles** 

**Cree usuarios para asignarle los roles creados** 

**Verifique que los usuarios solo tienen los privilegios  Autorizados**
