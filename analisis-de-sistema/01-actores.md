# 01 - Actores

## Contexto del negocio
LlegueYa es una plataforma digital de guía turística para los sitios arqueológicos de Ayacucho. No vende entradas: ubica al turista en el mapa y lo dirige al sitio de venta (presencial o virtual). También reúne proveedores verificados con puntuación y comentarios, fotos de experiencias, historias, fotografías y libros turísticos, y un chatbot web.

## Actores humanos

| Actor | ¿Qué necesita realizar? |
|---|---|
| Turista | Consultar sitios y su acceso, ubicar en el mapa y acceder al sitio de venta de entradas, consultar proveedores verificados, puntuar y comentar servicios, publicar y ver fotos de experiencias, leer historias y ver fotografías, consultar libros turísticos, recibir notificaciones, ver paquetes y consultar al chatbot. Puede ser nacional o extranjero. |
| Proveedor (hospedaje, restaurante, transportista) | Registrar su oferta y sus documentos (licencia de funcionamiento, RUC habido, registro o permiso vigente). |
| Administrador | Verificar los documentos de los proveedores, registrar sitios y sus puntos y enlaces de venta, publicar historias, fotografías y libros, y moderar reseñas y fotos. |

## Sistemas externos

| Sistema externo | ¿Qué necesita realizar? |
|---|---|
| Servicio de mapas | Mostrar la ubicación de sitios, puntos de venta y proveedores. |
| Sitios de venta de entradas (presencial o virtual) | Vender las entradas; LlegueYa solo redirige hacia ellos. |
| Servicio de IA (modelo de lenguaje) | Generar las respuestas del chatbot apoyándose en la base de conocimiento de LlegueYa. |
| Servicio de correo | Enviar las notificaciones a los usuarios. |

## Notas
- El **Proveedor** y el **Administrador** se derivan de la verificación de documentos de hospedajes, restaurantes y transportistas (secciones 3 y 4.3 del documento).
- Se retiraron respecto a la versión anterior: operador/agencia (reserva de cupos), personal de control de acceso, pasarela de pagos y DDC/Municipalidades (reportes de aforo), porque ya no se venden ni validan boletos.
- Se asume que las historias, fotografías y libros los publica el Administrador (por confirmar).
- Se asume el correo como canal de notificación (por confirmar). Quedan fuera WhatsApp y Telegram.
