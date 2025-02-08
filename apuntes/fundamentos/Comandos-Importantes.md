# Comandos Importantes

### DQL

Lenguaje de consulta de datos

### DDL

lenguaje de definición de datos hace referencia a la estructura de la tabla (crear eliminar o modificando los objetos dentro de la tabla)

**CREATE TABLE :** Crea una tabla estructurando los parámetros o columnas

```SQL
CREATE TABLE estudiantes (/*parámetros*/ id INT, nombre VARCHAR(50), edad INT)

```

**ALTER TABLE :** Permite modificar la estructura de esa tabla después de haberla creado, sin borrarla ni perder los datos que ya tiene.
Si tu tabla es de Clientes y quieres añadir una columna para Teléfono, usas ALTER TABLE para agregarla sin afectar los datos que ya están guardados.

**ADD columna\_ :** Agrega una columna seguida del nombre

```SQL
ALTER TABLE estudiantes ADD columna_grado VARCHAR(10)
```

**DROP TABLE :** Elimina la tabla

```SQL
DROP TABLE estudiantes
```

---

### DML

Lenguaje de manipulación de los datos para la información interna de la tabla

**INSERT INTO :** Genera un post de la estructura de información ya creada

```SQL
INSERT INTO estudiantes (id,nombre,edad) VALUES/*Añade el valor*/ (1,'JUAN',20)
```

### **WHERE es muy importante pues dice a quien le estoy haciendo el cambio**

### Si no pongo el WHERE se elimina toda la tabla

**UPDATE :** Modifica información ya existente

```SQL
UPDATE estudiantes Set edad = 21 WHERE id =1;
/*Cambia la edad del estudiante 1*/
```

**DELETE :** Elimina la información

```SQL
DELETE FROM estudiantes WHERE id = 1;
```

---

### DCL

Hace referencia al lenguaje de control de datos, es decir al los roles y permisos a un usuario en especifico de lo que puede hacer dentro del **CRUD**

```SQL
GRANT SELECT ON estudiantes To usuario1:
/*Da permisos de lectura*/
```

```SQL
REVOKE SELECT ON estudiantes FROM usuario1;
/*Le quita permisos al usuario*/
```

---

### TCL

Lenguaje de control de transacciones permitiendo tener mas control sobre las operaciones que realizamos en procedimientos complejos

**SAVEPOINT :** Es como un "marcador" dentro de una transacción larga. Te permite guardar un estado específico al que puedes volver si algo sale mal, sin cancelar toda la transacción.

**ROLLBACK :**Sirve para deshacer cambios realizados en una transacción si algo falla. Puedes volver al inicio de la transacción o a un SAVEPOINT específico.

**COMMIT :**Es como decir "¡Listo, guarda todos los cambios!". Cuando usas COMMIT, todas las operaciones de la transacción se aplican definitivamente en la base de datos.
