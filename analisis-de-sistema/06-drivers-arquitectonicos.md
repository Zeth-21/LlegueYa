# 06 - Drivers arquitectónicos

| ID | Driver arquitectónico | Origen | ¿Por qué influye en la arquitectura? |
|---|---|---|---|
| DA01 | El sistema debe soportar el aumento de visitas en festividades. | AC02 - Disponibilidad, AC03 - Escalabilidad | Influye en la estrategia de escalamiento, balanceo de carga y despliegue. |
| DA02 | La plataforma debe cargar rápido fotos, galerías y libros. | AC01 - Rendimiento, RF08, RF09, RF11 | Influye en el almacenamiento de archivos, la caché y la distribución de contenido estático. |
| DA03 | El sistema solo guía a sitios de venta verificados y no gestiona pagos. | RC05, RC06, AC04 - Seguridad | Influye en el modelo de sitios y puntos de venta, y elimina la necesidad de una pasarela de pagos. |
| DA04 | Solo deben ofrecerse proveedores con documentación verificada. | RC07, AC05 - Confiabilidad de la información | Influye en el modelo de datos de proveedores y en el flujo de verificación. |
| DA05 | El sistema debe integrarse con un servicio de mapas externo. | RC04 - Servicio de mapas | Condiciona la forma de comunicación e integración con servicios externos. |
| DA06 | El chatbot debe responder con un modelo de lenguaje apoyado en una base de conocimiento propia. | RC08 - Modelo de lenguaje, RF14 a RF16 | Influye en la integración con el servicio de IA y en el almacenamiento de la base de conocimiento. |
| DA07 | Se debe notificar a los usuarios cuando se publique nuevo contenido. | RF12, RC09 | Influye en la comunicación entre el módulo de contenido, el de notificaciones y el servicio de correo. |
| DA08 | Los comentarios y fotos de usuarios deben revisarse antes de mantenerse visibles. | RF21, AC04 - Seguridad, AC05 | Influye en el flujo de moderación y en el modelo de datos del contenido de usuarios. |
| DA09 | La comunicación entre frontend y backend debe usar una API REST. | RC03 - API REST | Limita las alternativas de comunicación entre las partes del sistema. |
