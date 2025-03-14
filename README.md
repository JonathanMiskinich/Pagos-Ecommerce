# Sistema de Gesti�n de Inventarios para una Tienda Online 

## Descripci�n 
Este proyecto es un sistema backend para gestionar el inventario de una tienda online. Permite agregar productos, actualizar existencias y notificar cuando un producto est� por agotarse. El sistema est� dise�ado para ser eficiente, escalable y f�cil de integrar con otras plataformas.

## Requisitos 
### Estructuras de datos
- **�rbol binario de b�squeda (BST)**: Para almacenar productos ordenados por ID.
- **Lista enlazada (LinkedList)**: Para gestionar el historial de movimientos de inventario (agregar, eliminar, actualizar).

### Algoritmos
- **B�squeda binaria**: Para buscar productos por nombre.
- **Reordenamiento autom�tico**: Reordena el inventario cuando un producto alcanza un nivel m�nimo de stock.

### Patrones de dise�o
- **Observer**: Para notificar al equipo de compras cuando un producto est� por agotarse.
- **Decorator**: Para a�adir funcionalidades adicionales a los productos (por ejemplo, descuentos, env�o gratis).

### L�gica de programaci�n
- **Validaci�n de cantidades**: No se pueden agregar productos con cantidades negativas al inventario.
- **Reporte de productos agotados**: Genera un reporte de productos agotados.

## Tecnolog�as utilizadas 
- **Lenguaje de programaci�n**: C#
- **Estructuras de datos**: �rboles binarios de b�squeda, listas enlazadas.
- **Patrones de dise�o**: Observer, Decorator.
- **Herramientas**: Git, GitHub, Visual Studio.