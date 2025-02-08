# SQL

Es un lenguaje de consulta estándar para el manejo de bases de datos relacionales

## Objetos en bases de datos

**Esquemas :** Un esquema puede existir en una base de datos dependiendo el area del negocio que se desee trabajar, es decir en una base de datos pueden haber diferentes esquemas dependiendo a que parte del negocio se este apuntando

**Tablas :** estén compuestas por filas y columnas he internamente las filas contienen registro o datos y las columnas contienen los atributos

- **Claves Primarias** las cuales actúan como identificador único que nos permite diferenciar los registros y asi evitar errores "ID's"

- **Claves foráneas :** Es la forma de poner una sub clave a un objeto la cual indica que se relaciona con otro identificador único fuera de este. por ejemplo en un producto tenemos el id de este el cual seria la clave primaria y este tendrá a su vez una categoría la cual tendrá el id de la categoría, este id se relacionara con la clave primaria de la categoría.

- **Vistas :** Una vista en SQL es como una "foto instantánea" o un "atajo" que te muestra solo una parte específica de esos datos, sin alterar la tabla original. Es como si crearas una ventana personalizada para ver solo lo que te interesa.

- **Procedimientos Almacenados :** Son bloques de codigo SQL que realizan tareas especificas como un **CRUD**

Create : Create
Read : Select
Update :Update
Delete :Delete
