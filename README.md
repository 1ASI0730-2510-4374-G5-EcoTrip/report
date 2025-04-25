# report


### Universidad Peruana de ciencias Aplicadas 
### Ingeniería de Software
### 2025-01
### Código del Curso <br> y Nombre del curso


### 4374 - Aplicaciones Web
### Nombre del profesor
### "Informe de Trabajo Final"
### Nombre del startup<br>
### Nombre del producto<br>
### Relación de integrantes (Incluyendo en cada caso Código, Apellidos y Nombres)<br>
### Mes y año<br>
---------------------------------------------------------------------------------------------------------------------------
### Tabla de contenidos
### Student Outcome

### Capítulo I: Introducción<br>

1.1. Startup Profile

1.1.1. Descripción de la Startup

1.1.2. Perfiles de integrantes del equipo

1.2. Solution Profile

1.2.1 Antecedentes y problemática

1.2.2 Lean UX Process.

1.2.2.1. Lean UX Problem Statements.

1.2.2.2. Lean UX Assumptions.

1.2.2.3. Lean UX Hypothesis Statements.

1.2.2.4. Lean UX Canvas.

1.3. Segmentos objetivo.

### Capítulo II: Requirements Elicitation & Analysis

2.1. Competidores.

2.1.1. Análisis competitivo.

2.1.2. Estrategias y tácticas frente a competidores.

2.2. Entrevistas.

2.2.1. Diseño de entrevistas.

2.2.2. Registro de entrevistas.

2.2.3. Análisis de entrevistas.

2.3. Needfinding.

2.3.1. User Personas.

2.3.2. User Task Matrix.

2.3.3. User Journey Mapping.

2.3.4. Empathy Mapping.

2.3.5. As-is Scenario Mapping.

2.4. Ubiquitous Language.


### Capítulo III: Requirements Specification

3.1. To-Be Scenario Mapping.

En esta sección se presenta el *To-Be Scenario Mapping* para cada uno de los segmentos de usuarios identificados: **Turistas Frecuentes** y **Turistas Ocasionales**. Este análisis tiene como objetivo visualizar cómo se transformaría la experiencia de estos usuarios al utilizar **EcoTrip**, una plataforma digital enfocada en la planificación y reserva de experiencias de viaje sostenibles.

A través del uso de EcoTrip, se busca mejorar los puntos de dolor detectados en el As-Is Scenario Mapping, ofreciendo una experiencia más intuitiva, informada y alineada con valores de responsabilidad ambiental y sostenibilidad. El mapeo considera los cambios clave que esta nueva solución podría aportar en términos de comportamiento, pensamiento y emociones de los usuarios.

El proceso de elaboración del To-Be Scenario Mapping siguió las siguientes etapas:

- **Preparación:** Revisión de los insights obtenidos del As-Is Scenario Mapping.
- **Lluvia de ideas individual:** Identificación de posibles soluciones y mejoras centradas en el usuario.
- **Revisión e identificación de fases:** Se mantuvieron las mismas fases empleadas en el análisis As-Is para asegurar comparabilidad.
- **Comparación con el As-Is:** Se contrastó con el escenario actual para identificar mejoras concretas, tanto funcionales como emocionales.

Las fases consideradas en este análisis son: **Descubrimiento, Evaluación, Reserva, Experiencia y Seguimiento.**


#### To-Be Scenario Mapping – Turista Frecuente
![To-Be Scenario Mapping](https://firebasestorage.googleapis.com/v0/b/abraam-66aa7.appspot.com/o/tobe1.jpg?alt=media&token=462ed5e0-3ddc-4eb1-b2c6-3bdcf1e759a5)

#### To-Be Scenario Mapping – Turista Ocasional
![To-Be Scenario Mapping](https://firebasestorage.googleapis.com/v0/b/abraam-66aa7.appspot.com/o/tobe2.jpg?alt=media&token=5669aba7-5f26-41ff-9548-fdd1c3a5084e)


3.2. User Stories.

En esta sección se presentan las User Stories desarrolladas para el proyecto EcoTrip, una plataforma digital orientada al turismo sostenible. Las historias están elaboradas en base a los perfiles identificados en el To-Be Scenario Mapping: Turistas Frecuentes y Turistas Ocasionales.

Cada historia refleja una necesidad concreta de los usuarios y está asociada a una funcionalidad clave del sistema. Asimismo, se incluyen los criterios de aceptación formulados en formato Gherkin, con tres escenarios por historia, lo cual permite validar de manera precisa y completa si una funcionalidad cumple con los requisitos del usuario. Esta estructura facilita la planificación ágil del desarrollo y asegura el alineamiento entre el equipo de diseño, desarrollo y las expectativas de los usuarios.


| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación (Gherkin)** | **Relacionado con (Epic ID)** |
|---------------------|------------|------------------|----------------------------------------|-------------------------------|
| EP-01 | Explorar experiencias | Como visitante del segmento *Turista Ocasional*, quiero ver experiencias sostenibles para saber qué ofrece EcoTrip. | **Escenario 1:**<br>**Given** que soy un visitante del segmento *Turista Ocasional*<br>**When** ingreso a la sección de experiencias<br>**Then** veo una lista de actividades con nombre, lugar y tipo.<br><br>**Escenario 2:**<br>**Given** que estoy en la lista de experiencias<br>**When** hago clic en una actividad<br>**Then** accedo a una página con información detallada.<br><br>**Escenario 3:**<br>**Given** que veo la lista<br>**When** no hay actividades disponibles<br>**Then** recibo un mensaje de “No se encontraron experiencias”. | - |
| US-01.1 | Filtrar experiencias | Como visitante del segmento *Turista Frecuente*, quiero filtrar por tipo de experiencia para encontrar lo que me interesa. | **Escenario 1:**<br>**Given** que estoy viendo las experiencias<br>**When** selecciono “Voluntariado” en los filtros<br>**Then** solo se muestran experiencias de voluntariado.<br><br>**Escenario 2:**<br>**Given** que ya he filtrado<br>**When** regreso a la lista<br>**Then** el filtro se mantiene aplicado.<br><br>**Escenario 3:**<br>**Given** que selecciono varios tipos<br>**When** aplico los filtros<br>**Then** se actualiza la lista con las experiencias combinadas. | EP-01 |
| EP-02 | Registro de proveedores | Como proveedor, quiero registrarme para ofrecer mis servicios turísticos. | **Escenario 1:**<br>**Given** que soy proveedor<br>**When** ingreso mis datos en el formulario<br>**Then** puedo enviar mi solicitud para revisión.<br><br>**Escenario 2:**<br>**Given** que subo mis documentos<br>**When** los archivos son válidos<br>**Then** el sistema me permite completar el registro.<br><br>**Escenario 3:**<br>**Given** que envío el formulario<br>**When** el proceso es exitoso<br>**Then** recibo un correo de confirmación. | - |
| US-02.1 | Aprobación de proveedor | Como administrador, quiero revisar los datos del proveedor para aprobar o rechazar su ingreso. | **Escenario 1:**<br>**Given** que hay una solicitud nueva<br>**When** reviso los documentos<br>**Then** puedo aprobarla desde el panel.<br><br>**Escenario 2:**<br>**Given** que detecto errores<br>**When** rechazo la solicitud<br>**Then** puedo escribir una razón y notificar al proveedor.<br><br>**Escenario 3:**<br>**Given** que apruebo una solicitud<br>**When** finalizo el proceso<br>**Then** se actualiza el estado a “Proveedor Activo”. | EP-02 |
| EP-03 | Crear plan | Como turista del segmento *Turista Frecuente*, quiero crear mi propio plan de viaje con actividades y hospedajes. | **Escenario 1:**<br>**Given** que estoy registrado<br>**When** accedo a la herramienta de itinerario<br>**Then** puedo agregar actividades, hospedajes y traslados.<br><br>**Escenario 2:**<br>**Given** que ya tengo un plan<br>**When** edito una actividad<br>**Then** se actualiza el itinerario en tiempo real.<br><br>**Escenario 3:**<br>**Given** que he terminado mi plan<br>**When** hago clic en guardar<br>**Then** puedo acceder a él desde mi perfil. | - |
| US-03.1 | Recomendaciones para itinerario | Como turista del segmento *Turista Ocasional*, quiero recibir sugerencias basadas en mis gustos. | **Escenario 1:**<br>**Given** que he completado mi perfil<br>**When** ingreso a la herramienta<br>**Then** veo actividades sugeridas basadas en mis intereses.<br><br>**Escenario 2:**<br>**Given** que no me gustan las sugerencias<br>**When** las marco como “No me interesa”<br>**Then** el sistema aprende y actualiza la lista.<br><br>**Escenario 3:**<br>**Given** que acepto una sugerencia<br>**When** la agrego al itinerario<br>**Then** se incorpora correctamente en mi plan. | EP-03 |
| EP-04 | Conexión con guías | Como turista del segmento *Turista Frecuente*, quiero contactar guías que hablen mi idioma. | **Escenario 1:**<br>**Given** que estoy buscando guías<br>**When** selecciono “Español”<br>**Then** solo se muestran guías que lo hablen.<br><br>**Escenario 2:**<br>**Given** que veo un guía<br>**When** accedo a su perfil<br>**Then** puedo leer reseñas y ver disponibilidad.<br><br>**Escenario 3:**<br>**Given** que encuentro un guía disponible<br>**When** lo contacto<br>**Then** puedo enviarle un mensaje directamente. | - |
| US-04.1 | Reservar guía específico | Como turista del segmento *Turista Ocasional*, quiero poder reservar a un guía en específico. | **Escenario 1:**<br>**Given** que encontré un guía<br>**When** elijo una fecha disponible<br>**Then** puedo hacer la reserva fácilmente.<br><br>**Escenario 2:**<br>**Given** que hice la reserva<br>**When** reviso mi perfil<br>**Then** veo la reserva en mi historial.<br><br>**Escenario 3:**<br>**Given** que el guía la confirma<br>**When** recibo el correo<br>**Then** me muestra el lugar y hora del encuentro. | EP-04 |
| EP-05 | Reservas y pagos | Como turista del segmento *Turista Frecuente*, quiero reservar experiencias y pagar fácilmente. | **Escenario 1:**<br>**Given** que selecciono una experiencia<br>**When** voy a pagar<br>**Then** puedo elegir entre tarjeta, Yape o transferencia.<br><br>**Escenario 2:**<br>**Given** que el pago fue exitoso<br>**When** reviso mi perfil<br>**Then** veo la reserva con estado “Confirmado”.<br><br>**Escenario 3:**<br>**Given** que tengo una duda<br>**When** hago clic en “Soporte”<br>**Then** me comunico con atención al cliente. | - |
| US-05.1 | Cancelar reserva | Como turista del segmento *Turista Ocasional*, quiero cancelar una reserva si no podré asistir. | **Escenario 1:**<br>**Given** que tengo una reserva activa<br>**When** accedo a ella<br>**Then** veo la opción para cancelar.<br><br>**Escenario 2:**<br>**Given** que cancelo con anticipación<br>**When** el plazo lo permite<br>**Then** recibo un reembolso automático.<br><br>**Escenario 3:**<br>**Given** que se cancela<br>**When** reviso mi correo<br>**Then** encuentro una confirmación de cancelación. | EP-05 |
| EP-06 | Página informativa | Como visitante del segmento *Turista Ocasional*, quiero saber qué es EcoTrip y qué servicios ofrece. | **Escenario 1:**<br>**Given** que ingreso al sitio<br>**When** accedo a la sección “Sobre EcoTrip”<br>**Then** encuentro una descripción clara de la plataforma.<br><br>**Escenario 2:**<br>**Given** que tengo dudas<br>**When** entro a Preguntas Frecuentes<br>**Then** puedo resolver inquietudes comunes.<br><br>**Escenario 3:**<br>**Given** que quiero saber más<br>**When** hago clic en “Contáctanos”<br>**Then** accedo a un formulario de contacto. | - |
| US-06.1 | Ver testimonios | Como visitante del segmento *Turista Frecuente*, quiero leer opiniones de otros para confiar en la plataforma. | **Escenario 1:**<br>**Given** que entro a la sección de testimonios<br>**When** veo las opiniones<br>**Then** se muestran con nombre, experiencia y calificación.<br><br>**Escenario 2:**<br>**Given** que quiero una experiencia específica<br>**When** uso el filtro por categoría<br>**Then** veo solo testimonios relevantes.<br><br>**Escenario 3:**<br>**Given** que leo un testimonio<br>**When** me parece útil<br>**Then** puedo marcarlo como “útil”. | EP-06 |






3.3. Impact Mapping.

3.4. Product Backlog.



### Capítulo IV: Product Design

4.1. Style Guidelines.

4.1.1. General Style Guidelines.

4.1.2. Web Style Guidelines.


4.2. Information Architecture.

4.2.1. Organization Systems.

4.2.2. Labeling Systems.

4.2.3. SEO Tags and Meta Tags

4.2.4. Searching Systems.

4.2.5. Navigation Systems.


4.3. Landing Page UI Design.

4.3.1. Landing Page Wireframe.

4.3.2. Landing Page Mock-up.


4.4. Web Applications UX/UI Design.

4.4.1. Web Applications Wireframes.

4.4.2. Web Applications Wireflow Diagrams.

4.4.2. Web Applications Mock-ups.

4.4.3. Web Applications User Flow Diagrams.

4.5. Web Applications Prototyping.

4.6. Domain-Driven Software Architecture.

4.6.1. Software Architecture Context Diagram.

4.6.2. Software Architecture Container Diagrams.

4.6.3. Software Architecture Components Diagrams.


4.7. Software Object-Oriented Design.

4.7.1. Class Diagrams.

4.7.2. Class Dictionary.


4.8. Database Design.

4.8.1. Database Diagram.

### Capítulo V: Product Implementation, Validation & Deployment

5.1. Software Configuration Management.

5.1.1. Software Development Environment Configuration.

5.1.2. Source Code Management.

5.1.3. Source Code Style Guide & Conventions.

5.1.4. Software Deployment Configuration.

5.2. Landing Page, Services & Applications Implementation.

5.2.X. Sprint n

5.2.X.1. Sprint Planning n.

5.2.X.2. Aspect Leaders and Collaborators.

5.2.X.3. Sprint Backlog n.

5.2.X.4. Development Evidence for Sprint Review.

5.2.X.5. Execution Evidence for Sprint Review.

5.2.X.6. Services Documentation Evidence for Sprint Review.

5.2.X.7. Software Deployment Evidence for Sprint Review.

5.2.X.8. Team Collaboration Insights during Sprint.

5.3. Validation Interviews.

5.3.1. Diseño de Entrevistas.

5.3.2. Registro de Entrevistas.

5.3.3. Evaluaciones según heurísticas.

5.4. Video About-the-Product.

### Conclusiones
### Conclusiones y recomendaciones.
### Video About-the-Team.
