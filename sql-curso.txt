-RDM = Relational Database Management System.
--Software que nos ayuda a manejar nuestra BD. Ej: MySQL, Postgres, etc.
--Nos Facilitan la conección con los lenguajes de programación (php, python, js, etc).

-El CRUD (Create, Read, Update, Delete) son las operaciones que se pueden realizar con los RDM.
-QUERY = Consulta / Petición -> Son aquellos 'pedidos' de datos realizados en los lenguajes hacia los RDM para hacer
las operaciones queridas.

-SQL -> Relacional. Se representan con tablas (columnas y filas). Usadas para almacenar datos organizados. Estas tablas se relacionan entre sí
a partir de keys.

-NoSQL -> No Relacional. Son representados de diferentes formas (key-value, json, etc). Usados para almacenar datos que no requieren relacionarse,
básicamente serían como un cajón donde solo se guardan los  datos y no se necesitan un orden. Son más flexibles, escalables y mayor rendimiento que 
las relacionales (esto se debe a que las relacionales pesan más debido a las diferentes tablas que puede llegar a haber).

SQL = Structured Query Language
-Columna ID: el id es un número único generado automaticamente (autoincremental) para cada dato que se agrega a la tabla de datos, 
es un identificador para el dato. Nos sirve para relacionar tablas.
-Fila = Registro.

Relaciones en BD Relacional: se trata del enlace que puede haber en dos (o más tablas)  donde la clave principal 
de una tabla se asocia con la clave externa de otra tabla utilizando las relaciones de la base de datos.
La cardinalidad es una restricción en una relación que especifica el número de instancias 
de entidad que una entidad específica puede estar relacionada a través de la relación.

Las tres clasificaciones de relaciones son: uno a uno, uno a muchos y muchos a muchos o muchos a uno.
Uno a Uno: Una entidad del conjunto de entidades A puede asociarse con a lo sumo una entidad del conjunto de entidades B y viceversa.
Uno a muchos: Una entidad del conjunto de entidades A puede asociarse con más de una entidad del conjunto de entidades B, sin embargo, una entidad del conjunto de entidades B puede asociarse con, como máximo,a una entidad.
Muchos a muchos: Las relaciones de muchos a muchos tienen "muchos" especificados para ambas cardinalidades.
Muchos a uno: Más de una entidad del conjunto de entidades A puede asociarse como máximo con una entidad del conjunto de entidades B, sin embargo, una entidad del conjunto de entidades B puede asociarse con más de una entidad del conjunto de entidades A.

-Las Columnas ID (las columnas que tengas las id's de los registros), se le dicen Primary Key. 
-Cuando en la tabla B hay una columna con la Id de registros de A (para relacionar ambas tablas), estas id se le 
denomina Foreign Key.

