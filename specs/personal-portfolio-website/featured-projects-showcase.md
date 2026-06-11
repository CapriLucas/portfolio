# Featured Projects Showcase

## User Story
Como visitante reclutador, quiero explorar los proyectos destacados de Lucas, para evaluar experiencia practica, tecnologias usadas, URLs, repositorios y contexto de cada proyecto.

## Objetivo
Mostrar proyectos reales de Lucas de forma clara, indexable y orientada a evaluacion profesional, destacando problema resuelto, rol de Lucas, capacidades full stack, uso de AI cuando corresponda, tecnologias utilizadas, URL publica si existe y estado del repositorio.

## Alcance
**Incluye:**
- Seccion o pagina de proyectos destacados en ingles.
- Tres proyectos iniciales: Prode, AI Digest y Gerardo.
- Para cada proyecto: nombre, descripcion breve, problema abordado, rol de Lucas, tecnologias usadas, URL publica si existe, repositorio si es publicable o aclaracion de repositorio privado.
- Senales de impacto o aprendizaje tecnico para cada proyecto.
- Diferenciacion entre proyectos activos, prototipos, herramientas personales o productos privados cuando aplique.
- Contenido indexable para SEO.

**No incluye:**
- Panel de administracion para cargar o editar proyectos.
- Importacion automatica desde GitHub.
- Screenshots obligatorios para cada proyecto.
- Publicacion de informacion sensible, credenciales, datos privados o detalles operativos internos.
- Metricas inventadas de usuarios, ingresos o trafico.

## Actores
- Visitante reclutador: Persona que revisa proyectos para evaluar experiencia, criterio tecnico y capacidad de entrega.
- Visitante tecnico: Persona que quiere entender arquitectura, tecnologias y decisiones de producto.
- Lucas: Propietario del sitio y autor de los proyectos destacados.

## Precondiciones
- La home ya presenta el perfil profesional de Lucas.
- Existen al menos tres proyectos destacados definidos.
- Lucas puede decidir que URLs y repositorios son publicables.

## Disparador
El visitante selecciona el acceso a proyectos desde la home, navegacion principal, resultado de busqueda o enlace directo.

## Flujo Principal
1. El visitante accede a la seccion de proyectos.
2. El sitio muestra una lista de proyectos destacados en ingles.
3. Cada proyecto presenta nombre, descripcion, contexto, tecnologias y rol de Lucas.
4. El visitante identifica si el proyecto tiene URL publica, repositorio publico o repositorio privado.
5. El visitante puede abrir la URL publica cuando exista.
6. El visitante puede abrir el repositorio cuando sea publicable.
7. El visitante comprende que capacidades demuestra cada proyecto.

## Flujos Alternativos
### FA-1: Proyecto sin URL publica
1. El visitante revisa un proyecto que no tiene URL publica.
2. El sitio muestra una aclaracion clara como "No public URL available" o equivalente en ingles.
3. El visitante puede igualmente entender el valor del proyecto mediante descripcion, tecnologias y rol.

### FA-2: Proyecto con repositorio privado
1. El visitante revisa un proyecto cuyo repositorio no es publicable.
2. El sitio muestra una aclaracion clara como "Private repository" o equivalente en ingles.
3. El sitio no expone enlaces rotos ni URLs internas.

### FA-3: Visitante busca evidencia tecnica
1. El visitante revisa tecnologias y contexto de cada proyecto.
2. El sitio muestra detalles suficientes para entender alcance, arquitectura general y responsabilidades.
3. El visitante puede relacionar los proyectos con experiencia full stack, AI u operacion segun corresponda.

## Reglas de Negocio
- RN-1: Todo el contenido visible de proyectos debe estar escrito en ingles.
- RN-2: Deben mostrarse inicialmente Prode, AI Digest y Gerardo.
- RN-3: Cada proyecto debe incluir descripcion breve, tecnologias usadas, URL si existe y repositorio si es publicable.
- RN-4: Si el repositorio no debe publicarse, el sitio debe indicarlo como repositorio privado.
- RN-5: Si una URL publica no existe o no debe compartirse, el sitio debe aclararlo sin mostrar enlaces rotos.
- RN-6: La descripcion de cada proyecto debe enfocarse en problema, solucion y capacidades demostradas.
- RN-7: La informacion publicada no debe incluir secretos, datos sensibles ni detalles privados de usuarios o cuentas.
- RN-8: Prode debe presentarse como una herramienta para predicciones del Mundial 2026 basada en partidos, probabilidades, odds y optimizacion de puntaje de prode.
- RN-9: AI Digest debe presentarse como un sistema personal de digests de noticias con fuentes configurables, deduplicacion, modelos de AI y entrega por email.
- RN-10: Gerardo debe presentarse como una plataforma personal de automatizacion financiera con bot, dashboard, DCA, reconciliacion, alertas y operacion programada.
- RN-11: Las tecnologias iniciales a mostrar deben basarse en evidencia real del proyecto y no en aspiraciones futuras.
- RN-12: Prode debe listar inicialmente tecnologias como TypeScript, Next.js, React, Tailwind CSS, PostgreSQL, Drizzle ORM, odds API, Docker y pnpm, segun corresponda al contenido publicable.
- RN-13: AI Digest debe listar inicialmente tecnologias como TypeScript, Node.js, RSS/scraping, OpenAI, Anthropic, DeepSeek, Resend, Supabase, GitHub Actions y email delivery, segun corresponda al contenido publicable.
- RN-14: Gerardo debe listar inicialmente tecnologias como TypeScript, Node.js, pnpm workspaces, Turborepo, Next.js, Tailwind CSS, shadcn/ui, Supabase Postgres, Drizzle ORM, GitHub Actions, Resend, React Email, Vercel, IOL integration y automated bot workflows, segun corresponda al contenido publicable.
- RN-15: Los repositorios iniciales detectados son CapriLucas/prode, CapriLucas/ai-digest y CapriLucas/gerardo; deben mostrarse como enlaces publicos solo si Lucas confirma que son publicables, y como "Private repository" en caso contrario.

## Criterios de Aceptacion
- CA-1: Dado un visitante que abre proyectos, cuando carga la seccion, entonces ve Prode, AI Digest y Gerardo como proyectos destacados.
- CA-2: Dado un proyecto destacado, cuando el visitante lo revisa, entonces encuentra descripcion, tecnologias, URL si existe y estado de repositorio.
- CA-3: Dado un proyecto con repositorio privado, cuando se muestra su informacion, entonces el sitio aclara que el repositorio es privado.
- CA-4: Dado un proyecto sin URL publica, cuando se muestra su informacion, entonces el sitio no muestra enlaces rotos ni URLs internas.
- CA-5: Dado un reclutador, cuando revisa los proyectos, entonces entiende que capacidades profesionales demuestra cada uno.
- CA-6: Dado un buscador, cuando indexa la seccion de proyectos, entonces encuentra contenido textual relevante para cada proyecto.
- CA-7: Dado cualquier visitante, cuando lee la seccion de proyectos, entonces todo el contenido visible esta en ingles.
- CA-8: Dado un proyecto destacado inicial, cuando el visitante revisa sus tecnologias, entonces el listado refleja tecnologias realmente usadas en ese proyecto.

## Resultado Esperado
El visitante puede evaluar rapidamente la experiencia practica de Lucas a traves de tres proyectos reales, entendiendo el valor de cada uno, las tecnologias utilizadas, el alcance de responsabilidad y la disponibilidad de URLs o repositorios.

## Definicion BDD/Gherkin
```gherkin
Feature: Featured projects showcase

  Scenario: Visitor sees the initial featured projects
    Given a visitor opens the projects section
    When the projects are displayed
    Then they see Prode, AI Digest, and Gerardo as featured projects

  Scenario: Visitor reviews project details
    Given a featured project is displayed
    When the visitor reads its card or detail view
    Then they find a description, technologies, public URL status, and repository status

  Scenario: Private repository is clearly identified
    Given a project repository is not public
    When the project is displayed
    Then the repository status is shown as private

  Scenario: Project without public URL does not show broken links
    Given a project has no public URL
    When the project is displayed
    Then no broken or internal URL is shown

  Scenario: Recruiter understands demonstrated capabilities
    Given a recruiter reviews the featured projects
    When they read each project description
    Then they understand the professional capabilities demonstrated by each project

  Scenario: Search engine indexes project content
    Given a search engine crawls the projects section
    When it analyzes the public content
    Then it finds relevant text for Prode, AI Digest, and Gerardo

  Scenario: Project content is only in English
    Given any visitor reads the projects section
    When visible text is displayed
    Then all visible project content is written in English

  Scenario: Initial project technologies are evidence-based
    Given an initial featured project is displayed
    When the visitor reviews its technologies
    Then the technology list reflects technologies actually used in that project
```
