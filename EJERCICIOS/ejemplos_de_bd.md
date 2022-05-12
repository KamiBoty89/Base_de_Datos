Reseña la historia de SQL.

<b> Introducción

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
