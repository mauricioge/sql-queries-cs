# SQL: Lenguaje de Consultas Estructuradas - 4 horas

## A QUIÉN ESTÁ DIRIGIDO:
Este curso está diseñado para principiantes y personas que deseen reforzar sus conocimientos en la creación de consultas SQL para extraer y manipular datos de bases de datos relacionales.

## TEMARIO:

### MÓDULO 0: [Introducción a BBDD y SQL (45min)](https://github.com/mauricioge/sql/blob/main/modulo0.md)
- **¿Qué es una Base de Datos Relacional?**
  + Conceptos clave.
  + Sistemas de Gestión de Bases de Datos Relacionales (RDBMS)
  + Ventajas.
  + Casos de uso en Ciberseguridad.
- **¿Qué es SQL y para qué sirve?**
  + Definición.
  + Propósito.
  + Categorías de comandos SQL.
- **Entorno de Trabajo**
  + Instalación y configuración de un Cliente SQL.
  + Conexión a una base de datos de ejemplo.
  + Concepto de `SELECT` simple para ver una tabla.

### MÓDULO 1: [Consultas Básicas de Selección (1h 15min)](https://github.com/mauricioge/sql/blob/main/modulo1.md)
- **Sentencia `SELECT`**
  + Seleccionar todas las columnas (`SELECT *`).
  + Seleccionar columnas específicas (`SELECT columna1, columna2,`).
  + Incluir columnas estáticas (`SELECT 'Hola Mundo'`).
  + Incluir columnas calculadas (`SELECT columna1 + columna2`).
  + Renombrar columnas (`SELECT columna1, columna2,`).
  + Alias de columnas (`AS`).
- **Sentencia `FROM`**
- **Filtrar Resultados con `WHERE`:**
  + Operadores de comparación `=`, `!=`, `<`, `>`, `<=`, `>=`
  + Operadores lógicos `AND`, `OR`, `NOT`
  + Operador `BETWEEN` y `NOT BETWEEN`.
  + `IN` y `NOT IN`.
  + `LIKE` y `NOT LIKE` (uso de `%` y `_`).
  + `IS NULL` y `IS NOT NULL`.
- **Sentencia `INSERT INTO`**
- **Sentencia `UPDATE`**
- **Sentencia `DELETE`**
- **Ordenar Resultados (`ORDER BY`):**
  + Orden ascendente (`ASC`) y descendente (`DESC`).
  + Ordenar usando múltiples columnas.
- **Limitar Resultados (`LIMIT` / `TOP`):**
  + Cómo obtener un número específico de filas.

### MÓDULO 3: [Agregación y Agrupación de Datos (1h)](https://github.com/mauricioge/sql/blob/main/modulo3.md)
- **Funciones de Agregación:**
  + `COUNT()`: Contar filas.
  + `SUM()`: Sumar valores numéricos.
  + `AVG()`: Calcular el promedio.
  + `MIN()`: Encontrar el valor mínimo.
  + `MAX()`: Encontrar el valor máximo.
- **Agrupación de Resultados (`GROUP BY`):**
  + Agrupar datos por una o más columnas.
  + Uso de funciones de agregación con `GROUP BY`.
- **Filtrado de Grupos (`HAVING`):**
  + Diferencia entre `WHERE` y `HAVING`.
  + Filtrar resultados después de la agrupación.

### MÓDULO 4: [Combinación de Tablas (JOINs) y Subconsultas (1h)](https://github.com/mauricioge/sql/blob/main/modulo4.md)
- **Concepto de JOINs:**
  + Relaciones entre tablas.
- **Tipos de JOINs más comunes:**
  + `INNER JOIN`: Obtener filas coincidentes entre tablas.
  + `LEFT JOIN` (o `LEFT OUTER JOIN`): Incluir todas las filas de la tabla izquierda.
  + `RIGHT JOIN` (o `RIGHT OUTER JOIN`): Incluir todas las filas de la tabla derecha (mencionar brevemente).
- **Subconsultas (Subqueries):**
  + Concepto y cuándo utilizarlas.
  + Subconsultas en la cláusula `WHERE`.
  + Subconsultas como origen de datos.
- **Ejercicios Prácticos y Preguntas y Respuestas (15min)**
  + Resolver un par de problemas que integren los conceptos vistos.
  + Sesión abierta para preguntas y respuestas.

## Consideraciones Adicionales para el Curso:
- **Práctica Constante:** Cada módulo incluye ejercicios prácticos para que los participantes puedan aplicar lo aprendido.
- **Base de Datos de Ejemplo:** Para los ejercicios que realizaremos utilizaremos una base de datos sencilla pero consistente pero con todo lo necesario para que entender los conceptos y realizar prácticas.
- **Demostraciones en Video:** Puedes ver esta clase en video acá.
- **Recursos Adicionales:**
  + Descarga el PDF de este curso
  + Descarga la guía de referencia rápida de SQL
  + Documentación oficial
  + Plataformas de práctica online
