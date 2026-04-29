# 📡🛰️ Desafíos Galileo — SQL & Análisis de Datos con SQLite
Este repositorio contiene una serie de desafíos prácticos de análisis de datos utilizando SQLite y Python.
El objetivo es resolver problemas reales de gestión y consulta de bases de datos, aplicando SQL para obtener información útil y generar recomendaciones basadas en datos.
Los ejercicios se desarrollan sobre una base de datos llamada biblioteca.db, que simula un sistema de préstamos de libros.

### 🚀 Contenido del proyecto
El notebook Desafíos_Galileo.ipynb incluye tres desafíos principales:

####🔹 Desafío 1 — Sistema de multas
Implementación de un sistema automático de multas para préstamos devueltos con retraso.
Incluye:
- Creación de una tabla multas con claves foráneas y validaciones.
- Cálculo del importe de la multa (0,50 € por día de retraso).
- Inserción y consulta de multas asociadas a cada préstamo.
Habilidades demostradas:
SQL DDL, SQL DML, cálculos con fechas, integridad referencial.

####🔹 Desafío 2 — Historial completo de usuario
Consulta avanzada que muestra:
- Todos los préstamos de un usuario (activos y devueltos).
- Total de días que ha tenido libros.
- Número de retrasos.
- Importe total de multas.
Habilidades demostradas:
Consultas agregadas, subconsultas, joins, filtros condicionales.

####🔹 Desafío 3 — Recomendaciones de libros
Generación de recomendaciones basadas en el historial del usuario:
- Libros del mismo autor que ya ha leído.
- Filtrado para mostrar solo libros que aún no ha tomado prestados.
Habilidades demostradas:
Recomendación basada en contenido, subconsultas anidadas, joins múltiples.

### 🛠️ Tecnologías utilizadas
- Python
- SQLite3
- Pandas
- SQL (DDL, DML, consultas avanzadas)

### 🎯 Objetivo del repositorio
Este proyecto demuestra tu capacidad para:
- trabajar con bases de datos reales,
- diseñar tablas y relaciones,
- realizar consultas SQL complejas,
- resolver problemas prácticos de negocio,
- integrar SQL con Python para análisis.

### 📁 Estructura del repositorio
/Desafíos_Galileo.ipynb   # Notebook con los ejercicios
/README.md                # Este archivo
