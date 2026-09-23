# Gestor para restaurantes

<br>

## *1. Definición del proyecto:*

El proyecto consiste en desarrollar una aplicación web integral diseñada para digitalizar la operativa de un restaurante conectando a clientes (desde sus casas o desde el local), y trabajadores del negocio en tiempo real. La plataforma permite a los usuarios tramitar pedidos en mesa o a domicilio siguiendo su estado en vivo, mientras los cocineros gestionan las comandas entrantes cambiando su estado y los camareros controlan las mesas y cuentas del local. Asimismo, el administrador dispone de un panel centralizado para gestionar la carta, los precios y la disponibilidad de los platos de forma ágil.

<hr>

<br>

## *2. ¿Qué es MERN?:*

Se trata de un `stack` o conjunto de tecnologías de desarrollo web basado en JavaScript y orientado en la construcción de aplicaciones modulares y escalables. Su principal ventaja es la unificación del lenguaje a través del empleo de JavaScript en entorno cliente, servidor y base de datos, empleando JSON como formato para el intercambio de información. Sus siglas significan: 

**M** – MongoDB: Base de datos NoSQL orientada a documentos, ideal para manejar información flexible. A diferencia de las bases de datos relacionales tradicionales, prescinde de tablas rígidas con esquemas fijos, lo que permite guardar objetos anidados y colecciones dinámicas.

**E** – Express.js: Framework ligero para Node.js que facilita crear la API REST abstrayendo la complejidad nativa de la gestión de peticiones HTTP, es decir, mejora la construcción de la parte encargada de gestionar rutas, peticiones, validación de roles mediante tokens, control de errores y lógica de negocio. 

**R** – React.js: Librería de JavaScript enfocada en la construcción de interfaces de usuario dinámicas y reactivas basadas en el diseño de una sola página (SPA - Singe Page Applications). Se caracteriza por una estructura basada en componentes reutilizables e independientes y la existencia de un Virtual DOM (representación del DOM real), que permite actualizar únicamente las partes que han sufrido cambios.

**N** – Node.js: Entorno de ejecución de JavaScript en el servidor. Su arquitectura está basada en eventos (event-driven) y cuenta con un modelo de entrada/salida no bloqueante o asíncrona, lo que permite procesar miles de conexiones concurrentes de manera eficiente sin sobrecargar recursos con hilos pesados.

<hr>

<br>

## *3. Justificación de MERN en el proyecto:*

`MongoDB (M).`  Su estructura documental permite almacenar pedidos completos como objetos anidados que incluyen notas específicas para cocina (por ejemplo, "hamburguesa al punto sin gluten" o suplementos) y listas dinámicas de alérgenos en los platos de la carta, evitando la sobrecarga de consultas y tablas intermedias propias de SQL.

`Express.js (E).` Principalmente por la facilidad que ofrece para la creación de la API REST y el uso de middlewares que permitan blindar las rutas según el rol del usuario, algo fundamental en un proyecto con cuatro perfiles: cliente, camarero, cocinero y admin.

`React.js (R).` Permite diseñar interfaces reactivas y modulares mediante componentes, logrando que el panel de cocina (KDS) actualice al instante las tarjetas de las comandas pasando visualmente de "En preparación" a "Listo para servir" mediante su Virtual DOM sin recargar la página.

`Node.js (N).`  Su modelo de eventos asíncrono y no bloqueante soporta los picos de concurrencia en las horas punta del restaurante, respondiendo con fluidez mientras decenas de comensales consultan la carta, los camareros comandan en sala y cocina actualiza los estados simultáneamente.

<hr>

<br>

## *4. Evidencias del uso de Toggl Track:*

- Captura para mostrar Toggl Track implementado en una tarea:

  ![Tracker funcionando en github]()
  

- PDF generado por la aplicación: 
  - Summary:
 [Reporte resumen]()
  - Detailed:
  [Reporte detallado]()


