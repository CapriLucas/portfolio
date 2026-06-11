# Home SEO-Friendly Profile

## User Story
Como visitante reclutador, quiero ver una home clara y SEO-friendly en ingles, para entender rapidamente el perfil profesional de Lucas como full stack developer con experiencia en AI.

## Objetivo
Presentar a Lucas como desarrollador full stack con experiencia practica en AI, comunicando rapidamente su propuesta profesional, los tipos de proyectos que construye y los caminos principales para explorar su trabajo, ver su CV o contactarlo por oportunidades laborales.

## Alcance
**Incluye:**
- Contenido visible de la home escrito unicamente en ingles.
- Posicionamiento principal de Lucas como full stack developer con experiencia practica en AI.
- Mensaje inicial que comunique que hace Lucas, que tipo de proyectos construye y como puede aportar valor.
- Accesos visibles hacia proyectos, CV y contacto.
- Contenido y estructura orientados a SEO organico.
- Tono profesional, directo y personal.
- Mencion explicita de experiencia AI, desarrollo full stack y capacidad de llevar productos desde idea hasta despliegue.

**No incluye:**
- Detalle completo de cada proyecto destacado.
- Formulario o flujo completo de contacto.
- Contenido completo del CV.
- Implementacion o definicion tecnica de frameworks, librerias, base de datos o hosting.
- Contenido multilenguaje.

## Actores
- Visitante reclutador: Persona que evalua a Lucas para una oportunidad laboral y necesita entender rapidamente su perfil profesional.
- Lucas: Profesional propietario del sitio que quiere comunicar su experiencia, proyectos y disponibilidad para oportunidades laborales.

## Precondiciones
- El visitante accede a la pagina principal del sitio.
- El sitio cuenta con contenido profesional base en ingles.
- Existen destinos o secciones previstas para proyectos, CV y contacto.

## Disparador
Un visitante ingresa a la home del sitio desde un buscador, enlace compartido, perfil profesional o URL directa.

## Flujo Principal
1. El visitante accede a la home.
2. El sitio muestra un mensaje principal en ingles que identifica a Lucas como full stack developer con experiencia en AI.
3. El sitio comunica en los primeros segundos el tipo de valor profesional que Lucas ofrece.
4. El visitante identifica accesos claros hacia proyectos, CV y contacto.
5. El visitante puede continuar explorando el sitio segun su intencion: revisar proyectos, ver el CV o iniciar contacto.
6. El contenido de la home presenta senales indexables y comprensibles para buscadores sobre el perfil profesional de Lucas.

## Flujos Alternativos
### FA-1: Visitante llega desde un buscador
1. El visitante encuentra un resultado con titulo y descripcion relacionados con Lucas, full stack development y AI.
2. El visitante abre la home.
3. La home confirma rapidamente que el resultado coincide con su busqueda profesional.

### FA-2: Visitante busca una accion concreta
1. El visitante entra a la home con intencion de ver proyectos, CV o contacto.
2. El sitio muestra accesos visibles a esas acciones.
3. El visitante selecciona el acceso que corresponde a su objetivo.

### FA-3: Visitante no conoce previamente a Lucas
1. El visitante accede sin contexto previo.
2. La home explica quien es Lucas, que hace y por que su experiencia es relevante.
3. El visitante puede decidir si profundiza en proyectos, CV o contacto.

## Reglas de Negocio
- RN-1: Todo el contenido visible de la home debe estar escrito en ingles.
- RN-2: La home debe posicionar a Lucas como full stack developer con experiencia practica en AI.
- RN-3: La home debe incluir accesos visibles a proyectos, CV y contacto.
- RN-4: La home debe comunicar valor profesional en los primeros segundos de lectura.
- RN-5: El tono debe ser profesional, directo y personal.
- RN-6: La home debe incluir contenido indexable relevante para SEO organico.
- RN-7: La home no debe depender de conocimiento previo del visitante sobre Lucas.
- RN-8: La home debe mencionar desarrollo full stack, AI y capacidad de llevar productos desde idea hasta despliegue.

## Criterios de Aceptacion
- CA-1: Dado un visitante que ingresa a la home, cuando lee la primera pantalla, entonces entiende que Lucas es full stack developer con experiencia en AI.
- CA-2: Dado un visitante reclutador, cuando revisa la home, entonces encuentra accesos claros a proyectos, CV y contacto.
- CA-3: Dado un visitante que llega sin contexto previo, cuando lee la home, entonces entiende que hace Lucas y que valor profesional puede aportar.
- CA-4: Dado un buscador que indexa la home, cuando analiza el contenido publico, entonces encuentra texto relevante sobre Lucas, full stack development, AI y proyectos.
- CA-5: Dado cualquier visitante, cuando navega la home, entonces todo el contenido visible esta en ingles.
- CA-6: Dado un visitante que evalua seniority y alcance, cuando lee la home, entonces encuentra senales de experiencia end-to-end desde idea hasta despliegue.

## Resultado Esperado
La home funciona como entrada principal del sitio y permite que un reclutador o potencial empleador entienda rapidamente el perfil de Lucas, su foco en full stack development y AI, y los caminos para revisar proyectos, acceder al CV o contactarlo.

## Definicion BDD/Gherkin
```gherkin
Feature: Home SEO-friendly professional profile

  Scenario: Visitor understands Lucas' professional positioning
    Given a recruiter visits the home page
    When the first screen is displayed
    Then the recruiter understands that Lucas is a full stack developer with AI experience

  Scenario: Recruiter finds key navigation paths
    Given a recruiter is reviewing the home page
    When they look for next actions
    Then they can access projects, CV, and contact paths clearly

  Scenario: New visitor understands the value proposition
    Given a visitor does not know Lucas beforehand
    When they read the home page content
    Then they understand what Lucas does and the professional value he can provide

  Scenario: Search engine can index relevant professional content
    Given a search engine crawls the public home page
    When it analyzes the page content
    Then it finds relevant text about Lucas, full stack development, AI, and projects

  Scenario: Visible content is only in English
    Given any visitor opens the home page
    When they read the visible content
    Then all visible text is written in English

  Scenario: Visitor identifies end-to-end product experience
    Given a visitor evaluates Lucas' scope of experience
    When they read the home page
    Then they find signals that Lucas can take products from idea to deployment
```
