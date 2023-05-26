# UML de cosecha propia. (Parte A)
## Enunciado: Sistema de Ventas Online de Videojuegos.
El objetivo es diseñar una aplicación que permita a los usuarios comprar videojuegos directamente desde nuestra plataforma. Para ello, necesitaremos un Diagrama UML que nos ayude a estructurar y visualizar la aplicación.

### Menú del cliente.

La aplicación contará con un "MenúCliente", donde los usuarios podrán:

- Buscar videojuegos
- Ver su carrito de compras
- Acceder al servicio de atención al cliente

### Búsqueda de videojuegos y feedback de los usuarios.

La búsqueda de videojuegos se manejará mediante la clase "BibliotecaVJ", que mostrará los géneros de videojuegos disponibles, calcular la cantidad total de videojuegos existentes en la tienda (para presumir) y acceder a la clase "GeneroVJ" que tembién contiene un contador de juegos del género, y la lista con los nombres de los videojuegos. Esta clase de "GeneroVJ" esta conectada a la clase "Videojuego".

La clase "BibliotecaVJ" se compone por al menos un videojuego.

La clase "Videojuego" estará conectada con "ReseñaVJ" para que los usuarios puedan escribir y publicar reseñas con puntuaciones de los juegos, proporcionando un feedback valioso para la mejora continua de nuestros videojuegos.

Un videojuego no tiene porque tener reseñas.

### Proceso de compra.

Para gestionar el proceso de compra, "Videojuego" se conectará con "Pago", que también estará vinculada con "Carrito", lo que permitirá la compra de varios juegos a la vez o de un solo videojuego.

### Atencion al cliente.

En "AtencionCliente" se busca que el usuario pueda comunicarse con los trabajadores mediante un correo que se escribiría desde el propio programa o bien comunicandose dejando el numero de teléfono en especifico en una esquina para que el cliente pueda llamar si lo vé necesario.

## Resultado:

![Modelo UML](UML_Propia_Cosecha(1).jpg)

