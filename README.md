## Principios SOLID

Los principios SOLID son cinco principios fundamentales del diseño de software orientado a objetos que nos ayudan a crear código más mantenible, flexible y escalable.

### Pero ¿Qué significa SOLID?

**SOLID** es un acronimo que representa:

**S** - **Single Responsibility Principle (Principio de Responsabilidad Única)** 
	<ins>_Una clase debe tener una sola razón para cambiar_</ins>, es decir, debe tener una única responsabilidad. Esto significa que cada clase debe enfocarse en hacer una cosa y hacerla bien.

**O** - **Open/Closed Principle (Principio Abierto/Cerrado)** Las entidades de software 
	<ins>_deben estar abiertas para extensión pero cerradas para modificación_</ins>. Debes poder agregar nueva funcionalidad sin modificar el código existente.

**L** - **Liskov Substitution Principle (Principio de Sustitución de Liskov)** 
	<ins>_Los objetos de una clase derivada deben poder reemplazar a los objetos de la clase base_</ins> sin alterar el funcionamiento del programa. Las subclases deben ser sustituibles por su clase padre.

**I** - **Interface Segregation Principle (Principio de Segregación de Interfaces)** 
	<ins>_Los clientes no deben depender de interfaces que no utilizan_</ins>. Es mejor tener muchas interfaces específicas que una interfaz general y monolítica.

**D** - **Dependency Inversion Principle (Principio de Inversión de Dependencias)** 
	<ins>_Los módulos de alto nivel no deben depender de módulos de bajo nivel_</ins>. Ambos deben depender de abstracciones. Las abstracciones no deben depender de los detalles, sino que los detalles deben depender de las abstracciones.

### Una explicación más simple

Imagina que estás construyendo con bloques de LEGO. Los principios SOLID son como **reglas para construir de manera inteligente**:

**S - Una pieza, una función** <ins>_Cada pieza de LEGO tiene un propósito específico_</ins>. Una rueda es para rodar, una ventana es para ver. En programación: cada parte de tu código debe hacer solo una cosa.

**O - Agregar sin romper** <ins>_Puedes agregar más piezas a tu construcción sin desarmar lo que ya hiciste_</ins>. En código: puedes añadir nuevas funciones sin cambiar lo que ya funciona.

**L - Las piezas similares funcionan igual** <ins>_Si cambias una rueda por otra rueda del mismo tipo, tu auto sigue funcionando_</ins>. En código: si cambias una parte por otra similar, todo debe seguir funcionando.

**I - No necesitas todo el set** <ins>_No necesitas comprar un set gigante de 1000 piezas si solo quieres construir un auto pequeño_</ins>. En código: solo usa las funciones que realmente necesitas.

**D - Usa las instrucciones, no inventes** <ins>_En lugar de adivinar cómo armar algo, sigues las instrucciones del manual_</ins>. En código: usa las "instrucciones" (interfaces) en lugar de depender de piezas específicas.