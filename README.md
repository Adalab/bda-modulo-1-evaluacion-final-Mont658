<<<<<<< HEAD
Mi Tienda
=======
# Mi Tienda

>>>>>>> 07538161c879a8824a6b31d21a9ef009defd9d7f
# TiendaOnline - Proyecto de Gestión

Este es un proyecto para manejar el inventario y las ventas de una tienda online.És bastante básico.

## Lo que se puede hacer

* **Manejo de Productos:**
    * Añadir productos nuevos al inventario.
    * Ver qué productos tenemos en stock.
    * Buscar un producto por su nombre.
    * Actualizar cuántos productos tenemos.
    * Quitar productos del inventario.
    * Saber cuánto vale todo el inventario junto.
* **Ventas:**
    * Dejar que un cliente elija qué quiere comprar y en qué cantidad.
    * Calcular cuánto tiene que pagar el cliente.
    * Actualizar el stock después de que se hace la venta.

## Cómo está hecho el código

Todo está dentro de una clase que se llama `TiendaOnline`.

### La clase `TiendaOnline`

Aquí está toda la lógica de la tienda.

#### Cosas que tiene la clase (Atributos)

* `inventario` (lista): Aquí guardamos los productos. Cada producto es como una ficha con el nombre, precio y cantidad.
* `clientes` (diccionario): Esto es para llevar la cuenta de los clientes.
* `ventas_totales` (float): Para saber cuántas ventas hemos hecho en total.

#### Cosas que puede hacer la clase (Métodos)

* `__init__(self)`: Esto es lo primero que se ejecuta al crear la tienda.
* `agregar_producto(self, nombre, precio, cantidad)`: Para añadir un producto.
* `ver_inventario(self)`: Para ver qué tenemos en la tienda.
* `buscar_producto(self, nombre)`: Para buscar un producto por su nombre.
* `actualizar_stock(self, nombre, cantidad)`: Para cambiar la cantidad de un producto.
* `eliminar_producto(self, nombre)`: Para quitar un producto de la tienda.
* `calcular_valor_inventario(self)`: Para saber cuánto vale todo lo que tenemos en la tienda.
* `realizar_compra(self)`: Para que el cliente pueda comprar.


## Para probarlo

Hay un ejemplo de cómo usarlo al final del archivo. Puedes modificarlo para probar diferentes cosas.


