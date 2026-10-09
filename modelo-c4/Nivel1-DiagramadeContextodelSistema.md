
# Nivel 1 - Diagrama de contexto del sistema

## Objetivo

Mostrar a LlegueYa como un sistema único y sus relaciones con las personas y sistemas externos que lo rodean. El sistema no vende entradas ni procesa pagos: únicamente presenta puntos de venta verificados y redirige al turista.

```mermaid
flowchart LR
	Turista["Turista\nConsulta sitios, proveedores, contenido y paquetes; usa el mapa y el chatbot"]
	Proveedor["Proveedor\nRegistra su oferta y carga documentos"]
	Admin["Administrador\nVerifica proveedores, gestiona sitios y contenido, modera publicaciones"]

	LlegueYa[["LlegueYa\nPlataforma web de guía turística segura para Ayacucho"]]

	Mapas["Servicio de mapas\nMapas, ubicaciones y rutas"]
	Venta["Sitios de venta de entradas\nVenta presencial o virtual"]
	IA["Servicio de IA\nModelo de lenguaje para el chatbot"]
	Correo["Servicio de correo\nEntrega de notificaciones"]

	Turista -->|Consulta información y recibe recomendaciones| LlegueYa
	Proveedor -->|Registra oferta y documentos| LlegueYa
	Admin -->|Administra y modera información| LlegueYa

	LlegueYa -->|Solicita mapas y ubicaciones| Mapas
	LlegueYa -->|Redirige mediante enlaces verificados| Venta
	LlegueYa -->|Envía contexto turístico y consulta| IA
	LlegueYa -->|Solicita envío de notificaciones| Correo
```

## Descripción de las relaciones

| Elemento | Relación con LlegueYa |
|---|---|
| Turista | Consulta sitios arqueológicos, accesos, proveedores verificados, reseñas, fotos, historias, libros y paquetes. También puede iniciar sesión, publicar contenido y usar el chatbot. |
| Proveedor | Registra hospedajes, restaurantes o servicios de transporte y carga la documentación necesaria para ser verificado. |
| Administrador | Verifica o suspende proveedores, registra sitios y puntos de venta, gestiona contenido turístico y modera reseñas y fotos. |
| Servicio de mapas | Proporciona mapas y ubicación de sitios, puntos de venta y proveedores. |
| Sitios de venta de entradas | Reciben al turista mediante un enlace presencial o virtual previamente registrado y verificado. LlegueYa no cobra entradas. |
| Servicio de IA | Genera respuestas del chatbot usando la base de conocimiento turística de LlegueYa. |
| Servicio de correo | Envía avisos cuando se publica nuevo contenido turístico. |

## Alcance y límites

- **Dentro de LlegueYa:** guía turística, proveedores verificados, reseñas, fotos de experiencias, contenido cultural, paquetes, chatbot web y notificaciones.
- **Fuera de LlegueYa:** cobro de entradas, pasarela de pagos, emisión de boletos, control de aforo y chatbot por WhatsApp o Telegram.

## Trazabilidad

Este nivel refleja RF01-RF21, RC04-RC10, HU01-HU19 y ADR-006/ADR-009.
