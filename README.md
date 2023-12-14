# Proyecto Final Java - Codo a Codo

Este proyecto es una extensión del proyecto anterior [Trabajo-practico-integrador-JS-Codo-a-Codo](https://github.com/fcongedo/Trabajo-practico-integrador-JS-Codo-a-Codo), en el marco del programa Codo a Codo de Java. La finalidad es ampliar las funcionalidades del sitio web existente, agregando capacidades de almacenamiento en base de datos, gestión de oradores y autenticación de usuarios.

## Descripción del Proyecto Anterior

El proyecto anterior consistió en la creación de una aplicación web que permitía a los usuarios comprar boletos para un evento específico. Incluía las siguientes funcionalidades:

- **Seleccionar una Categoría:** Los usuarios podían elegir una categoría de boleto entre Estudiante, Trainee o Junior, cada una con un descuento asociado.
  
- **Ingresar Información Personal:** Los usuarios debían proporcionar su nombre, apellido y dirección de correo electrónico en el formulario.
  
- **Especificar la Cantidad de Boletos:** Los usuarios podían ingresar la cantidad de boletos que deseaban comprar.
  
- **Calcular el Total a Pagar:** Al hacer clic en el botón "Resumen", la aplicación calculaba automáticamente el monto total a pagar teniendo en cuenta la categoría seleccionada y la cantidad de boletos. El monto total se mostraba en la interfaz.
  
- **Validación de Campos:** La aplicación realizaba validaciones de entrada para garantizar que los campos obligatorios se completaran correctamente. Los errores se mostraban al usuario.
  
- **Mensaje de Confirmación:** Cuando todos los campos eran válidos y se hacía clic en el botón "Resumen", se mostraba un mensaje de éxito con la información de la compra.
  
- **Restablecer Formulario:** El botón "Borrar" permitía a los usuarios restablecer el formulario y eliminar los estilos de error.

## Nuevas Funcionalidades Agregadas

### 1. Almacenamiento en Base de Datos de Oradores

Se implementó la funcionalidad para guardar registros de oradores en una base de datos. Estos oradores son las personas que darán conferencias o charlas.

### 2. Botón "Ver Oradores"

Se incorporó un botón en la interfaz que permite visualizar el estado actual de la base de datos con los oradores registrados. Esta función proporciona una lista de los oradores almacenados.

### 3. Autenticación de Usuarios

Se añadió la opción de iniciar sesión mediante un usuario y contraseña. Esta autenticación es necesaria para actualizar, modificar o eliminar los registros de la base de datos de oradores.

## Cómo Utilizar el Proyecto

### Requisitos Previos
- [NetBeans](https://www.oracle.com/tools/downloads/netbeans-netbeanside.html)
- [XAMPP](https://www.apachefriends.org/index.html)
- [MySQL Workbench](https://www.mysql.com/products/workbench/)

### Pasos para Utilizar el Proyecto
1. Clona este repositorio en tu máquina local usando el comando `git clone [https://github.com/fcongedo/Proyecto-Final-Codo-a-Codo]`.
2. Abre NetBeans e importa el proyecto.
3. Configura la conexión a la base de datos en el proyecto según las credenciales de tu entorno.
4. Inicia XAMPP y asegúrate de que Apache y MySQL estén activos.
5. Abre MySQL Workbench y configura la base de datos según las necesidades del proyecto.
6. Ejecuta el proyecto desde NetBeans y asegúrate de que la conexión a la base de datos funcione correctamente.
7. Explora las funcionalidades implementadas en la aplicación.

### Video de Demostración

Puedes encontrar una copia del [video de demostración](Demo-Proyecto-Final.mp4) dentro de este repositorio para una referencia rápida.

Además, aquí está el [enlace al video de demostración en YouTube](https://www.youtube.com/watch?v=0O47v6TwLxk&feature=youtu.be) que muestra las funcionalidades implementadas en el proyecto.

## Tecnologías Utilizadas

- Java
- MySQL Workbench
- XAMPP
- HTML
- CSS
- JavaScript
- Bootstrap
- SweetAlert2

Estas tecnologías fueron fundamentales para el desarrollo, gestión de la base de datos y el entorno de ejecución del proyecto.

## Agradecimientos

Agradezco a Miguel Angel Nefle por su invaluable apoyo y contribución al proyecto.

