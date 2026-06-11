# Job Opportunity Contact

## User Story
Como visitante reclutador, quiero contactar a Lucas desde el sitio, para iniciar una conversacion por una oportunidad laboral.

## Objetivo
Facilitar que reclutadores y potenciales empleadores puedan contactar a Lucas de forma rapida, clara y confiable, con un enfoque especifico en oportunidades laborales y sin introducir friccion innecesaria.

## Alcance
**Incluye:**
- Acceso visible a contacto desde la home y navegacion principal o CTA equivalente.
- Canal principal de contacto orientado a oportunidades laborales.
- Texto en ingles que invite a contactar a Lucas por roles full stack, AI o producto.
- Alternativas profesionales de contacto si aplica, como email, LinkedIn o GitHub.
- Estados claros cuando una accion de contacto no puede completarse.

**No incluye:**
- Sistema de mensajeria interno.
- Bandeja de administracion de mensajes.
- Automatizacion de respuestas.
- Captura de archivos adjuntos.
- CRM o integracion con herramientas externas de recruiting.

## Actores
- Visitante reclutador: Persona interesada en contactar a Lucas por una oportunidad laboral.
- Lucas: Profesional que recibe la consulta y decide como continuar la conversacion.

## Precondiciones
- La home presenta a Lucas y ofrece acceso visible a contacto.
- Existe al menos un canal de contacto publicable.
- Los textos de contacto estan en ingles.

## Disparador
El visitante selecciona una accion de contacto desde la home, seccion de contacto, CV o proyectos.

## Flujo Principal
1. El visitante identifica una accion clara de contacto.
2. El visitante selecciona el canal principal de contacto.
3. El sitio inicia o facilita la comunicacion con Lucas.
4. El visitante cuenta con contexto suficiente para enviar una oportunidad laboral.
5. Lucas recibe o puede recibir el contacto por el canal definido.

## Flujos Alternativos
### FA-1: Visitante prefiere contacto profesional externo
1. El visitante no quiere usar el canal principal.
2. El sitio muestra alternativas profesionales disponibles.
3. El visitante selecciona una alternativa y continua fuera del sitio.

### FA-2: Accion de contacto no disponible
1. El visitante intenta usar una accion de contacto.
2. La accion no puede completarse.
3. El sitio muestra una alternativa clara para contactar a Lucas.

### FA-3: Visitante necesita contexto antes de contactar
1. El visitante llega a la seccion de contacto.
2. El sitio refuerza brevemente el perfil profesional y tipos de oportunidades relevantes.
3. El visitante puede revisar proyectos o CV antes de enviar el contacto.

## Reglas de Negocio
- RN-1: Todo el contenido visible de contacto debe estar escrito en ingles.
- RN-2: El contacto debe estar orientado principalmente a oportunidades laborales.
- RN-3: El sitio debe ofrecer al menos un canal de contacto sin requerir autenticacion.
- RN-4: El canal principal debe ser facil de encontrar desde la home.
- RN-5: El texto debe indicar que Lucas esta abierto a conversaciones profesionales relevantes.
- RN-6: Si se ofrecen multiples canales, deben distinguirse claramente por uso esperado.
- RN-7: El sitio no debe solicitar informacion sensible al visitante.
- RN-8: Si una accion falla o no esta disponible, debe existir una alternativa visible.

## Criterios de Aceptacion
- CA-1: Dado un visitante en la home, cuando busca contactar a Lucas, entonces encuentra una accion visible de contacto.
- CA-2: Dado un reclutador interesado, cuando abre la seccion de contacto, entonces entiende que puede contactar a Lucas por oportunidades laborales.
- CA-3: Dado un visitante que selecciona el canal principal, cuando la accion se ejecuta, entonces puede iniciar una comunicacion con Lucas.
- CA-4: Dado un visitante que prefiere otro canal, cuando revisa contacto, entonces encuentra alternativas profesionales si estan disponibles.
- CA-5: Dado que una accion de contacto no esta disponible, cuando el visitante intenta usarla, entonces recibe una alternativa clara.
- CA-6: Dado cualquier visitante, cuando lee la seccion de contacto, entonces todo el contenido visible esta en ingles.

## Resultado Esperado
El visitante puede iniciar una conversacion laboral con Lucas de manera directa y sin friccion, con mensajes claros sobre el tipo de oportunidades relevantes y alternativas profesionales cuando correspondan.

## Definicion BDD/Gherkin
```gherkin
Feature: Job opportunity contact

  Scenario: Visitor finds contact from the home page
    Given a visitor is on the home page
    When they look for a way to contact Lucas
    Then they find a visible contact action

  Scenario: Recruiter understands contact purpose
    Given a recruiter opens the contact section
    When they read the contact copy
    Then they understand they can contact Lucas about job opportunities

  Scenario: Visitor starts communication through the primary channel
    Given a visitor selects the primary contact channel
    When the action is executed
    Then they can start communication with Lucas

  Scenario: Visitor uses an alternative professional channel
    Given a visitor prefers another professional channel
    When they review the contact options
    Then they find available alternatives if they exist

  Scenario: Contact action is unavailable
    Given a contact action is unavailable
    When a visitor tries to use it
    Then the site provides a clear alternative

  Scenario: Contact content is only in English
    Given any visitor reads the contact section
    When visible text is displayed
    Then all visible contact content is written in English
```
