Hola Ale!

El proyecto fue implementado sin vistas. Devuelvo JSON para no extenderme con los tiempos de entrega.

Implementé JWT de forma "nativa", es decir, sin passport, debido a que nunca pude hacerlo funcionar correctamente. En la clase correspondiente le consulté a mi tutor, pero no pudo salvarme la duda. También te consulté a vos por el chat de coder, pero por cuestiones de tiempo tampoco fue posible despejarme la duda. Lo resolví de esta forma para cumplir con las consignas, por lo cual en el login devuelvo el JWT para ser utilizado en los encabezados de las peticiones que lo requieran.

El modo admin se activa desde la consola cuando levantamos el server con el flag < -u admin > para la vista de órdenes y la adminstración de productos disponibles.

El tiempo de sesión se configura en minutos.

El modelo está preparado para integrar distintas bases de datos. Empecé a desarrollar la conexión con Firebase y MySQL, pero por cuestiones de tiempo lo dejo como dice la consigna, sólo con mongodb.

Para ingresar al chat con postman primero hay que hacer un get en la carpeta chat/ingreso al chat, luego conectarse al socket (dentro de la carpeta "Coder Proyecto Final Chat)