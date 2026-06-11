# Epica: Personal Portfolio Website

## Descripcion
Como desarrollador full stack con conocimiento de AI, quiero tener mi propio sitio web profesional, para mostrar mis proyectos, facilitar contacto por oportunidades laborales y compartir mi CV.

## Objetivo
Crear un sitio personal en ingles, SEO-friendly y orientado a oportunidades laborales, que comunique de forma clara la experiencia full stack, los proyectos destacados, el uso de AI y la capacidad de construir, desplegar y operar productos end-to-end.

## Alcance general
**Incluye:**
- Home profesional en ingles con posicionamiento claro como full stack developer con experiencia en AI.
- Seccion de proyectos destacados para Prode, ai-digest y Gerardo.
- Descripcion de cada proyecto, URL si existe, repositorio si existe o aclaracion de repositorio privado, y tecnologias usadas.
- Acceso visible al CV.
- Mecanismo de contacto orientado a ofertas laborales.
- Animacion inicial local y liviana que represente el perfil AI/full stack y los proyectos destacados.
- Mencion de experiencia operacional, incluyendo manejo de VPS en Hetzner.
- Consideraciones funcionales de SEO para contenido, metadata y estructura publica del sitio.

**No incluye:**
- Panel de administracion para editar proyectos desde el sitio.
- Blog o sistema de articulos.
- Analytics avanzado o dashboard interno.
- Autenticacion de usuarios.
- Contenido multilenguaje.
- Integracion automatica con APIs de LinkedIn, GitHub u otros servicios externos.

## Historias de Usuario
| # | Historia | Spec | Estado |
|---|----------|------|--------|
| 1 | Como visitante reclutador, quiero ver una home clara y SEO-friendly en ingles, para entender rapidamente el perfil profesional de Lucas como full stack developer con experiencia en AI. | [home-seo-friendly-profile](./home-seo-friendly-profile.md) | Especificada |
| 2 | Como visitante reclutador, quiero explorar los proyectos destacados de Lucas, para evaluar experiencia practica, tecnologias usadas, URLs, repositorios y contexto de cada proyecto. | [featured-projects-showcase](./featured-projects-showcase.md) | Especificada |
| 3 | Como visitante reclutador, quiero acceder al CV de Lucas, para revisar su experiencia profesional, habilidades y antecedentes en formato claro y compartible. | [cv-access](./cv-access.md) | Especificada |
| 4 | Como visitante reclutador, quiero contactar a Lucas desde el sitio, para iniciar una conversacion por una oportunidad laboral. | [job-opportunity-contact](./job-opportunity-contact.md) | Especificada |
| 5 | Como visitante, quiero ver una animacion inicial local y liviana que represente los proyectos y perfil AI/full stack, para que el sitio tenga una primera impresion memorable sin afectar SEO ni performance. | [initial-ai-animation](./initial-ai-animation.md) | Especificada |
| 6 | Como visitante tecnico, quiero ver senales de experiencia operacional como manejo de VPS en Hetzner, para entender que Lucas puede construir, desplegar y mantener proyectos end-to-end. | [operational-experience-hetzner](./operational-experience-hetzner.md) | Especificada |

## Dependencias entre historias
- La historia 2 depende de la historia 1 para mantener consistencia narrativa y SEO.
- La historia 3 depende de la historia 1 para definir ubicacion y jerarquia del acceso al CV.
- La historia 4 depende de la historia 1 para definir CTA principal y tono profesional.
- La historia 5 depende de las historias 1 y 2 para representar correctamente el perfil y los proyectos.
- La historia 6 depende de las historias 1 y 2 para integrarse como evidencia tecnica dentro del posicionamiento general.
