# Sistema de gestión de bases de datos

Es aquel que nos permite manejar todas las operaciones relacionadas a las bases de datos como la inserción, la actualización, eliminación y consulta.

## Gestión de transacciones

Los motores de bases de datos tienen algunas características como lo es la **gestión de transacciones** esto hace referencia por ejemplo al soporte para **ACID** QUE SIGNIFICA

- Atomicidad
- Consistencia
- Aislamiento
- Durabilidad

Esto garantiza la integridad y confiabilidad de la base de datos

### Control de concurrencia

Mecanismo que permite que multiples usuarios realicen operaciones al mismo tiempo sin conflictos

---

## Lenguaje de consulta

Es la interpretación y ejecución de consultas. Los motores de bases de datos relacionales utilizan el lenguaje **SQL** para la manipulación de datos mientras que los motores **NoSQL** pueden usar otros lenguajes o APIs.

### optimización de consultas

las bases de datos implementan generalmente optimizadores que nos ayudan a que el procesamiento de la información sea mas rápida y eficaz.

### Manejo de datos

Almacenamiento : Los motores gestionan como de almacenan físicamente los datos em discos y como se recupera esta información de forma eficiente

### Seguridad y autenticación

- Gestión de usuarios y roles
- Cifrado de datos
- Auditoria de transacciones en la base de datos

### Escalabilidad y rendimiento

- Escalabilidad horizontal y vertical
- Cache
- Replicación de la información
- Particionamiento de los datos

### Integridad y Consistencia de los datos

- Restricciones y disparadores a la hora de realizar procesos.

### Soporte para tipos de datos avanzados

Permite tener compatibilidad don distintos tipos de datos y funciones

### Respaldo y recuperación

Los **Backups** automáticos o manuales se utilizan para crear respaldos periódicos en caso de fallas

### Compatibilidad y extension

- **Interoperatividad :** Soporte para integrarse con otros sistemas a traves de APIs, ODBC/JDBC o controladores nativos

- **Extensibilidad :** Capacidad de agregar nuevas funcionalidades a traves de modulos o plugins
