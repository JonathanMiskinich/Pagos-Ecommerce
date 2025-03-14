# Sistema de Gestión de Inventarios para una Tienda Online 

## Descripción 
Este proyecto es un sistema backend para gestionar el inventario de una tienda online. Permite agregar productos, actualizar existencias y notificar cuando un producto esté por agotarse. El sistema está diseñado para ser eficiente, escalable y fácil de integrar con otras plataformas.

## Requisitos 
### Estructuras de datos
- **Árbol binario de búsqueda (BST)**: Para almacenar productos ordenados por ID.
- **Lista enlazada (LinkedList)**: Para gestionar el historial de movimientos de inventario (agregar, eliminar, actualizar).

### Algoritmos
- **Búsqueda binaria**: Para buscar productos por nombre.
- **Reordenamiento automático**: Reordena el inventario cuando un producto alcanza un nivel mínimo de stock.

### Patrones de diseño
- **Observer**: Para notificar al equipo de compras cuando un producto esté por agotarse.
- **Decorator**: Para añadir funcionalidades adicionales a los productos (por ejemplo, descuentos, envío gratis).

### Lógica de programación
- **Validación de cantidades**: No se pueden agregar productos con cantidades negativas al inventario.
- **Reporte de productos agotados**: Genera un reporte de productos agotados.

## Tecnologías utilizadas 
- **Lenguaje de programación**: C#
- **Estructuras de datos**: Árboles binarios de búsqueda, listas enlazadas.
- **Patrones de diseño**: Observer, Decorator.
- **Herramientas**: Git, GitHub, Visual Studio.