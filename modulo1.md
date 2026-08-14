# MÓDULO 1: Introducción a las Bases de Datos y SQL (45min)

## ¿Qué es una Base de Datos Relacional?
[🔗](https://www.oracle.com/lad/database/what-is-a-relational-database/):  
Es una forma de organizar información en tablas con filas y columnas, estableciendo relaciones entre las diferentes tablas a través de claves. Esto facilita la organización, almacenamiento, recuperación y gestión de datos de manera eficiente, especialmente cuando se necesita mantener la integridad y consistencia de la información. 

### Conceptos clave:
- **Tabla (table)**:  
  En una base de datos relacional la información se organiza en tablas, que son estructuras bidimensionales con filas y columnas.
- **Fila (row)**:  
  Una fila representa un registro o entidad de datos.
- **Columna (column)**:  
  Una columna representa un atributo o campo de los datos (que describe la información de la tabla).
- **Clave primaria (PK / primary key)**:  
  Es un atributo (una columna) o un conjunto de atributos (varias columnas) dentro de una tabla que identifica de forma única cada fila (registro) de esa tabla.
- **Clave foránea (FK / foreign key)**:  
  Es un atributo (una columna) o un conjunto de atributos (varias columnas) en una tabla (la tabla "hija" o "dependiente") que hace referencia a la clave primaria de otra tabla (la tabla "padre" o "referenciada").
- **Restricción (constraint)**:  
  Es una regla o condición que se impone sobre los datos de una tabla o columna para asegurar la integridad, precisión y consistencia de la información almacenada en la base de datos.
- **Consulta (query/queries)**:  
  Una consulta es una orden o petición que se hace a una base de datos para buscar, ver, cambiar o borrar información.  

### Sistemas de Gestión de Bases de Datos Relacionales (RDBMS)(Motor - Engine):
- SQLite
- MySQL
- MariaDB
- PostgreSQL
- SQL Server
- Oracle Database, etc.

### Ventajas:
- **Organización estructurada**:  
  Los datos se organizan de forma clara y sistemática.
- **Facilidad de consulta**:  
  Se pueden realizar consultas complejas utilizando SQL para recuperar información específica.
- **Integridad de datos**:  
  Se garantiza que los datos sean consistentes y precisos.
- **Relaciones entre datos**:  
  Permite establecer relaciones entre diferentes tablas para obtener una visión más completa de la información.
- **Escalabilidad**:  
  Las bases de datos relacionales pueden manejar grandes volúmenes de datos.

### Ejemplos de uso:
- **Gestión de bases de datos en el comercio minorista**:  
  Para almacenar información sobre productos, clientes y pedidos.
- **Atención médica**:  
  Para almacenar información sobre pacientes y registros médicos.
- **Finanzas**:  
  Para almacenar información sobre transacciones y cuentas.
- **Comercio electrónico**:  
  Para almacenar información sobre productos, usuarios y pedidos.
- **Redes sociales**:  
  Para almacenar información sobre usuarios y sus interacciones.

### ¿Qué es SQL y para qué sirve?
- **Definición**:  
  SQL es un lenguaje estandarizado por el ANSI (American National Standards Institute) e ISO (International Organization for Standardization), lo que asegura una gran compatibilidad entre diferentes sistemas de gestión de bases de datos relacionales con el fin de gestionar y manipular bases de datos relacionales.
- **Propósito**:  
  Proporcionar una sintaxis universal para realizar una **amplia gama de operaciones** en bases de datos relacionales.
- **Categorías de comandos SQL**:
  + **DDL - Lenguaje de Definición de Datos**:  
    Uso: crear, modificar o eliminar objetos en la base de datos.  
    Comandos principales: CREATE, ALTER, DROP, etc.
  + **DML - Lenguaje de Manipulación de Datos**:  
    Uso: consultar y modificar los datos.  
    Comandos principales: SELECT, INSERT, UPDATE, DELETE, etc.  
    *Este curso se enfoca, en el uso de instrucciones DML para consultar datos.*
  + **DCL - Lenguaje de Control de Datos**:  
    Uso: determinar quién puede ver o modificar los datos.  
    Comandos principales: GRANT, DENY, REVOKE, etc.
  + **TCL - Lenguaje de Control de Transacciones**:  
    Uso: gestionar las transacciones en una base de datos.  
    Comandos principales: COMMIT, ROLLBACK, SAVEPOINT, etc.
   
### ¿Qué es y cuándo usar NoSQL?  
[🔗](https://www.oracle.com/lad/database/nosql/what-is-nosql/)
- **Significado**:  
Originalmente significaba "Non-SQL", ahora se interpreta más comúnmente como "Not Only SQL" o "No Solo SQL" y se refiere a una categoría amplia de sistemas de gestión de bases de datos que se desvían del modelo relacional tradicional y, por lo tanto, no utilizan SQL como su lenguaje de consulta principal o exclusivo.
- **Comparación**:  
  Mientras que las bases de datos relacionales (SQL) se basan en un esquema rígido, tablas estructuradas, claves primarias y foráneas, y la estricta adherencia a la atomicidad, consistencia, aislamiento y durabilidad (ACID), las bases de datos NoSQL ofrecen un enfoque más flexible y variado para el almacenamiento y la recuperación de datos.
- **¿Cuándo usar NoSQL?**
  + Necesita escalabilidad horizontal para manejar grandes volúmenes de datos y/o tráfico.
  + Trabaja con datos no estructurados o semi-estructurados cuyo esquema es flexible o evoluciona rápidamente.
  + La velocidad de desarrollo y la capacidad de iterar rápidamente sobre el modelo de datos son cruciales.
  + La consistencia estricta (ACID) es menos crítica que la disponibilidad y la toleración a particiones (modelo BASE: Basically Available, Soft state, Eventually consistent).
  + El modelo de datos natural del problema se ajusta mejor a uno de los modelos NoSQL (por ejemplo, grafos para relaciones, documentos para jerarquías complejas).

### Entorno de Trabajo (Video Demo)
- Instalación y configuración de un Cliente SQL (DBeaver / MySQL Workbench / PHPMyAdmin).
- Conexión a una base de datos de ejemplo.
