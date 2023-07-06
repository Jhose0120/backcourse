#Clase 2
Tipos de Bases NoSQL
* Documentales: se empareja cada clave con una estructura de datos compleja que se denomina documento, existen otras bases de datos documentales como Cloud Firebase o Couchbase.
* Grafos: Se utilizan para almacenar información sobre redes de datos, como las conexiones sociales. Neo4j es uno de los ejemplos mas populares de bases datos de este tipo.
* Clave - Valor: Son las bases de datos NoSQL mas simples. Cada elemento de la base de datos se almacena como un nombre de atributo (o “clave”), junto con su valor para acceso de memoria rápida. un ejemplo de estas bases de datos es redis.
* rientada a columnas: Estas bases de datos, como Cassandra (la mas popular) o Hbase, permiten realizar consultas en grandes conjuntos y almacenan los datos en columnas, en lugar de filas.
---
___
Las bases de datos NoSQL tienen la característica de tener gran facilidad de escalamiento.
* Escalamiento vertical: incrementar las características de esa misma maquina (+RAM, +CPU, almacenamiento)
* Escalamiento horizontal: Tener una maquina (o nodo) y “copiarla” (ahora tienes varios nodos o maquinas con las mismas características), asegurando alta disponibilidad, sistemas de replicacion o tener un conjunto que responda en simultaneo. Esto te libera de la necesidad de escalar de forma vertical.
## A tener en cuenta
Hacer escalamiento vertical es mas fácil pero mas costoso con el paso del tiempo. el escalamiento horizontal es mas costoso en el inicio pero luego el precio se mantiene “estándar” con el paso del tiempo.
Las bases de datos NoSQL aprovechan muy bien el 

* Escalamiento horizontal: puedes armar un cluster de información en el que los datos se van a conectar entre si (varios nodos). Esto hace que los bases datos de datos NoSQL sea mas fácilmente escalable o replicable que una SQL.
* Que es Replicacion? una técnica en la que, una ves distribuimos la base de datos en varios nodos (EH😉), mediante un load balancer, asigna las peticiones y consultas a cada uno de los nodos en una forma ordenada. Esto permite procesamiento en paralelo y también alta disponibilidad (si una replica falla, habrá otra disponible). Esto no es posible en el escalamiento vertical.
este curso es un “combo” de cursos de MongoDB, el otro curso es el curso de Modelado de datos con MongoDB.