# Bases de Datos

Es un sistema que permite almacenar, consultar y modificar los datos. Estas pueden ser relacionales o no relacionales.

Esto puede ser similar a un archivo de excel que esta compuesto por filas y columnas, donde las filas representan registros y las columnas representan atributos. todo esto lo vemos relacionado en tablas cando hablamos de bases de datos relacionales.

### Tipos de bases de datos

## Relacionales **RBDMS**

Los datos de almacenan en tablas organizadas en filas y columnas. Cada fila representa una entidad única y cada columna representa un atributo de esa entidad.

**RBDMS Esquema rígido :**

- Es un esquema rígido que debe definirse de antemano y los satos deben ajustarse a este esquema.
- **Relaciones :** las relaciones se definen entre tablas mediante claves primarias y foráneas
- **Escalabilidad :** por lo general se escala de forma vertical, mejorando en hardware del servidor
- **Integridad :** Garantiza la consistencia y la integridad de los datos mediante restricciones como claves únicas, claves primarias y reglas de integridad referencia.

**Motores de Bases de Datos RELACIONALES comunes :**

- MySQL
- PostGreSQL
- Oracle
- SQLite

---

### No relacionales **NoSQL**

No utilizan tablas. Pueden usar estructuras como documentos, grafos, clave-valor, archivos Json o columnas anchas

**NoSQL Esquema Flexible :**

- Requieren un esquema fijo. Los datos se pueden almacenar en diferentes formatos y pueden agregar atributos nuevos sin modificar las estructuras existentes

- La Escalabilidad normalmente se genera de manera Horizontal agregando nodos o servidores a medida que crecen los datos.

**Motores de Bases de Datos NoSQL comunes :**

- MongoDB
- Cassandra
- Redis
- DynamoDB
