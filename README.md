Lista Enlazada
Clase Nodo:

Esta clase representa un nodo en una lista enlazada.
Tiene dos propiedades:
$dato: almacena el valor del nodo.
$siguiente: apunta al siguiente nodo en la lista (inicialmente null).
El constructor de la clase toma un valor $dato y lo asigna a la propiedad correspondiente.
Clase ListaEnlazada:

Esta clase representa una lista enlazada.
Tiene una propiedad $cabeza que apunta al primer nodo de la lista (inicialmente null).
El constructor inicializa la lista vacía.
Este fragmento de código establece la estructura básica para una lista enlazada, pero no incluye métodos para manipular la lista, como agregar o eliminar nodos.

Uso de una Pila
Creación de una Pila:

Se utiliza un array ($pila) para implementar una pila.
Se añaden elementos a la pila usando array_push(), que agrega elementos al final del array.
Extracción de un Elemento:

Se utiliza array_pop() para eliminar y devolver el último elemento agregado a la pila.
El elemento extraído se almacena en $elemento.
Salida:

Se imprime el último elemento ingresado a la pila.
Este fragmento de código demuestra cómo se puede utilizar un array en PHP para implementar una estructura de datos tipo pila (LIFO - Last In, First Out).

Conclusión Final
Ambos fragmentos de código ilustran conceptos fundamentales de estructuras de datos en programación:

Listas Enlazadas: Son útiles para situaciones donde se requiere una estructura dinámica que permita inserciones y eliminaciones eficientes en cualquier posición. Sin embargo, el código proporcionado solo define la estructura básica sin operaciones de manipulación.

Pilas: Son estructuras de datos que siguen el principio LIFO, útiles para tareas como el manejo de expresiones, deshacer operaciones, etc. El código muestra cómo implementar una pila usando arrays en PHP, lo cual es sencillo y efectivo para muchos casos de uso.
