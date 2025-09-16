## Principios SOLID

Los principios SOLID son cinco principios fundamentales del diseño de software orientado a objetos que nos ayudan a crear código más mantenible, flexible y escalable.

### Pero ¿Qué significa SOLID?

**SOLID** es un acronimo que representa:

**S** - **Single Responsibility Principle (Principio de Responsabilidad Única)** Una clase debe tener **una sola razón para cambiar**, es decir, debe tener una única responsabilidad. Esto significa que cada clase debe enfocarse en hacer una cosa y hacerla bien.

**O** - **Open/Closed Principle (Principio Abierto/Cerrado)** Las entidades de software **deben estar abiertas para extensión pero cerradas para modificación**. Debes poder agregar nueva funcionalidad sin modificar el código existente.

**L** - **Liskov Substitution Principle (Principio de Sustitución de Liskov)** **Los objetos de una clase derivada deben poder reemplazar a los objetos de la clase base** sin alterar el funcionamiento del programa. Las subclases deben ser sustituibles por su clase padre.

**I** - **Interface Segregation Principle (Principio de Segregación de Interfaces)** **Los clientes no deben depender de interfaces que no utilizan**. Es mejor tener muchas interfaces específicas que una interfaz general y monolítica.

**D** - **Dependency Inversion Principle (Principio de Inversión de Dependencias)** <ins>Los módulos de alto nivel no deben depender de módulos de bajo nivel</ins>. Ambos deben depender de abstracciones. Las abstracciones no deben depender de los detalles, sino que los detalles deben depender de las abstracciones.