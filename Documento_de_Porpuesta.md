# Documento de propuesta

### 1. IDEA DE LA APLICACIÓN
La aplicación será una plataforma de gestión de citas y servicios para centros de peluquería y estética y centros de belleza. Permitirá reservar citas, obtener recomendaciones, consultar servicios y realizar pagos.
Para los negocios será una herramienta de gestión para organizar citas y gestionar la relación con los clientes.

### 2. AUDIENCIA OBJETIVO
La aplicación está dirigida a:
- **Centros de peluqería y estética y centros de belleza**: que necesitan una solución para gestionar sus citas y controlar la disponibilidad de su personal.
- **Clientes de estos centros**: que buscan una maera mas sencilla y rápida para agendar sus citas e informarse sobre estos centros.
- **Freelancers del sector de belleza**: como peluqueros y esteticistas independientes que necesitan gestionar sus citas y tener una comunicación directa con sus clientes. 

Así todos se benefician evitando largas esperas o llamdas telefónicas.

### 3. ANÁLISIS DE MERCADO

#### Aplicaciones similares:
- **Booksy**: Permite a los usuarios reservar citas online para servicios de belleza y bienestar. Su principal ventaja es la integración de pagos y su accesible interfaz.
- **Treatwell**: Plataforma de reservas online. También permite gestionar pagos, ver opiniones y localizar centros cercanos.

#### Opciones de diferenciación:
- **Sistema de fidelación**: se podría implementar un sistema de puntos o recompensas para clientes recurrentes que ofrezca descuentos o similares.
- **Análisis de clientes**: usar datos para sugerir servicios o productos según citas pasadas y preferencias del cliente.
- **Mejorar la experiencia del cliente**: ofrecer una interfaz muy intuitiva, que facilite la búsqueda y reserva.

### 4. FUNCIONALIDADES CLAVE
- **Reserva en línea**: los usuarios pueden elegir servicios y seleccionar profesionales.
- **Gestión de clientes**: el sistema llevará un registro de clientes, historial, preferencias y recordatorios.
- **Calendario interactivo**: los profesionales podrán gestionar su disponibilidad.
- **Pagos online**: aceptará múltiples formas de pago.
- **Sistema de fidelización**: los clientes podrán acumular puntos o recibir descuentos.
- **Reseñas y recomendaciones**: los usuarios podrán calificar y dejar comentarios.

### 5. TECNOLOGÍAS SELECCIONADAS PARA EL DESARROLLO Y JUSTIFICACIÓN
### Frontend: 

**React con TypeScript**: Tiene una mejor legibilidad y mantenibilidad, tiene una fácil refactorización y pocos errores indefinidos. También ha sido seleccionada porque React es compatible por defecto con TypeScript en librerias comunes.

### Backend: 

**Node.js con Express**: Utilizando JavaScript en el servidor, habrá mayor compatibilidad entre frontend y backend usando Node.js con Express. Ya que Node.js es eficaz con tareas asíncronas y procesando múltiples peticiones. Node también es muy escalable.

### Base de datos:
**PostgreSQL**: Elegida por su capacidad de manejar relaciones entre clientes, servicios y citas, garantizando escalabilidad y consistencia.

### Sistema de pagos:
**Stripe o Paypal**: Estas con soluciones seguras y ampliamente utilizadas


# APARTADO RECURSOS (NO ESTA ORDENADO NI FINALIZADO)

React y TypeScript: https://vanessamarely.medium.com/qu%C3%A9-ventajas-tengo-al-usar-typescript-en-react-b5f1d6431bb0
Node.js con Express: https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction
PostgreSQL: https://www.todopostgresql.com/ventajas-y-desventajas-de-postgresql/
