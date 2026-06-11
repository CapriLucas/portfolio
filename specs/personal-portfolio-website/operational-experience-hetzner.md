# Operational Experience Hetzner

## User Story
Como visitante tecnico, quiero ver senales de experiencia operacional como manejo de VPS en Hetzner, para entender que Lucas puede construir, desplegar y mantener proyectos end-to-end.

## Objetivo
Comunicar que Lucas no solo desarrolla aplicaciones, sino que tambien entiende despliegue, operacion, servidores, configuracion de servicios y mantenimiento basico de productos en produccion o entornos similares.

## Alcance
**Incluye:**
- Mencion visible de experiencia operacional end-to-end.
- Referencia explicita al manejo de VPS en Hetzner.
- Contexto profesional sobre despliegue, configuracion, monitoreo basico, backups o mantenimiento cuando aplique.
- Conexion entre experiencia operacional y proyectos reales.
- Redaccion en ingles, clara y sin exagerar seniority ni alcance.

**No incluye:**
- Publicacion de IPs, credenciales, nombres internos de servidores o configuraciones sensibles.
- Runbooks operativos completos.
- Dashboard de infraestructura.
- Promesas de SRE avanzado si no corresponden.
- Detalles que comprometan seguridad de proyectos o servidores.

## Actores
- Visitante tecnico: Persona que evalua capacidad tecnica end-to-end.
- Visitante reclutador: Persona que busca senales de autonomia y ownership tecnico.
- Lucas: Profesional que quiere comunicar experiencia operacional sin exponer informacion sensible.

## Precondiciones
- La home y proyectos ya comunican experiencia full stack.
- Existe experiencia real de manejo de VPS en Hetzner.
- Lucas define que detalles operativos son publicables.

## Disparador
El visitante revisa la home, proyectos, skills o una seccion de experiencia tecnica.

## Flujo Principal
1. El visitante encuentra una referencia a experiencia operacional.
2. El sitio menciona manejo de VPS en Hetzner de forma clara y profesional.
3. El sitio explica que esa experiencia se relaciona con despliegue, configuracion y mantenimiento de proyectos.
4. El visitante entiende que Lucas puede trabajar mas alla del codigo de aplicacion.
5. El sitio evita publicar detalles sensibles de infraestructura.

## Flujos Alternativos
### FA-1: Visitante revisa un proyecto con experiencia operacional asociada
1. El visitante abre un proyecto destacado.
2. El sitio muestra senales de despliegue u operacion cuando corresponda.
3. El visitante relaciona el proyecto con capacidad end-to-end.

### FA-2: Visitante busca habilidades tecnicas generales
1. El visitante revisa la seccion de skills o perfil.
2. El sitio incluye VPS, deploy y operacion junto a full stack y AI.
3. El visitante identifica autonomia tecnica en construccion y mantenimiento.

### FA-3: Detalles sensibles no publicables
1. El visitante intenta inferir detalles de infraestructura.
2. El sitio solo muestra informacion profesional de alto nivel.
3. No se exponen datos internos, secretos ni configuraciones riesgosas.

## Reglas de Negocio
- RN-1: El contenido visible debe estar escrito en ingles.
- RN-2: Debe mencionarse explicitamente experiencia con Hetzner VPS.
- RN-3: La experiencia operacional debe presentarse como parte de la capacidad end-to-end de Lucas.
- RN-4: El sitio no debe exponer IPs, credenciales, nombres internos de servidores ni configuraciones sensibles.
- RN-5: Las afirmaciones deben ser concretas y creibles, evitando exageraciones.
- RN-6: La experiencia operacional debe conectarse con proyectos, deploys o mantenimiento cuando corresponda.
- RN-7: La comunicacion debe ser comprensible tanto para reclutadores como para visitantes tecnicos.

## Criterios de Aceptacion
- CA-1: Dado un visitante tecnico, cuando revisa el sitio, entonces encuentra una mencion clara a experiencia con Hetzner VPS.
- CA-2: Dado un reclutador, cuando lee el perfil tecnico, entonces entiende que Lucas puede construir, desplegar y mantener productos end-to-end.
- CA-3: Dado un visitante que revisa proyectos, cuando hay experiencia operacional asociada, entonces el sitio la presenta como evidencia de ownership tecnico.
- CA-4: Dado cualquier visitante, cuando lee la informacion operacional, entonces no encuentra datos sensibles de infraestructura.
- CA-5: Dado un visitante no tecnico, cuando lee la mencion operacional, entonces puede entender el valor profesional sin necesitar conocimiento profundo de infraestructura.
- CA-6: Dado cualquier visitante, cuando lee esta informacion, entonces todo el contenido visible esta en ingles.

## Resultado Esperado
El sitio comunica de forma creible que Lucas tiene experiencia end-to-end: desarrollo, AI, producto, despliegue y operacion basica de infraestructura, incluyendo manejo de VPS en Hetzner.

## Definicion BDD/Gherkin
```gherkin
Feature: Operational experience with Hetzner VPS

  Scenario: Technical visitor finds Hetzner VPS experience
    Given a technical visitor reviews the site
    When they look for operational experience
    Then they find a clear mention of Hetzner VPS experience

  Scenario: Recruiter understands end-to-end ownership
    Given a recruiter reads Lucas' technical profile
    When operational experience is presented
    Then they understand Lucas can build, deploy, and maintain products end-to-end

  Scenario: Project includes operational evidence
    Given a visitor reviews a project with operational work
    When the project details are displayed
    Then the site presents that work as evidence of technical ownership

  Scenario: Sensitive infrastructure details remain private
    Given any visitor reads operational information
    When the content is displayed
    Then no sensitive infrastructure data is exposed

  Scenario: Non-technical visitor understands the value
    Given a non-technical visitor reads the operational section
    When they see VPS and deployment references
    Then they understand the professional value without deep infrastructure knowledge

  Scenario: Operational content is only in English
    Given any visitor reads operational information
    When visible text is displayed
    Then all visible operational content is written in English
```
