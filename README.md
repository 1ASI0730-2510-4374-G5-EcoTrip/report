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

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación (Gherkin)** | **Relacionado con (Epic ID)** |
|---------------------|------------|------------------|----------------------------------------|-------------------------------|
| EP-01 | Explorar experiencias | Como visitante, quiero ver experiencias sostenibles para saber qué ofrece EcoTrip. | **Given** que soy visitante<br>**When** ingreso a la sección de experiencias<br>**Then** puedo ver una lista de actividades disponibles. | - |
| US-01.1 | Filtrar experiencias | Como visitante, quiero filtrar por tipo de experiencia para encontrar lo que me interesa. | **Given** que veo las experiencias<br>**When** elijo un tipo como “voluntariado”<br>**Then** solo se muestran ese tipo de experiencias. | EP-01 |
| EP-02 | Registro de proveedores | Como proveedor, quiero registrarme para ofrecer mis servicios turísticos. | **Given** que soy proveedor<br>**When** completo el formulario de registro<br>**Then** recibo un mensaje indicando que fue enviado para revisión. | - |
| US-02.1 | Aprobación de proveedor | Como administrador, quiero revisar los datos del proveedor para aprobar o rechazar su ingreso. | **Given** que hay un nuevo registro<br>**When** reviso sus datos<br>**Then** puedo aprobarlo o rechazarlo. | EP-02 |
| EP-03 | Crear plan | Como turista, quiero crear mi propio plan de viaje con actividades y hospedajes. | **Given** que estoy registrado<br>**When** uso la herramienta de itinerario<br>**Then** puedo armar mi viaje agregando opciones. | - |
| US-03.1 | Recomendaciones para itinerario | Como turista, quiero recibir sugerencias basadas en mis gustos. | **Given** que completé mi perfil<br>**When** creo un itinerario<br>**Then** se me sugieren actividades que me podrían gustar. | EP-03 |
| EP-04 | Conexión con guías | Como turista, quiero contactar guías que hablen mi idioma. | **Given** que busco un guía<br>**When** indico mi idioma<br>**Then** veo una lista de guías que lo hablan. | - |
| US-04.1 | Reservar guía específico | Como turista, quiero poder reservar a un guía en específico. | **Given** que encontré un guía<br>**When** hago clic en reservar<br>**Then** recibo una confirmación de reserva. | EP-04 |
| EP-05 | Reservas y pagos | Como turista, quiero reservar experiencias y pagar fácilmente. | **Given** que elijo una experiencia<br>**When** hago clic en reservar y pago<br>**Then** recibo una confirmación automática. | - |
| US-05.1 | Cancelar reserva | Como turista, quiero cancelar una reserva si no podré asistir. | **Given** que tengo una reserva<br>**When** la cancelo dentro del tiempo permitido<br>**Then** recibo un mensaje de cancelación y reembolso. | EP-05 |
| EP-06 | Página informativa | Como visitante, quiero saber qué es EcoTrip y qué servicios ofrece. | **Given** que entro al sitio<br>**When** veo la página principal<br>**Then** encuentro información sobre la plataforma. | - |
| US-06.1 | Ver testimonios | Como visitante, quiero leer opiniones de otros para confiar en la plataforma. | **Given** que estoy en la página<br>**When** entro a la sección de testimonios<br>**Then** puedo leer lo que otros viajeros dicen. | EP-06 |





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
