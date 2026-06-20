# Sistema de Gestión de Restaurante (POO Python)

**Estudiante:** Anderson Johao Rodriguez Espinosa 
**Asignatura:** Programación Orientada a Objetos - Semana 4  

## Descripción del Sistema
Este es un software básico modular desarrollado en Python utilizando los fundamentos de la Programación Orientada a Objetos. Modela el comportamiento de un restaurante administrando el menú de productos disponibles y los consumos individuales de los clientes de manera estructurada.

## Estructura del Proyecto
El código se organiza siguiendo la arquitectura de separación de responsabilidades:
- `modelos/`: Contiene las clases de las entidades de datos (`Producto` y `Cliente`).
- `servicios/`: Contiene la clase lógica de control (`Restaurante`) que coordina las operaciones.
- `main.py`: Punto de entrada que ejecuta y demuestra la funcionalidad general del sistema.

## Reflexión sobre la Modularización y POO
La separación de responsabilidades facilita significativamente el mantenimiento y la escalabilidad del software. Al aislar los modelos de datos de los servicios lógicos, cualquier cambio en la estructura de una entidad (como añadir un ID al producto) no afecta de forma directa el algoritmo de inicio en `main.py`. La POO nos permite abstraer elementos del mundo real (como platos y comensales) en objetos interactivos e independientes, logrando un código limpio, legible y reutilizable.