# Informe Técnico

### MODELOS DE EJECUCIÓN
### Cliente:

**Ventajas**: Operaciones rápidas que no requieren interacción constante con el servidor, mejorando la experiencia del usuario.

**Desventajas**: Menor control sobre los datos, mayor riesgo de exposición si la seguridad no está correctamente gestionada.

**Ejemplo**: Al seleccionar una cita, el usuario puede interactuar con un calendario que se actualiza dinámicamente sin necesidad de refrescar la página.


### Servidor:

**Ventajas**: Más adecuado para operaciones sensibles como gestión de datos personales o transacciones, dando mayor seguridad.

**Desventajas**: Puede haber tiempos de respuesta más lentos si no está bien optimizado.

**Ejemplo**: Procesamiento de pagos y confirmaciones de reservas, que requieren comunicación directa con el servidor para validar y almacenar de forma segura.

### LENGUAJES DE PROGRAMACIÓN WEB
### JavaScript:

**Ventajas**: Lenguaje flexible, soportado por todos los navegadores y con muchas bibliotecas y frameworks.

**Desventajas**: Su tipado es débil, puede generar errores difíciles de rastrear en proyectos grandes.

### TypeScript: 

**Ventajas**: Agrega tipado estático a JavaScript, lo que facilita la detección de errores en la compilación. Ayuda a mantener un código más limpio y mantenible.

**Desventajas**: Requiere una fase de compilación adicional, haciendo el deasrrollo inicial más lento.

### COMPATIBILIDAD EN NAVEGADORES
Cada navegador maneja JavaScript de manera diferente debido a sus motores de ejecución:

**Chrome** (V8 Engine): Excelente rendimiento y compatibilidad con las últimas versiones.

**Safari**(WebKit): Buen rendimiento, pero puede tener problemas de compatibilidad con algunos elementos de CSS y nuevas características de JavaScript.

**Firefox**(SpiderMonkey): Compatibilidad con estándares web, pero no siempre tan eficiente en la ejecución de JavaScript como Chrome.

#### Problemas y soluciones:

**Compatibilidad ECMAScript**: Los navegadores más antiguos pueden no soportar las características más nuevas de JavaScript. Herramientas como Babel permiten transpilar código moderno para que sea compatible con versiones más antiguas de los navegadores.
  
**CSS inconsistente**: Algunas características de diseño, como propiedades avanzadas de CSS Grid o Flexbox, pueden no ser soportadas completamente en todos los navegadores. Se pueden emplear polyfills o postprocesadores CSS para mitigar este problema.

#### Integración de lenguajes de marcas con lenguajes de programación de clientes web

En aplicaciones modernas como la propuesta, el lenguaje de marcas (HTML) y los lenguajes de programación (JavaScript/TypeScript) están integrados de manera eficiente a través de frameworks como React.

**HTML** estructura la página, mientras que React se encarga de gestionar las interacciones dinámicas mediante su Virtual DOM, lo que permite modificar la interfaz de usuario sin recargar la página.

**CSS** gestiona la presentación y, junto con JavaScript, permite una experiencia de usuario fluida y reactiva.

#### Evaluación de herramientas de programación para clientes web
**Herramientas seleccionadas**:

**Visual Studio Code** (VSCode): Elegido por su ligereza, amplia gama de extensiones y soporte para TypeScript. Facilita la depuración, integración con Git y manejo de diferentes entornos de trabajo.

**Postman**: Utilizada para probar y validar las APIs del backend, asegurando que el flujo de datos entre el servidor y el cliente funcione correctamente.

**Git**: Control de versiones indispensable para un desarrollo colaborativo, permitiendo rastrear cambios, gestionar ramas de código y colaborar eficazmente con el equipo.

#### Justificación:

**VSCode** facilita el desarrollo gracias a su integración con linters y debuggers para TypeScript, asegurando un código limpio y optimizado.

**Postman** es clave para la correcta verificación del backend, probando el comportamiento de la API sin necesidad de implementar toda la interfaz de usuario.

**Git** garantiza que todos los desarrolladores puedan trabajar en diferentes partes del proyecto de manera simultánea sin interferencias.

#### Análisis de mercado y propuesta de valor

En el mercado actual, existen aplicaciones líderes como Booksy y Treatwell, que dominan el sector de la gestión de citas en centros de belleza y bienestar. No obstante, la diferenciación de la nueva aplicación propuesta radica en:

**Personalización**: Ofrecer recomendaciones basadas en el historial del cliente y en sus preferencias.

**Simplicidad**: Una experiencia fluida y accesible tanto para clientes como para los centros, con funcionalidades que se pueden activar o desactivar según el tamaño del negocio.

**Sistema de fidelización**: Una característica que no siempre está bien integrada en otras aplicaciones líderes, y que puede aumentar la retención de clientes.





# ENLACES DE FUENTES
JavaScript: https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript
TypeScript: https://www.mytaskpanel.com/lenguaje-de-programacion-typescript/

COMPATIBILIADAD:
https://caniuse.com/
https://v8.dev/
https://webkit.org/
