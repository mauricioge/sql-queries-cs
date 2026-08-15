# MÓDULO 1: Consultas Básicas (CRUD) (1h 15min)

## Comentarios
- Comentar **una línea** con: `--`
- Comentar **múltiples líneas** con: `/*` y `*/`

## ¿Qué es una Consulta (Query)?
Es una solicitud que se enviará a una base de datos con el fin de obtener un conjunto de resultados (que puede ser un valor único, una fila, una columna o una tabla).

## CRUD
- **¿A qué se le llama CRUD?**  
  Es el acrónimo formado por el conjunto de cláusulas:
  + **C**reate (Crear): `INSERT INTO`
  + **R**ead (Leer): `SELECT`
  + **U**pdate (Actualizar): `UPDATE`
  + **D**elete (Eliminar): `DELETE`

## Sentencias `SELECT` y `FROM`
- **Seleccionar todas las columnas en una tabla**  
  `SELECT * FROM tabla`
- **Seleccionar columnas específicas en una tabla**  
  `SELECT columna1, columna2, columna5 FROM tabla`
- **Incluir columnas estáticas**
  `SELECT 'Hola mundo' FROM tabla`
- **Incluir columnas calculadas**
  `SELECT columna1 + columna2 FROM tabla`
- **Alias de columna**  
  `SELECT columna1 AS nuevo_nombre FROM tabla`
- **Alias de tabla**  
  `SELECT columna1 FROM tabla AS nuevo_nombre`

## Filtrar Resultados con `WHERE`:
- **Operadores de comparación**:  
  `=`, `!=`, `<`, `>`, `<=`, `>=`
- **Operadores lógicos**:  
  `AND`, `OR`, `NOT`
- **Operador ENTRE**:  
  `BETWEEN` / `NOT BETWEEN`
- **Operador EN**:  
  `IN` / `NOT IN`
- **Operador SIMILAR A**:  
  `LIKE` / `NOT LIKE` (uso de `%` y `_`)
- **Operador ES NULO**:  
  `IS NULL` / `IS NOT NULL`

## Sentencia `INSERT INTO`
- **Insertar un registro en una tabla**  
  `INSERT INTO tabla (columna1, columna2) VALUES (valor1, valor2)`

## Sentencias `UPDATE` y `SET`
- **Actualizar TODOS los registros en una tabla**  
  `UPDATE tabla SET columna1 = valor1, columna2 = valor2`
- **Actualizar uno o más registros en una tabla con condición**  
  `UPDATE tabla SET columna1 = valor1, columna2 = valor2 WHERE condicion`

## Sentencias `DELETE` y `WHERE`
- **Eliminar TODOS los registros en una tabla**  
  `DELETE FROM tabla`
- **Eliminar uno o más registros en una tabla con condición**  
  `DELETE FROM tabla WHERE condicion`

## Ordenar Resultados con `ORDER BY`:
- **Orden ascendente `ASC` (predeterminado)(de menor a mayor)**  
  `ORDER BY columna1 ASC`
- **Orden descendente `DESC` (de mayor a menor)**  
  `ORDER BY columna1 DESC`
- **Ordenar usando más de una columna**  
  `ORDER BY columna1 ASC, columna2 DESC`

## Limitar Resultados con `LIMIT` / `TOP`:
- **Solicitar un número específico de filas**  
  `SELECT * FROM tabla LIMIT 10`
