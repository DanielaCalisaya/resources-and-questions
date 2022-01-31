# Módulo 6 - Bases de datos

## Instalación en Windows 
XAMPP https://www.apachefriends.org/pt_br/index.html

DBeaver https://dbeaver.io/download/

## Clase 28 Diseño y relaciones
- MySQL: ¿es una base de datos relacional o no relacional?
- ¿Por qué MySQL corre en otro servidor diferente al de nuestra aplicación web?
- ¿Con qué otro elemento podemos hacer la analogía de una tabla en una base de datos?
- ¿Cuántas tablas pueden existir en una base de datos?
- ¿Existe un límite de columnas dentro de una tabla?
- ¿Cuáles son los tipos de datos más comunes en una base de datos?
- ¿Cómo podemos relacionar dos tablas entre sí?
- ¿Qué son los constraints y qué nos permiten hacer?
- ¿La Foreign Key es un constraint?

## Clase 29 Manipulación y consulta de datos
Date format https://www.w3schools.com/sql/func_mysql_date_format.asp

- En una consulta tipo SELECT, ¿cómo podemos hacer para seleccionar TODAS las columnas de una tabla?
- Cuál de los siguientes operadores no funcionaría en una consulta con el WHERE: LIKE, =, BETWEEN, <>, ON.
- ¿Cuáles son los valores posibles al implementar la cláusula ORDER BY?
- ¿Qué no debemos olvidar poner en el WHERE cuando estamos haciendo un UPDATE o un DELETE?
- ¿Para qué sirve la función de alteración EXTRACT?
- ¿Es obligatorio usar el alias al momento de realizar una consulta tipo SELECT?

## Clase 30 Uniones y funciones de agregación
JOIN https://www.vichaunter.org/desarrollo-web/joins-mysql-bien-explicado-lo-necesitas-saber

- ¿Cuáles son las tres directrices que trae consigo MySQL para poder insertar, actualizar y borrar registros de una tabla?
- ¿Con qué directriz de MySQL podemos traer registros de una tabla filtrando por una determinada condición?
- Si tuviéramos que hacer un buscador con paginación, ¿cuáles son las dos cosas de MySQL que no pueden faltar en nuestras consultas?
- Para hacer uso del sistema relacional, ¿cómo podemos unir tablas entre sí?
- ¿Para qué sirve la cláusula DISTINCT?
- ¿Podemos nombrar al menos 3 funciones de agregación?

## Clase 31 Introducción, modelos y consultas básicas
Uso de promesas https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Using_promises

promisesAll() https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Promise/all

Sequelize https://sequelize.org/

DataTypes https://sequelize.org/v4/manual/tutorial/models-definition.html

findAll, findByPk, findOne https://sequelize.org/master/manual/model-querying-basics.html#simple-select-queries

Where y operadores https://sequelize.org/v5/manual/querying.html

Order y limit https://sequelize.org/v4/manual/tutorial/querying.html#pagination-limiting

- Además de la instalación de Sequelize en el proyecto, ¿qué otros paquetes de npm necesitamos instalar?
- ¿Con qué comando podemos generar las carpetas base (config y models) dentro del proyecto?
- ¿Cómo se definen las columnas o atributos de una tabla dentro de un modelo?
- ¿Cuál es la diferencia entre los métodos findAll() y findByPk()?
- ¿Para qué se usan los operadores —como el like— que provee Sequelize?
- ¿Cómo podemos generar una consulta que ordene los resultados y traiga una cantidad límite de los mismos?

## Clase 33 Relaciones y CRUD completo

Relaciones 1:N https://sequelize.org/master/class/lib/associations/base.js~Association.html

Relaciones N:M https://sequelize.org/master/class/lib/associations/base.js~Association.html

## Clase 34 Cierre de módulo

SQL tutorial https://www.w3schools.com/sql/

Normalización https://www.youtube.com/watch?v=pHkv7LxkLIo

Guía de MySQL https://www.mysqltutorial.org/

## Biografía:

- Head First SQL (Inglés)

Recomendamos este libro que abarca desde qué es una base de datos a cómo realizar scripts en la base de datos. Muy didáctico y muy recomendado.

- Bases de datos

Editorial Alfaomega. Autores: Enrique José Reinosa y otros. Este libro es práctico y apunta directo a las bases de datos relacionales. Vamos a poder profundizar en el armado de las mismas y en el poder de correr validaciones y scripts dentro de la misma base de datos.

- NoSQL Distilled (Inglés)

Este libro es más teórico, pero nos introduce a todos los conceptos relacionados a bases de datos que no son relacionales, algo que sin duda nos va a dejar un valor agregado interesante.
https://martinfowler.com/books/nosql.html

- Paso a paso con Sequelize (Inglés)

En este blog encontraremos un espectacular paso a paso de la creación de un CRUD con Sequelize. Si bien ya hemos visto este proceso en repetidas ocasiones, nunca está de más tener otra visión al respecto.
https://www.bezkoder.com/node-js-express-sequelize-mysql/
