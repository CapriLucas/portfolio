# CV Access

## User Story
Como visitante reclutador, quiero acceder al CV de Lucas, para revisar su experiencia profesional, habilidades y antecedentes en formato claro y compartible.

## Objetivo
Permitir que reclutadores y potenciales empleadores encuentren, abran y compartan facilmente el CV de Lucas desde el sitio, manteniendo consistencia con el contenido en ingles y reforzando el posicionamiento profesional definido en la home.

## Alcance
**Incluye:**
- Acceso visible al CV desde la home y la navegacion principal o CTA equivalente.
- CV disponible en ingles.
- Posibilidad de abrir o descargar el CV.
- Nombre y contexto profesional claros alrededor del acceso al CV.
- Manejo claro si el archivo de CV no esta disponible temporalmente.

**No incluye:**
- Editor de CV dentro del sitio.
- Generacion dinamica de CV desde datos estructurados.
- Multiples versiones de CV por idioma.
- Carga de archivos por usuarios externos.
- Tracking avanzado de descargas.

## Actores
- Visitante reclutador: Persona que necesita revisar el CV para evaluar una oportunidad laboral.
- Lucas: Propietario del sitio que quiere compartir su CV de forma profesional.

## Precondiciones
- Existe una version publicable del CV en ingles.
- La home ya incluye un acceso visible hacia el CV.
- El CV no contiene informacion que Lucas no quiera publicar.

## Disparador
El visitante selecciona el acceso al CV desde la home, navegacion, seccion de contacto o enlace directo.

## Flujo Principal
1. El visitante identifica el acceso al CV.
2. El visitante selecciona la accion para abrir o descargar el CV.
3. El sitio entrega el CV en un formato claro y compartible.
4. El visitante puede revisar experiencia, habilidades y antecedentes profesionales.
5. El visitante puede volver al sitio para revisar proyectos o contactar a Lucas.

## Flujos Alternativos
### FA-1: CV no disponible temporalmente
1. El visitante intenta acceder al CV.
2. El sitio informa en ingles que el CV no esta disponible temporalmente.
3. El sitio ofrece una alternativa de contacto para solicitarlo.

### FA-2: Visitante llega directamente al CV
1. El visitante abre un enlace directo al CV.
2. El CV permite identificar claramente a Lucas y su perfil profesional.
3. El visitante puede usar la informacion del CV para continuar el proceso de evaluacion.

### FA-3: Visitante quiere contactar despues de leer el CV
1. El visitante revisa el CV.
2. El sitio mantiene o facilita un camino claro de regreso a contacto.
3. El visitante puede iniciar una conversacion por una oportunidad laboral.

## Reglas de Negocio
- RN-1: El CV publicable debe estar en ingles.
- RN-2: El acceso al CV debe ser visible desde la home.
- RN-3: El CV debe poder abrirse o descargarse sin autenticacion.
- RN-4: El acceso al CV debe usar texto claro en ingles, como "View CV" o "Download CV".
- RN-5: Si el CV no esta disponible, el sitio debe mostrar un mensaje claro y ofrecer contacto alternativo.
- RN-6: El CV no debe exponer informacion privada que Lucas no quiera publicar.
- RN-7: La experiencia presentada en el CV debe ser consistente con el posicionamiento de la home y los proyectos destacados.

## Criterios de Aceptacion
- CA-1: Dado un visitante en la home, cuando busca informacion curricular, entonces encuentra un acceso visible al CV.
- CA-2: Dado un visitante que selecciona el CV, cuando la accion se completa, entonces puede abrir o descargar el CV.
- CA-3: Dado un reclutador que revisa el CV, cuando lee el contenido, entonces encuentra informacion profesional en ingles.
- CA-4: Dado que el CV no esta disponible, cuando el visitante intenta acceder, entonces recibe un mensaje claro y una alternativa de contacto.
- CA-5: Dado un visitante que accede al CV, cuando quiere continuar evaluando a Lucas, entonces puede volver a proyectos o contacto.

## Resultado Esperado
El CV de Lucas queda disponible de forma profesional, clara y compartible, permitiendo que un reclutador avance desde la home hacia una evaluacion curricular y luego hacia proyectos o contacto.

## Definicion BDD/Gherkin
```gherkin
Feature: CV access

  Scenario: Visitor finds CV from the home page
    Given a visitor is on the home page
    When they look for resume information
    Then they find a visible CV access point

  Scenario: Visitor opens or downloads the CV
    Given a visitor selects the CV action
    When the action is completed
    Then the visitor can open or download the CV

  Scenario: Recruiter reads English CV content
    Given a recruiter opens the CV
    When they read its content
    Then the professional information is available in English

  Scenario: CV is temporarily unavailable
    Given the CV file is not available
    When a visitor tries to access it
    Then the site shows a clear message and an alternative contact path

  Scenario: Visitor continues after reviewing the CV
    Given a visitor has accessed the CV
    When they want to continue evaluating Lucas
    Then they can return to projects or contact options
```
