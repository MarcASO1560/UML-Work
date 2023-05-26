# UML de cosecha propia. (Parte A)
## Enunciado: Sistema de Ventas Online de Videojuegos.
El objetivo es diseñar una aplicación que permita a los usuarios comprar videojuegos directamente desde nuestra plataforma. Para ello, necesitaremos un Diagrama UML que nos ayude a estructurar y visualizar la aplicación.

### Menú del cliente.

La aplicación contará con un "MenúCliente", donde los usuarios podrán:

- Buscar videojuegos
- Ver su carrito de compras
- Acceder al servicio de atención al cliente

### Búsqueda de videojuegos y feedback de los usuarios.

La búsqueda de videojuegos se manejará mediante la clase "BibliotecaVJ", que mostrará los géneros de videojuegos disponibles. 

La clase "BibliotecaVJ" se conectará con "GeneroVJ", que contendrá todos los juegos de cada género. 

Finalmente, "Videojuego" estará conectada con "ReseñaVJ" para que los usuarios puedan escribir y publicar reseñas con puntuaciones de los juegos, proporcionando un feedback valioso para la mejora continua de nuestros videojuegos.

### Proceso de compra.

A su vez, "GeneroVJ" se vinculará con "Videojuego", permitiendo acciones como la compra del juego. Para gestionar el proceso de compra, "Videojuego" se conectará con "Pago".

Esta clase también estará vinculada con "Carrito", lo que permitirá la compra de varios juegos a la vez.

### Atencion al cliente.

En "AtencionCliente" se busca que el usuario pueda comunicarse con los trabajadores mediante un correo que se escribiría desde el propio programa o bien comunicandose dejando el numero de teléfono en especifico en una esquina para que el cliente pueda llamar si lo vé necesario.

## Resultado:

![Modelo UML]()

