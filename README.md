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
Este rol permite realizar las consultas sobre la base de datos, se utilizará para Monitoreo y consulta solo ejecutara select sobre todas las tablas excepto la tabla JOBS que contiene salarios y tiene acceso completo a EMPLOYEES para realizar update e insert.

**CREACCION DE ROLL RRHH**    
![Image of Yaktocat](https://github.com/jomaarango/Taller3G1/blob/taller-3-borrador/rol%20creado%20de%20recursos%20humanos.PNG)   

**CONFIGURACION DE ROLL**    
![Image of Yaktocat](https://github.com/jomaarango/Taller3G1/blob/taller-3-borrador/configuriacion%20de%20permisos%20del%20rol%20RRHH.PNG)  


**CREACCION DE USUARIO**  
![Image of Yaktocat](https://github.com/jomaarango/Taller3G1/blob/taller-3-borrador/CREACION%20DE%20USUARIO%20Y%20ASIGNACION%20DE%20ROL%20RRHHH.PNG)  


**PERMISOS DE LECTURA**    
![Image of Yaktocat](https://github.com/jomaarango/Taller3G1/blob/taller-3-borrador/PERMISOS%20DEL%20JOMAARANGO.PNG)  

**PERMISOS DENEGADOS DEL ROL RRHH**

![Image of Yaktocat](https://github.com/jomaarango/Taller3G1/blob/taller-3-borrador/Evidencia%20que%20no%20puede%20ver%20datos%20de%20la%20tabla%20JOBS.PNG)  

**ROL FINANCIERO**  
Este rol tiene acceso a las tablas JOBS.escritura y EMPLOYEES.lectura.

configuracion del rol  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero1.PNG)  

permisos login  


![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero2.PNG)  
conexion

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero3.PNG)  

Consulta select 


![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero4.PNG)  

Consulta select 

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero5.PNG)  

Evidencia de aplicacion del ROL 

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Financiero6.PNG)   


**ROL AUDITOR**  
Este rol tiene la función de consulta general sobre las bases de datos.   

* Creación del rol Audito denominado Audito_rol.  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/Rolauditor.JPG)  
* Comprobando el rol asignado al usuario Auditor, realizamos el login.  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/sesionauditor.JPG)  

* Luego realizamos una consulta SELECT.  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/selectauditor.JPG)  

* Al tratar de realizar un INSERT se genera un error por el nivel de privilegios.  

![Image of Yaktocat](https://raw.githubusercontent.com/jomaarango/Taller3G1/taller-3-borrador/insertauditor.JPG)  
