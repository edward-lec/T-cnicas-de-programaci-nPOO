"Ejemplo de Técnicas de programación POO en Python"

Este proyecto presenta un ejemplo práctico del uso de las principales técnicas de Programación Orientada a Objetos (POO) aplicadas en Python.  
Para ilustrar estos conceptos se utiliza una pequeña jerarquía de vehículos compuesta por una clase base y dos clases derivadas.

"Contenido del proyecto"

El código está organizado utilizando los cuatro pilares de la POO:

"Abstracción"
Se define una clase abstracta llamada "Vehiculo", la cual sirve como estructura general para cualquier tipo de vehículo.  
Incluye atributos protegidos y un método abstracto que obliga a las clases hijas a implementar su propia versión.

"Encapsulación"
Los atributos están protegidos mediante el prefijo `_`, y se utilizan métodos "getter" y "setter" para acceder y modificar el valor del modelo con una validación básica.

"Herencia"
Las clases "Auto" y "Moto" heredan de la clase base "Vehiculo", reutilizando su constructor e incorporando características propias de cada tipo de vehículo.

"Polimorfismo"
Ambas clases hijas implementan su propia versión del método `descripcion()`, lo que permite que diferentes objetos respondan de manera distinta al mismo método.


"Funcionalidad" 

El archivo incluye una función `main()` donde se:

- Crean instancias de `Auto` y `Moto`.
- Se almacenan en una lista para demostrar polimorfismo al llamar al método `descripcion()`.
- Se prueba la encapsulación modificando el modelo de la moto mediante el setter.

