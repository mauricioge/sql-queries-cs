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

### Casos de uso en Ciberseguridad:
- **Auditoría de accesos y detección de intrusiones (SIEM)**:  
  Propósito: Registrar cada intento de autenticación en la infraestructura para detectar patrones anómalos.
- **Gestión de Vulnerabilidades y Activos (Asset & Patch Management)**:  
  Propósito: Mapear qué servidores o equipos tienen vulnerabilidades conocidas (CVEs) pendientes de corregir.
- **Control de Acceso Basado en Roles (RBAC/IAM)**:  
  Propósito: Garantizar el principio de menor privilegio (Least Privilege) administrando qué usuario puede ejecutar qué acción.
- **Gestión de Incidentes de Seguridad (SOC)**:  
  Propósito: Registrar y hacer seguimiento a alertas de seguridad atendidas por el Centro de Operaciones de Seguridad (SOC).

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
   
### Entorno de Trabajo (Video Demo)
- Instalación y configuración de un Cliente SQL (DBeaver / MySQL Workbench / PHPMyAdmin).
- Conexión a una base de datos de ejemplo.
