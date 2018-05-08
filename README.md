# sql-server-apuntes
Apuntes de sql server

## Reglas de base de datos
- No pueden existir dos tablas con el mismo nombre ni registro
- Cada tabla es un conjunto de filas y columnas
- La Relacion entre una tabla padre y un hijo se lleva a cabo por medio de las claves primarias y claves foraneas
## Caracteristicas de la Base de Datos
- Las claves primarias son la clave principal
- Debe haber una diferencia entre Modelo Logico, Modelo Fisico
Diseño de Bsae de Datos
- El diseño de una base de datos consiste en definir la estructura de los datos que debe tener un sistema de informacion determinado
- Las fases en el proceso de diseño son el modelo conceptual, el logico y el fisico
- Modelo logico: una de sus caracteristicas es que tiene relaciones muchos a muchos
## Normalizacion
Debe tener *Consistencia*, y mejorar el rendimiento
`C -> Create
 R -> Read
 U -> Update
 D -> Delete
`
## 1ra Forma Normal
- Tiene Primary Key
## 2ra Forma Normal
- Las tuplas tienen sentido (Tupla en contexto)
## 3ra Forma Normal
- No existe ninguna dependencia funcional transitiva en los atributos que no son clave

DDL (Data Definition Language)
- Create
- Alter
(ESCRIBIR SENTENCIAS)

CREATE TABLE

NOT NULL = Valores no nulos
UNIQUE = valores unicos
PRIMARY KEY = Llave primaria
FOREIGN KEY = Llave foranea
CHECK 
