CRUD es el acrónimo de Create (Crear), Read (Leer), Update (Actualizar) y Delete (Borrar).Es un concepto que se utiliza para describir las cuatro operaciones que se pueden realizar en las bases de datos y sistemas de gestion de informacion.

Estas operaciones pueden a los usuarios crear nuevos datos, leer los exstentes, actulizarlos y eliminarlos.

La idea es que cualquier sistema de informacion que interactue con datos proporcione funcionalidades para crer, leer, actualizar y eliminar dichos datos.
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos
para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

---

Teddy Sun LAMP se refiere a un conjunto de tecnologías para el desarrollo web que incluye Linux, Apache, MySQL y PHP (también conocido como LAMP). Aquí te proporciono un ejemplo básico de un CRUD utilizando Teddy Sun LAMP:

1. Configuración de la base de datos MySQL:
Asegúrate de tener una base de datos MySQL configurada con una tabla adecuada para almacenar los datos que planeas manipular con el CRUD. Por ejemplo, podrías tener una tabla llamada usuarios con campos como id, nombre, apellido, etc.

2. Creación de archivos PHP para el CRUD:
a. Create (Crear):
Página: create.php (formulario para ingresar nuevos datos).
Funcionalidad: Procesar el formulario y agregar los datos a la base de datos.
b. Read (Leer):
Página: read.php (mostrar los datos existentes).
Funcionalidad: Consultar la base de datos y mostrar los datos en una tabla.
c. Update (Actualizar):
Página: update.php (formulario prellenado con los datos existentes para ser modificados).
Funcionalidad: Procesar el formulario actualizado y actualizar los datos correspondientes en la base de datos.
d. Delete (Eliminar):
Página: delete.php (confirmación de eliminación).
Funcionalidad: Eliminar los datos seleccionados de la base de datos.
