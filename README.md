# Primera Practica Integradora
Servidor basado express que trabaja con base de datos en MongoDB.

## Pasos a seguir para correr la aplicacion:
- npm i
- node src/app.js
- El servidor iniciara en el puerto 8080.

## Testing de la aplicacion:
- Se abrirá la ruta raíz desde el navegador a la url http://localhost:8080
- Debe visualizarse el contenido de la vista index.handlebars, el cual debe mostrar los 10 productos iniciales llamados desde la base de datos de MongoDB.
- Se buscará en la url del navegador la ruta http://localhost:8080/realtimeproducts
- Se pedira autentificar con un nombre de usuario o correo.
- Se corroborará que el servidor haya conectado con el cliente, en la consola del servidor deberá mostrarse un mensaje de “Nuevo cliente conectado”.
- Se debera mostrar el Chat donde los mensajes que se envien se guardaran para el usuario previamente registrado en la base de datos de MongoDB
- Se debe mostrar la lista de productos llamados desde MongoDB.
- Se podra eliminar un producto al introducir el ID del producto y dar click en "Delete", el resultado se vera reflejado inmediatamente en la vista.
- Se podra agregar un producto al introducir los campos del producto y dar click en "Add", el resultado se vera reflejado inmediatamente en la vista.
- Tambien se podran modificar los productos con el id indicado desde PostMan como se hizo en practicas enteriores.
- Tambien se podra acceder al carrito con el id indicado desde PostMan como se hizo en practicas anteriores.
