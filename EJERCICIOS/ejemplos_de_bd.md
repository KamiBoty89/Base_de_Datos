Reseña la historia de SQL.

Introducción

El lenguaje de consulta estructurado (SQL) es un lenguaje de base de datos normalizado, utilizado por losdiferentes motores de bases de datos para realizar determinadas operaciones sobre los datos o sobre laestructura de los mismos. Pero como sucede con cualquier sistema de normalización hay excepcionespara casi todo; de hecho, cada motor de bases de datos tiene sus peculiaridades y lo hace diferente deotro motor, por lo tanto, el lenguaje SQL normalizado (ANSI) no nos servirá para resolver todos losproblemas, aunque si se puede asegurar que cualquier sentencia escrita en ANSI será interpretable porcualquier motor de datos.

Breve Historia

La historia de SQL (que se pronuncia deletreando en inglés las letras que lo componen, es decir "ese-cu-ele" y no "siquel" como se oye a menudo) empieza en 1974 con la definición, por parte de DonaldChamberlin y de otras personas que trabajaban en los laboratorios de investigación de IBM, de un lenguajepara la especificación de las características de las bases de datos que adoptaban el modelo relacional.Este lenguaje se llamaba SEQUEL (Structured English Query Language) y se implementó en un prototipollamado SEQUEL-XRM entre 1974 y 1975. Las experimentaciones con ese prototipo condujeron, entre1976 y 1977, a una revisión del lenguaje (SEQUEL/2), que a partir de ese momento cambió de nombre pormotivos legales, convirtiéndose en SQL. El prototipo (System R), basado en este lenguaje, se adoptó yutilizó internamente en IBM y lo adoptaron algunos de sus clientes elegidos. Gracias al éxito de estesistema, que no estaba todavía comercializado, también otras compañías empezaron a desarrollar susproductos relacionales basados en SQL. A partir de 1981, IBM comenzó a entregar sus productosrelacionales y en 1983 empezó a vender DB2. En el curso de los años ochenta, numerosas compañías(por ejemplo Oracle y Sybase, sólo por citar algunos) comercializaron productos basados en SQL, que seconvierte en el estándar industrial de hecho por lo que respecta a las bases de datos relacionales.
En 1986, el ANSI adoptó SQL (sustancialmente adoptó el dialecto SQL de IBM) como estándar para loslenguajes relacionales y en 1987 se transfomó en estándar ISO. Esta versión del estándar va con elnombre de SQL/86. En los años siguientes, éste ha sufrido diversas revisiones que han conducido primeroa la versión SQL/89 y, posteriormente, a la actual SQL/92.
El   hecho   de   tener   un   estándar   definido   por   un   lenguaje   para   bases   de   datos   relacionales   abrepotencialmente el camino a la intercomunicabilidad entre todos los productos que se basan en él. Desde elpunto de vista práctico, por desgracia las cosas fueron de otro modo. Efectivamente, en general cadaproductor adopta e implementa en la propia base de datos sólo el corazón del lenguaje SQL (el asíllamado Entry level o al máximo el Intermediate level), extendiéndolo de manera individual según la propiavisión que cada cual tenga del mundo de las bases de datos.
Actualmente, está en marcha un proceso de revisión del lenguaje por parte de los comités ANSI e ISO,que   debería   terminar   en   la   definición   de   lo   que   en   este   momento   se   conoce   como   SQL3.   Lascaracterísticas principales de esta nueva encarnación de SQL deberían ser su transformación en unlenguaje   stand-alone   (mientras   ahora   se   usa   como   lenguaje   hospedado   en   otros   lenguajes)   y   laintroducción de nuevos tipos de datos más complejos que permitan, por ejemplo, el tratamiento de datosmultimediales. 

Componentes del SQL

El lenguaje SQL está compuesto por comandos, cláusulas, operadores y funciones de agregado. Estoselementos se combinan en las instrucciones para crear, actualizar y manipular las bases de datos.

Comandos

Existen dos tipos de comandos SQL:

•Los DLL que permiten crear y definir nuevas bases de datos, campos e índices. 
•Los DML que permiten generar consultas para ordenar, filtrar y extraer datos de la base de datos.

Ejemplifica los Gestores de Bases de Datos según el tipo de BD.

Un Sistema Gestor de Base de Datos (SGBD) o DataBase Managenent System (DBMS) es un sistema que permite la creación, gestión y administración de bases de datos, así como la elección y manejo de las estructuras necesarias para el almacenamiento y búsqueda de información del modo más eficiente posible.

En la actualidad, existen multitud de SGBD y pueden ser clasificados según la forma en que administran los datos en:

•Relacionales (SQL)
•No relacionales (NoSQL)

Sistemas Gestores de bases de datos Relacionales (SQL)
Desde que se comenzó a usar el modelo de bases de datos relacionales, en 1970, ha ido sufriendo una serie de transformaciones hasta convertirse, hoy en día, en el modelo más utilizado para administrar bases de datos.

Este modelo se basa fundamentalmente en establecer relaciones o vínculos entre los datos, imaginando una tabla aparte por cada relación existente con sus propios registros y atributos.

Los principales Sistemas gestores de bases de datos relacionales (SGBD SQL) actualmente son:

 ![image](https://user-images.githubusercontent.com/101414787/168116192-702bd1f8-dabc-4ab7-b9e1-b072c8c19609.png)
 
 ![image](https://user-images.githubusercontent.com/101414787/168116241-577d7cb2-9ef7-46fd-b6de-c797e5ba00df.png)
 
 ![image](https://user-images.githubusercontent.com/101414787/168116293-7813269d-fd4f-47d1-bedd-343f82e43751.png)
 
 ![image](https://user-images.githubusercontent.com/101414787/168116332-541bbe24-cd56-4104-bd95-5b9b256c5386.png)
 
 ![image](https://user-images.githubusercontent.com/101414787/168116374-c98ff6a1-c792-473e-839a-0baf49da34f2.png)
 
 ![image](https://user-images.githubusercontent.com/101414787/168116408-11ae685e-2eec-420b-b264-5bfaf5b1882c.png)



Sistemas Gestores de bases de datos No Relacionales (NoSQL)
Una base de datos no relacional (NoSQL) es aquella base de datos que:

•No requiere de estructuras de datos fijas como tablas
•No garantiza completamente las características ACID
•Escala muy bien horizontalmente.
•Se utilizan en entornos distribuidos que han de estar siempre disponibles y operativos y que gestionan un importante volumen de datos.

Para la administración de este tipo de bases de datos, actualmente los principales sistemas gestores de bases de datos (SGBD NoSQL) son:

![image](https://user-images.githubusercontent.com/101414787/168116613-65a4aadf-3461-4588-81d4-68aced8651ef.png)

![image](https://user-images.githubusercontent.com/101414787/168116633-fcf35df9-7a93-405b-b4a5-fc1c5ccb5c27.png)

![image](https://user-images.githubusercontent.com/101414787/168116686-f600e724-1860-4c01-ad21-b17228751fb8.png)





