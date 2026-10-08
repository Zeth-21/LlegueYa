# LlegueYa
Sistema inteligente de guía turística y viaje seguro al patrimonio arqueológico y cultural de Ayacucho.

## Integrantes
- LLALLAHUI GOMEZ, Cristian Mier - 27222118
- ATAO HUAMAN, Yordi Ajeo - 27222121

## Descripción
Plataforma web de guía turística para los sitios arqueológicos de Ayacucho (Wari, Vilcashuamán, Intihuatana/Pumacocha, Quinua y otros). LlegueYa **no vende entradas**: guía al turista hacia el sitio de venta (presencial o virtual) mediante su ubicación en el mapa. Además ofrece proveedores con documentación verificada (hospedaje, restaurantes, transporte) con puntuación y comentarios, fotos de experiencias, historias y fotografías de personas, libros turísticos con notificaciones y un chatbot web que recomienda según el presupuesto y el mejor mes para viajar.

## Caso de estudio
LlegueYa: propuesta de plataforma de turismo seguro para Ayacucho (documento `llegueYa_ARQUITECTURA.pdf`), ajustada para guiar a los sitios de venta en lugar de vender boletos.

## Curso
Arquitectura de Software (IS-488) - Escuela Profesional de Ingeniería de Sistemas, UNSCH.
Docente: Ing. Lizbeth Jaico Quispe - Semestre 2026-II.

## Alcance
Incluye: sitios con ubicación en mapa y enlace al sitio de venta, proveedores verificados, puntuación y comentarios, fotos de experiencias, historias, fotografías y libros con notificaciones, paquetes y chatbot web.
No incluye: venta o cobro de entradas, pasarela de pagos, QR de boletos, control de aforo, ni chatbot por WhatsApp o Telegram.

## Entregables
| Guía | Entregable | Archivo |
|---|---|---|
| 02 | Actores, historias de usuario, requisitos funcionales, atributos de calidad, restricciones y drivers | `analisis-de-sistema/01` a `06` |
| 02 | Arquitectura inicial en 3 capas | `arquitectura/arquitectura-inicial.*` |
| 03 | 1. Necesidad del negocio | `analisis-de-sistema/00-necesidad-del-negocio.md` |
| 03 | 4. Drivers arquitectónicos (con DA10 y DA11) | `analisis-de-sistema/06-drivers-arquitectonicos.md` |
| 03 | 5. Decisiones arquitectónicas (ADR) | `arquitectura/decisiones-arquitectonicas.md` |
| 03 | 6. Estilo arquitectónico | `arquitectura/estilo-arquitectonico.*` |
| 03 | Enfoque: Clean Architecture | `arquitectura/enfoque/enfoque-arquitectonico.*` |

## Estructura del repositorio
```
LlegueYa-arquitSoft-02
├── analisis-de-sistema
│   ├── 00-necesidad-del-negocio.md
│   ├── 01-actores.md
│   ├── 02-historias-de-usuario.md
│   ├── 03-requisitos-funcionales.md
│   ├── 04-atributos-de-calidad.md
│   ├── 05-restricciones.md
│   └── 06-drivers-arquitectonicos.md
├── arquitectura
│   ├── arquitectura-inicial.md / .drawio / .html
│   ├── decisiones-arquitectonicas.md
│   ├── estilo-arquitectonico.md / .drawio / .html
│   └── enfoque
│       └── enfoque-arquitectonico.md / .drawio / .html
├── .gitignore
└── README.md
```
