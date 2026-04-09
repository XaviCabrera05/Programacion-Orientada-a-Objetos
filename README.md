 Programación Orientada a Objetos (POO)
 ¿Qué es la POO?

La Programación Orientada a Objetos (POO) es un paradigma de programación que organiza el código en objetos, los cuales representan entidades del mundo real.

Cada objeto combina:

Atributos (datos)
Métodos (funciones o comportamientos)

Su objetivo principal es facilitar el desarrollo de software modular, reutilizable y mantenible.

¿Cuáles son los pilares fundamentales de la POO?

Los 4 pilares fundamentales son:

Encapsulamiento
Abstracción
Herencia
Polimorfismo
Definición de cada pilar
1. Encapsulamiento

Consiste en ocultar los detalles internos de un objeto y permitir el acceso solo a través de métodos definidos.

✔ Protege los datos
✔ Evita modificaciones indebidas

Ejemplo:
Una clase CuentaBancaria no permite modificar el saldo directamente, solo mediante métodos como depositar() o retirar().

 2. Abstracción

Es la capacidad de mostrar solo lo esencial y ocultar lo complejo.

✔ Simplifica el uso del sistema
✔ Reduce la complejidad

Ejemplo:
Cuando usas un carro, no necesitas saber cómo funciona el motor, solo cómo conducir.

 3. Herencia

Permite que una clase herede propiedades y métodos de otra.

✔ Reutilización de código
✔ Organización jerárquica

Ejemplo:

Clase padre: Animal
Clase hija: Perro (hereda de Animal)
 4. Polimorfismo

Permite que un mismo método tenga diferentes comportamientos según el contexto.

✔ Flexibilidad
✔ Código más dinámico

Ejemplo:
Un método hacerSonido():

En Perro → ladra
En Gato → maúlla ¿Por qué los lenguajes orientados a objetos soportan la POO?

Lenguajes como Java, Python o C++ incluyen soporte para POO porque:

Permiten modelar problemas reales fácilmente
Facilitan el mantenimiento del código
Promueven la reutilización
Mejoran la escalabilidad de sistemas grandes

 Estos lenguajes incorporan directamente clases, objetos, herencia y otros mecanismos necesarios.

 ¿En qué contextos aplicar cada pilar?
 Encapsulamiento
Sistemas financieros (seguridad de datos)
Aplicaciones donde se controla el acceso a información
 Abstracción
Interfaces de usuario
APIs
Sistemas complejos (ocultar lógica interna)
🧬 Herencia
Sistemas con jerarquías (ej: empleados, vehículos)
Reutilización de código en proyectos grandes
 Polimorfismo
Interfaces gráficas
Sistemas extensibles
Manejo de múltiples tipos de objetos
