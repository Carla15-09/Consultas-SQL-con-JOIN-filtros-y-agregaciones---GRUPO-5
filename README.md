# Consultas-SQL-con-JOIN-filtros-y-agregaciones---GRUPO-5
Descripción del Proyecto

Este proyecto consiste en el desarrollo de una base de datos para una clínica veterinaria utilizando Oracle SQL Developer. El objetivo principal es aplicar consultas SQL básicas y avanzadas mediante el uso de instrucciones como SELECT, WHERE, ORDER BY, INNER JOIN, GROUP BY, HAVING, funciones de agregación (SUM, COUNT, AVG) y subconsultas.

La base de datos simula el funcionamiento de una veterinaria, permitiendo gestionar información relacionada con propietarios, mascotas, veterinarios, especialidades y consultas médicas.

Integrantes del Proyecto
Sandro Iker Fernández Lima
Brittany Carla Paredes Chávez
Gabriel Alexander Rojas Silva
Rodolfo Enrique Zambrano Alban
Institución

Universidad Técnica de Ambato
Facultad de Ingeniería en Sistemas Electrónica e Industrial
Carrera de Software

Tecnologías Utilizadas
Oracle Database XE
Oracle SQL Developer
Java JDK
Objetivos
Objetivo General

Aplicar consultas SQL utilizando SELECT, WHERE, ORDER BY, INNER JOIN, GROUP BY, HAVING, SUM, COUNT, AVG y subconsultas en Oracle SQL Developer.

Objetivos Específicos
Desarrollar consultas SQL básicas y avanzadas para la recuperación y organización de información.
Implementar relaciones entre tablas mediante INNER JOIN.
Aplicar funciones de agregación y subconsultas para el análisis estadístico de datos.
Estructura de la Base de Datos

La base de datos VETERINARIA_DB está conformada por las siguientes tablas:

PROPIETARIO
ESPECIE
ESPECIALIDAD
VETERINARIO
MASCOTA
CONSULTA

Las tablas están relacionadas mediante llaves primarias y foráneas para garantizar la integridad de los datos.

Funcionalidades Implementadas
Consultas Básicas
Filtrado de registros con WHERE
Ordenamiento con ORDER BY
Consultas de rangos y condiciones
Relaciones entre Tablas
Uso de INNER JOIN
Relación entre mascotas, propietarios, veterinarios y consultas
Funciones de Agregación
COUNT()
SUM()
AVG()
MIN()
MAX()
Consultas Avanzadas
Subconsultas
Agrupaciones con GROUP BY
Filtros sobre agrupaciones con HAVING
Ejemplos de Consultas Realizadas
Mostrar mascotas mayores a 4 años
Mostrar consultas ordenadas por costo
Mostrar mascota, propietario y ciudad
Contar mascotas por especie
Mostrar veterinarios cuyos ingresos superen el promedio
Mostrar el total de dinero generado por consultas
Mostrar propietarios con más de una mascota
Mostrar la consulta más costosa y la más barata
Requisitos Previos

Antes de ejecutar el proyecto se debe instalar:

Oracle Database XE
Oracle SQL Developer
Java JDK
Configuración de la Conexión

Crear una conexión en Oracle SQL Developer con los siguientes parámetros:

Usuario: VETERINARIA_DB
Contraseña: VETERINARIA_DB
Host: localhost
Puerto: 1521
SID: xe
Ejecución del Proyecto
Abrir Oracle SQL Developer.
Crear una nueva conexión.
Ejecutar el script de creación de tablas.
Ejecutar los scripts INSERT INTO.
Ejecutar las consultas SQL desarrolladas.
Aprendizajes Obtenidos
Manejo de bases de datos relacionales.
Implementación de relaciones entre tablas.
Optimización de consultas SQL.
Uso de funciones de agregación y subconsultas.
Trabajo colaborativo en desarrollo de bases de datos.
Recomendaciones
Validar correctamente los datos ingresados.
Mantener nombres claros y organizados para tablas y atributos.
Practicar consultas más complejas y optimizadas.
Documentar adecuadamente cada consulta desarrollada.
Referencias
Oracle, Oracle Database SQL Language Reference 21c, 2023.
R. Elmasri y S. Navathe, Fundamentals of Database Systems, 7th ed., Pearson, 2016.
A. Silberschatz, H. Korth y S. Sudarshan, Database System Concepts, 7th ed., McGraw-Hill, 2019.
J. Viescas y M. Hernandez, SQL Queries for Mere Mortals, 4th ed., Addison-Wesley, 2018.
Oracle, Oracle SQL Developer User’s Guide, 2024.
Licencia

Proyecto académico desarrollado con fines educativos para la asignatura de Base de Datos.
