# Requisitos Funcionales
## Inventario
### RF - : Presenta en forma de lista los elementos del inventario
Se presenta el inventario del negocio en forma de tabla, donde cada fila debe ser un elemento del inventario. Las columnas de la tabla deben ser las sigueintes:
- Producto
- Categoria
- Cantidad

&nbsp;

### RF - : Permite cambiar las cantidades en almacen de un elemento
Se permite elegir un elemento de la lista y seleccionar un valor entero para substraerlo o a la cantidad en inventario de ese elemento

&nbsp;

### RF - : Permite agregar elementos a la lista
Se permite agregar un nuevo elemento a la lista, pidiendo la siguiente informacion:
- Nombre del elemento
- Categoria del elemento
- Cantidad en almacen a agregar al inventario

&nbsp;

### RF - : Permite cambiar el estado de grupos de elementos
Permite seleccionar un grupo de elementos de la lista del inventario, y otorgarles un estado distinto  

&nbsp;

## Agenda/Calendario
### RF - : La agenda permite visualizar las rentas en forma de un calendario o lista
La agenda recibe la informacion de las rentas desde el gestor, y las representa como recordatorios en en forma de un calendario de recordatorios

&nbsp;

### RF - : La agenda debe permitir interactuar con las rentas atravez de los recordatorios
Se puede interactuar con los recordatorios para:
- Visualizar los elementos rentados
- Visualizar la informacion de la renta
- Permitir alterar los elementos rentados
- Permitir alterar la informacion de la renta

&nbsp;

## Gestor
### RF - : Permite crear grupos de objetos rentados
Permite otorgarle a un grupo de objetos del inventario el estado de rentado, el sistema debe pedir los datos de la renta a la hora de usar esta funcion:
- Nombre de el cliente
- Fecha
- Direccion
- Contacto del cliente
Despues los elementos pasaran a tener el estado de "Rentado" y se agregara en la agenda un recordatorio