# Act_4.2_Estructuras_Lineales_Dinamicas
Proyecto desarrollado en Java para administrar trabajos de biblioteca mediante una estructura de datos lineal dinámica de tipo Cola. Se utilizan conceptos de herencia, polimorfismo y programación genérica.

## Equipo #2
CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo
Desarrollar un sistema de gestión de trabajos de biblioteca en Java mediante una estructura de datos lineal dinámica de tipo Cola. El programa permite registrar, consultar y atender publicaciones, aplicando programación genérica, herencia y polimorfismo.

# Tecnologías utilizadas
Java
Java Swing
Apache NetBeans
Git y GitHub

# Características
Registro de libros, revistas y artículos.

Captura de datos generales y específicos de cada publicación.

Implementación de una Cola FIFO (First In, First Out).

Inserción de nuevos trabajos en la cola.

Consulta del primer elemento.

Atención y eliminación del primer elemento.

Visualización de los trabajos registrados.

Opción para vaciar la cola.

Validación de los datos ingresados.

Interfaz gráfica para facilitar el uso del sistema.

# Estructura del proyecto
El proyecto está organizado mediante clases que permiten administrar los diferentes tipos de publicaciones:

Trabajo: clase principal con los atributos generales.

Libro: clase heredada que contiene el número de páginas.

Revista: clase heredada que contiene el número de edición.

Articulo: clase heredada que contiene el nombre de la conferencia.

Clase de Cola: administra los trabajos mediante la estructura FIFO.

Interfaz gráfica: permite capturar información y ejecutar las operaciones de la cola.

# Interfaz gráfica
La aplicación cuenta con una interfaz desarrollada en Java Swing mediante el GUI Builder de NetBeans.

Desde ella se pueden seleccionar los tipos de publicaciones, ingresar sus datos y utilizar los botones para encolar, atender, consultar el frente, mostrar los trabajos y vaciar la estructura.

La información de la cola se presenta en un área de visualización para facilitar el seguimiento de los elementos registrados.
