# Unidad C0: Recapitulación

Autor.

Introducción (sobre el documento o el tema tratado) -- mejor escribirla al final.

## Concepto y origen de las bases de datos
¿Qué son las bases de datos? ¿Qué problemas tratan de resolver? Definición de base de datos.

#####--Es un conjunto de datos organizado a la que puedes añadir, eliminar o modificar datos. Tratan de usar los datos de forma eficiente. 

## Sistemas de gestión de bases de datos
¿Qué es un sistema de gestión de bases de datos (DBMS)? ¿Qué características de acceso a los datos debería proporcionar? Definición de DBMS.
#####- Un sistema de gestión de base de datos es un software que permite administrar y controlar una base de datos. Este deberia facilitar el uso de una BD a muchos usuarios a la vez, además de almacenar los datos de manera persistente, proporcionar una cierta independencia del metodo de almacenamiento, que esten almacenados confidencialmente de manera encryptada.

### Ejemplos de sistemas de gestión de bases de datos
¿Qué DBMS se usan a día de hoy? ¿Cuáles de ellos son software libre? ¿Cuáles de ellos siguen el modelo cliente-servidor?

* Oracle DB - Se usa - No es software libre - Cliente-servidor
* IMB Db2 - Se usa - No es software libre - Cliente-servidor
* SQLite - No se usa - Software libre - No
* MariaDB - No se usa - Software libre - Cliente-servidor
* SQL Server - Se usa - No software libre - Cliente-servidor
* PostgreSQL - Se usa - Software libre - Cliente-servidor
* mySQL - Se usa - Software libre - Cliente-servidor

## Modelo cliente-servidor
¿Por qué es interesante que el DBMS se encuentre en un servidor? ¿Qué ventajas tiene desacoplar al DBMS del cliente? ¿En qué se basa el modelo cliente-servidor?

* __Cliente__: es la maquina o el software que va a acceder a un servicio.
* __Servidor__: es el que ejecuta el servicio (en este caso la base de datos) y se lo proporciona al cliente. Este tiene el SGBD y el SGBD la base de datos.
* __Red__: es mediante lo que el cliente accede al servidor. En todas las redes hay una IP con un puerto.
* __Puerto de escucha__: El servidor tiene un puerto de escucha las peticiones del cliente.
* __Petición__: el cliente envia una peticion al servidor con una consulta que quiere hacer y el servidor le responde con una respuesta.
* __Respuesta__: es lo que el servidor le envia al cliente que realiza la petición.

## SQL
¿Qué es SQL? ¿Qué tipo de lenguaje es?
Structure Query Language. Es un lenguaje declarativo, estandarizado por dos agencias de estandarizacion: ANSI e ISO. Lenguaje de 4a generación que se estandarizó en 1986. Existen las BBDD Relacionales (SQL) y No Relacionales (No SQL). 

### Instrucciones de SQL

#### DDL: CREATE, ALTER, RENAME...
#### DML: SELECT, INSERT, UPDATE, DELETE...
#### DCL: GRANT, REVOKE
#### TCL: COMMIT, ROLLABLE

## Bases de datos relacionales
¿Qué es una base de datos relacional? ¿Qué ventajas tiene? ¿Qué elementos la conforman?
- Una base de datos es una base de datos con varias tablas relacionadas entre si. Algunas ventajas de este tipo de base de datos relacional es que son muy sencillas a la hora de trabajar con ellas y también permite la accesibilidad de varios ususarios en una misma base de datos al mismo tiempo.

* __Relación (tabla)__: uno a uno, uno a varios, varios a varios.
* __Atributo/Campo (columna)__: Int, varchar, date...
* __Registro/Tupla (fila)__: valores numericos.

## Conlcusión
- En conclusión una BBDD es un conjunto organizado que almacena datos y permite modificarlos, borrarlos y añadirlos. Esta BBDD se encuentra almacenada en un sistema de gestión de base de datos. Existen muchas BBDD diferentes pero algunas de las más utilizadas son Oracle, SQLite, mySQL... Muchas de ellas presentan un modelo cliente-servidor y usan el lenguaje SQL con muchas instrucciones para realizar varias acciones diferentes.

Iván Montiano González