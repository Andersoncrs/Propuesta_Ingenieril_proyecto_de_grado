# **Plataforma digital para la comercialización directa de excedentes agrícolas**

## Prototipo funcional Desarrollado en Figma
**Enlace al prototipo interactivo:**
[https://www.figma.com/proto/0rkHHLX3ZZT8Ajk2IxbivC/Fase4-ProyectoDeGrado-AndersonRodriguez?node-id=2-6&p=f&t=9fmE5ewGO7LLHWgi-8&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=2%3A6&show-proto-sidebar=1&hide-ui=1](https://www.figma.com/proto/0rkHHLX3ZZT8Ajk2IxbivC/Fase4-ProyectoDeGrado-AndersonRodriguez?node-id=2-6&p=f&t=9fmE5ewGO7LLHWgi-8&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=2%3A6&show-proto-sidebar=1&hide-ui=1)

**Descripción del prototipo:**

El prototipo desarrollado en Figma representa un primer producto mínimo viable centrado en dos tipos de usuarios principales: **Productores** (pequeños agricultores con excedentes) y **Compradores** (tiendas de barrio, restaurantes y consumidores finales). A nivel de interacción y flujo, el prototipo contempla los pasos esenciales desde el registro hasta la venta, pasando por la publicación del producto, la búsqueda, la negociación y la confirmación de la solicitud.

Cada pantalla fue diseñada con criterios de simplicidad, legibilidad y minimización del consumo de datos. Se priorizó una experiencia que sea accesible principalmente a traves de: tipografías legibles, botones grandes, formularios con validación simple y uso moderado de imágenes para no penalizar conexiones lentas. El prototipo incluye pantallas clave como registro, login, formulario de publicación de producto (con fotografías, cantidad, descripción y ubicación), listado de productos con filtros, detalle de producto con galería de imágenes, panel de control del productor con inventario y solicitudes, y un flujo básico de mensajería/ contacto.

Además del aspecto visual, el prototipo incorpora microinteracciones y estados (por ejemplo: carga de imágenes, mensajes de confirmación, formularios incompletos) que permiten simular la experiencia real y facilitar pruebas de usabilidad. Los elementos de navegación están pensados para usuarios con experiencia digital limitada: caminos cortos para las acciones más frecuentes (publicar, responder solicitudes, ver catálogo) y botones que guían al usuario sobre la acción esperada.

---

## Problema que resuelve

En muchas zonas rurales, los pequeños productores agrícolas enfrentan una cadena de comercialización fragmentada. En la práctica, la venta de productos agrícolas suele mediarse por múltiples intermediarios: acopiadores, mayoristas y distribuidores. Cada intermediario reduce el margen del productor y, en muchos casos, condiciona el destino final de la producción. Cuando la demanda local es insuficiente o cuando la logística no está disponible de manera inmediata, parte de la cosecha se convierte en excedente que, sin una salida rápida, se desperdicia. Este problema es especialmente crítico en productos perecederos como frutas, verduras y tubérculos.

El desperdicio postcosecha no solo representa una pérdida económica para el productor sino que también tiene implicaciones sociales y ambientales: desperdicio de recursos (agua, fertilizantes, trabajo humano), pérdida de oportunidades de seguridad alimentaria local y aumento de emisiones por manejo ineficiente. Para compradores locales (tiendas, restaurantes y colegios), la falta de acceso directo a productores significa dependencia de canales más caros o con menor frescura del producto.

La Plataforma Digital propone una solución que aborda este fenómeno facilitando la **conexión directa entre productores y compradores locales**. La plataforma permite publicar excedentes de manera inmediata, mostrar cantidades reales y precios sugeridos, y activar canales de comunicación directa para negociar precios, cantidades y condiciones de entrega. Con esto se logra reducir el tiempo que transcurre entre cosecha y venta, aumentar la probabilidad de que los productos sean comercializados y, en consecuencia, disminuir las pérdidas por deterioro.

Más allá de la reducción del desperdicio, la plataforma genera beneficios colaterales: mejora de la trazabilidad básica del producto (qué se vendió, cuándo y a quién), empoderamiento del productor en la fijación de precios, y la posibilidad de consolidación logística posterior (por ejemplo, cuando varios productores cercanos acuerdan entrega conjunta). Esto fomenta un ecosistema local más resiliente donde la oferta y la demanda se equilibran con menor fricción, y donde la información de mercado es más accesible para actores que tradicionalmente han estado excluidos de canales digitales.

---

## Objetivos del proyecto

**Objetivo general**

Desarrollar una plataforma digital que permita la comercialización directa de excedentes agrícolas de pequeños productores, con la finalidad de mejorar sus ingresos, reducir el desperdicio postcosecha y facilitar cadenas de suministro más eficientes y sostenibles a nivel local.

**Objetivos específicos**

1. Investigar y documentar las barreras actuales de comercialización en la región piloto, recolectando información cualitativa y cuantitativa que permita medir el impacto del piloto.

2. Diseñar y construir un prototipo funcional y un MVP que incluya los módulos básicos necesarios para que productores y compradores interactúen de forma segura y eficiente: registro, publicación de productos, catálogo filtrable, mensajería y panel de control para productores.

3. Validar en campo (prueba piloto) la usabilidad y efectividad del MVP con un grupo controlado de productores y compradores, recopilando métricas que permitan evaluar reducción de desperdicio, incremento de ventas y satisfacción de usuarios.

4. Establecer lineamientos técnicos y operativos para la escalabilidad del sistema: decisiones de arquitectura, seguridad, gestión de datos y requisitos para consolidación logística y métodos de pago.

---

## Alcance y delimitación

El alcance del proyecto está planteado para una fase piloto regional que sirve como prueba de concepto y evidencia de impacto. En esta etapa se trabajará con un número limitado de productores (por ejemplo, una veintena) y compradores locales en una localidad definida para controlar variables y recoger datos representativos. El foco está en productos perecederos con alta probabilidad de generar excedentes: frutas, verduras y tubérculos.

Se delimita desde el inicio que el MVP no resolverá temas complejos de logística nacional ni pagos masivos; sin embargo, sí habilita mecanismos de contacto directo y negociación que permitan a los actores acordar condiciones de entrega (día, punto de recogida, consolidación). El piloto también trabajará en estrategias de capacitación para producir adopción tecnológica: materiales sencillos, demostraciones prácticas y acompañamiento presencial inicial.

---

## Características principales y requerimientos

La propuesta funcional busca responder a las necesidades inmediatas del productor y del comprador. Entre las características más relevantes se encuentran la capacidad de publicar rápidamente lotes disponibles, indicar cantidades y precios sugeridos, y permitir que los compradores busquen por proximidad y categoría. El objetivo es que un productor pueda, con pocos pasos, exponer su excedente y recibir ofertas.

Los requerimientos no funcionales son igualmente críticos: la aplicación debe ser ligera en consumo de datos, tolerante a conexiones intermitentes (capacidad de trabajo offline parcial con sincronización posterior), y con una interfaz comprensible para personas con experiencias digitales limitadas. La seguridad de la información y la privacidad deben ser tratadas con prioridad: manejo responsable de credenciales, cifrado de contraseñas y claridad en el uso de datos personales del usuario.

---

## Diseño técnico y stack tecnológico

Para el MVP se recomienda una arquitectura de tipo cliente–servidor con una API RESTful que sirva los datos a una aplicación móvil. A nivel de cliente, el uso de frameworks multiplataforma acelera el desarrollo y facilita el mantenimiento de la interfaz en dispositivos Android e iOS si se decide escalar. En el backend, para un lanzamiento rápido, se consideran soluciones gestionadas como Firebase (Autenticación y Firestore) que permiten prototipar con rapidez y manejar la sincronización offline de forma nativa.

Para la mensajería y la comunicación entre usuario y usuario se pueden contemplar dos alternativas: integración con canales externos (por ejemplo, enlaces directos a WhatsApp para comunicación inmediata) o implementar un chat interno que permita mantener historial dentro de la plataforma. La primera opción acelera adopción por su familiaridad; la segunda ofrece mayor control de datos y mejor experiencia integrada en el largo plazo.

---

## Metodología de desarrollo: SCRUM (ampliado)

El desarrollo de la plataforma digital se llevó a cabo utilizando la metodología ágil **SCRUM**, una elección que responde directamente a la naturaleza dinámica del proyecto, la necesidad de validación continua en entornos reales y la importancia de incorporar retroalimentación temprana de los usuarios finales. En contextos rurales, donde los procesos son altamente variables, las necesidades pueden cambiar de una semana a otra y los actores involucrados presentan distintos niveles de alfabetización digital, es fundamental contar con un método flexible, incremental y adaptable.

SCRUM permite dividir el desarrollo en ciclos cortos llamados *sprints*, los cuales facilitan la entrega gradual de funcionalidades utilizables. Esto genera múltiples beneficios: por un lado, se pueden realizar pruebas frecuentes en campo para validar hipótesis de diseño y usabilidad; por otro, es posible ajustar la planificación conforme surgen nuevos requerimientos o se identifican oportunidades de mejora. En proyectos sociales o de tecnología para el sector agrícola, esta capacidad de adaptación es especialmente importante, pues la realidad del productor puede diferir considerablemente de los supuestos iniciales.

Uno de los motivos clave para utilizar SCRUM es su énfasis en la **colaboración continua con stakeholders**, lo que resulta esencial en un sistema que involucra actores con intereses diversos, como productores, compradores, instituciones locales y equipo técnico. A través de *Sprint Planning*, *Daily Meeting*, *Sprint Review* y *Sprint Retrospective* se mantiene una comunicación fluida que permite tomar decisiones oportunas y alinear prioridades según el impacto esperado.

En este proyecto, SCRUM ha sido muy útil para abordar desafíos de adopción tecnológica: cambios en flujos de usuario, simplificación de formularios, ajustes en tiempos de carga y mejoras en accesibilidad han podido incorporarse rápidamente al backlog e implementarse en sprints sucesivos, evitando así que los problemas se acumulen o que el producto final esté desconectado de las necesidades reales.

Dentro del proceso, se inició con un **Sprint 0**, donde se definió el Product Backlog, se identificaron los actores involucrados, se establecieron criterios de aceptación y se organizaron las funcionalidades según prioridad. Posteriormente, se avanzó hacia una etapa de diseño y prototipado donde se construyeron wireframes y el prototipo completo en Figma. Esa fase permitió iterar visualmente antes de escribir una sola línea de código, lo cual redujo costos y permitió validar conceptos clave como navegación, carga de datos y estructura del catálogo.

A continuación, se ejecutaron varios **sprints de desarrollo incremental**, en los cuales se construyeron las primeras versiones de las funciones esenciales del MVP: registro, autenticación, publicación de productos, listado y filtrado, contacto entre usuarios y panel de control para productores. Cada sprint culminó con una revisión formal, en la que se recibieron comentarios tanto de usuarios potenciales como de actores clave del proyecto.

Las **pruebas de usabilidad en campo** constituyeron un elemento central del proceso SCRUM aplicado. Estas pruebas no solo permitieron identificar problemas de flujo o comprensión, sino que también revelaron oportunidades de mejora relacionadas con la experiencia del usuario, como simplificar la captura de imágenes, reducir pasos innecesarios en la publicación de un producto o hacer más visibles las notificaciones.

Finalmente, la metodología permitió planificar un **despliegue piloto acompañado de monitoreo continuo**, facilitando la incorporación de mejoras sobre la marcha. Este ciclo iterativo promovido por SCRUM garantiza que la plataforma digital evolucione de manera orgánica y orientada al usuario, permitiendo que la plataforma crezca de acuerdo con las necesidades reales del entorno agrícola al que está dirigida.

---

## Imágenes del prototipo

Estas imágenes permitirán visualizar con mayor claridad la estructura, el flujo de interacción y las pantallas principales que conforman la experiencia de usuario del sistema plataforma Digital.

![Pantalla inicio](https://raw.githubusercontent.com/Andersoncrs/Propuesta_Ingenieril_proyecto_de_grado/refs/heads/main/landing_page.png)

![Pantalla registro](https://raw.githubusercontent.com/Andersoncrs/Propuesta_Ingenieril_proyecto_de_grado/refs/heads/main/registro.png)

![Pantalla login](https://raw.githubusercontent.com/Andersoncrs/Propuesta_Ingenieril_proyecto_de_grado/refs/heads/main/login.png)

![Pantalla Home](https://raw.githubusercontent.com/Andersoncrs/Propuesta_Ingenieril_proyecto_de_grado/refs/heads/main/home.png)

---

## Agradecimiento

Muchas gracias por su atención e interés en la plataforma digital. Espero que este proyecto sea una herramienta útil para fortalecer la comercialización agrícola local, reducir el desperdicio de alimentos y mejorar las oportunidades económicas de comunidades rurales. Cualquier sugerencia, aporte o retroalimentación será recibido con gratitud para seguir evolucionando la plataforma y su impacto social.

