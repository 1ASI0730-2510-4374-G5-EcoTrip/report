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

En esta sección se presenta el *To-Be Scenario Mapping* para cada uno de los segmentos de usuarios identificados: **Turistas Responsables** y **Proveedores Turísticos Sostenibles**. Este análisis tiene como objetivo visualizar cómo se transformaría la experiencia de estos usuarios al utilizar **EcoTrip**, una plataforma digital enfocada en la planificación y reserva de experiencias de viaje sostenibles.

A través del uso de EcoTrip, se busca mejorar los puntos de dolor detectados en el As-Is Scenario Mapping, ofreciendo una experiencia más intuitiva, informada y alineada con valores de responsabilidad ambiental y sostenibilidad. El mapeo considera los cambios clave que esta nueva solución podría aportar en términos de comportamiento, pensamiento y emociones de los usuarios.

El proceso de elaboración del To-Be Scenario Mapping siguió las siguientes etapas:

- **Preparación:** Revisión de los insights obtenidos del As-Is Scenario Mapping.
- **Lluvia de ideas individual:** Identificación de posibles soluciones y mejoras centradas en el usuario.
- **Revisión e identificación de fases:** Se mantuvieron las mismas fases empleadas en el análisis As-Is para asegurar comparabilidad.
- **Comparación con el As-Is:** Se contrastó con el escenario actual para identificar mejoras concretas, tanto funcionales como emocionales.

Las fases consideradas en este análisis son: **Descubrimiento, Evaluación, Reserva, Experiencia y Seguimiento.**


#### To-Be Scenario Mapping – Turistas Responsables
![To-Be Scenario Mapping](https://firebasestorage.googleapis.com/v0/b/abraam-66aa7.appspot.com/o/tobe1.jpg?alt=media&token=16534694-15c3-4cf9-aedd-6f7f3e9d7fe4)

#### To-Be Scenario Mapping – Proveedores Turísticos Sostenibles
![To-Be Scenario Mapping](https://firebasestorage.googleapis.com/v0/b/abraam-66aa7.appspot.com/o/tobe2.jpg?alt=media&token=da5d1a75-1f37-4e5e-abe0-e0b945fdbc1c)


3.2. User Stories.

En esta sección se presentan las User Stories desarrolladas para el proyecto EcoTrip, una plataforma digital orientada al turismo sostenible. Las historias están elaboradas en base a los perfiles identificados en el To-Be Scenario Mapping: Turistas Frecuentes y Turistas Ocasionales.

Cada historia refleja una necesidad concreta de los usuarios y está asociada a una funcionalidad clave del sistema. Asimismo, se incluyen los criterios de aceptación formulados en formato Gherkin, con tres escenarios por historia, lo cual permite validar de manera precisa y completa si una funcionalidad cumple con los requisitos del usuario. Esta estructura facilita la planificación ágil del desarrollo y asegura el alineamiento entre el equipo de diseño, desarrollo y las expectativas de los usuarios.

Epics: 

| **Epic ID** | **Título**                     | **Descripción**                                                                                                                               | **Segmento Objetivo**              |
| ----------- | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| EP-01       | Explorar experiencias          | Como turista responsable, quiero ver experiencias sostenibles para saber qué ofrece EcoTrip.                                                  | Turistas responsables              |
| EP-02       | Registro de proveedores        | Como proveedor turístico sostenible, quiero registrarme para ofrecer mis servicios turísticos en la plataforma.                               | Proveedores turísticos sostenibles |
| EP-03       | Crear plan                     | Como turista responsable, quiero crear mi propio plan de viaje con actividades y hospedajes sostenibles.                                      | Turistas responsables              |
| EP-04       | Conexión con guías             | Como turista responsable, quiero contactar guías que hablen mi idioma para enriquecer mi experiencia.                                         | Turistas responsables              |
| EP-05       | Reservas y pagos               | Como turista responsable, quiero reservar experiencias y pagar fácilmente para confirmar mi participación.                                    | Turistas responsables              |
| EP-06       | Página informativa             | Como turista responsable, quiero saber qué es EcoTrip y qué servicios ofrece para decidir si usar la plataforma.                              | Turistas responsables              |
| EP-07       | Gestión de favoritos           | Como turista responsable, quiero poder marcar experiencias como favoritas para consultarlas después.                                          | Turistas responsables              |
| EP-08       | Validación de formularios      | Como proveedor turístico sostenible, quiero que todos los formularios tengan validación para evitar errores en el registro o actualizaciones. | Proveedores turísticos sostenibles |
| EP-09       | Notificaciones visuales        | Como usuario (turista o proveedor), quiero recibir mensajes visuales para saber qué acciones fueron exitosas o fallidas.                      | Ambos segmentos                    |
| EP-10       | Personalización del perfil     | Como usuario (turista o proveedor), quiero personalizar mi perfil con datos e intereses para mejorar mi experiencia en la plataforma.         | Ambos segmentos                    |
| EP-11       | Accesibilidad y UX             | Como usuario (turista o proveedor), quiero que el sitio sea accesible y cómodo para navegar en cualquier dispositivo.                         | Ambos segmentos                    |
| **EP-12**   | Edición de experiencias        | Como proveedor turístico sostenible, quiero poder editar mis experiencias publicadas para mantener la información actualizada.                | Proveedores turísticos sostenibles |
| **EP-13**   | Edición de perfil de proveedor | Como proveedor turístico sostenible, quiero poder editar la información de mi perfil para corregir o actualizar datos relevantes.             | Proveedores turísticos sostenibles |
| **EP-14**   | Gestión de redes sociales      | Como proveedor turístico sostenible, quiero poder agregar y modificar los enlaces a mis redes sociales para mejorar mi visibilidad.           | Proveedores turísticos sostenibles |

User Stories: 

| **User Story ID** | **Título**                       | **Descripción (Segmento Objetivo)**                                                                                            | **Criterios de Aceptación (Gherkin)**                                                                                                                                                                                                                                                                                                                                                                | **Relacionado con (Epic ID)** |
| ----------------- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| US-01             | Filtrar experiencias             | Como turista responsable, quiero filtrar por tipo de experiencia para encontrar lo que me interesa.                            | **Escenario 1:**<br>Given que estoy viendo las experiencias<br>When selecciono “Voluntariado”<br>Then solo se muestran experiencias de voluntariado.<br>**Escenario 2:**<br>Given que ya he filtrado<br>When regreso a la lista<br>Then el filtro se mantiene aplicado.<br>**Escenario 3:**<br>Given que selecciono varios tipos<br>When aplico los filtros<br>Then se actualiza la lista combinada. | EP-01                         |
| US-02             | Aprobación de proveedor          | Como administrador, quiero revisar los datos del proveedor turístico sostenible para aprobar o rechazar su ingreso.            | **Escenario 1:**<br>Given que hay una solicitud nueva<br>When reviso los documentos<br>Then puedo aprobarla.<br>**Escenario 2:**<br>Given que detecto errores<br>When rechazo la solicitud<br>Then puedo escribir una razón y notificar.<br>**Escenario 3:**<br>Given que apruebo<br>When finalizo el proceso<br>Then se actualiza a “Proveedor Activo”.                                             | EP-02                         |
| US-03             | Recomendaciones para itinerario  | Como turista responsable, quiero recibir sugerencias basadas en mis gustos.                                                    | **Escenario 1:**<br>Given que completé mi perfil<br>When ingreso a recomendaciones<br>Then veo actividades sugeridas.<br>**Escenario 2:**<br>Given que no me gustan<br>When marco “No me interesa”<br>Then se actualiza la lista.<br>**Escenario 3:**<br>Given que acepto<br>When agrego al itinerario<br>Then aparece en mi plan.                                                                   | EP-03                         |
| US-04             | Reservar guía específico         | Como turista responsable, quiero reservar a un guía específico que hable mi idioma.                                            | **Escenario 1:**<br>Given que encontré un guía<br>When elijo una fecha<br>Then hago la reserva.<br>**Escenario 2:**<br>Given que reservé<br>When reviso mi perfil<br>Then veo el historial.<br>**Escenario 3:**<br>Given que el guía confirma<br>When recibo el correo<br>Then veo detalles del encuentro.                                                                                           | EP-04                         |
| US-05             | Cancelar reserva                 | Como turista responsable, quiero cancelar una reserva si no puedo asistir.                                                     | **Escenario 1:**<br>Given que tengo una reserva<br>When accedo a ella<br>Then veo la opción cancelar.<br>**Escenario 2:**<br>Given que cancelo a tiempo<br>When aplico la acción<br>Then recibo reembolso.<br>**Escenario 3:**<br>Given que se cancela<br>When reviso correo<br>Then veo confirmación.                                                                                               | EP-05                         |
| US-06             | Ver testimonios                  | Como turista responsable, quiero leer opiniones de otros para confiar en la plataforma.                                        | **Escenario 1:**<br>Given que entro a testimonios<br>When veo las opiniones<br>Then muestran nombre, experiencia y calificación.<br>**Escenario 2:**<br>Given que busco algo específico<br>When uso filtro<br>Then veo testimonios relevantes.<br>**Escenario 3:**<br>Given que leo un testimonio<br>When me parece útil<br>Then puedo marcarlo como “útil”.                                         | EP-06                         |
| US-07             | Marcar experiencia como favorita | Como turista responsable, quiero marcar experiencias como favoritas para guardarlas y verlas luego.                            | **Escenario 1:**<br>Given que veo una experiencia<br>When hago clic en corazón<br>Then se guarda como favorita.<br>**Escenario 2:**<br>Given que estoy en mi perfil<br>When entro a favoritos<br>Then veo lista guardada.<br>**Escenario 3:**<br>Given que quito una experiencia<br>When hago clic otra vez<br>Then se elimina de favoritos.                                                         | EP-07                         |
| US-08             | Validar campos obligatorios      | Como proveedor turístico sostenible, quiero validaciones en los formularios para no enviar datos incompletos.                  | **Escenario 1:**<br>Given que lleno un formulario<br>When dejo un campo vacío<br>Then veo error.<br>**Escenario 2:**<br>Given que pongo un correo inválido<br>When intento enviar<br>Then veo advertencia.<br>**Escenario 3:**<br>Given que corrijo<br>When vuelvo a intentar<br>Then se envía correctamente.                                                                                        | EP-08                         |
| US-09             | Mostrar alertas visuales         | Como usuario (turista o proveedor), quiero ver alertas (toasts) al realizar acciones importantes.                              | **Escenario 1:**<br>Given que agrego experiencia<br>When confirmo acción<br>Then aparece toast de éxito.<br>**Escenario 2:**<br>Given que cancelo reserva<br>When confirmo cancelación<br>Then veo mensaje de confirmación.<br>**Escenario 3:**<br>Given que ocurre un error<br>When realizo acción<br>Then veo mensaje de error.                                                                    | EP-09                         |
| US-10             | Editar foto de perfil            | Como usuario (turista o proveedor), quiero subir o cambiar mi foto de perfil.                                                  | **Escenario 1:**<br>Given que estoy en perfil<br>When hago clic en “Cambiar foto”<br>Then selecciono imagen.<br>**Escenario 2:**<br>Given que subo imagen válida<br>When guardo<br>Then se actualiza foto.<br>**Escenario 3:**<br>Given que intento archivo no permitido<br>When lo subo<br>Then veo error.                                                                                          | EP-10                         |
| US-11             | Activar modo oscuro              | Como usuario (turista o proveedor), quiero activar modo oscuro para una experiencia visual cómoda.                             | **Escenario 1:**<br>Given que estoy en cualquier página<br>When activo switch modo oscuro<br>Then interfaz cambia.<br>**Escenario 2:**<br>Given que cierro sesión<br>When vuelvo a ingresar<br>Then modo oscuro sigue activo.<br>**Escenario 3:**<br>Given que desactivo modo oscuro<br>When hago clic en switch<br>Then vuelve al modo claro.                                                       | EP-11                         |
| **US-12**         | Editar experiencia publicada     | Como proveedor turístico sostenible, quiero editar la información de una experiencia publicada para corregir detalles.         | **Escenario 1:**<br>Given que estoy en mi panel de experiencias<br>When hago clic en “Editar”<br>Then puedo modificar los datos.<br>**Escenario 2:**<br>Given que termino de editar<br>When guardo cambios<br>Then se actualiza la experiencia.<br>**Escenario 3:**<br>Given que hay errores<br>When intento guardar<br>Then veo los mensajes de validación.                                         | EP-12                         |
| **US-13**         | Editar perfil de proveedor       | Como proveedor turístico sostenible, quiero editar los datos de mi perfil para mantener la información al día.                 | **Escenario 1:**<br>Given que accedo a mi perfil<br>When hago clic en “Editar perfil”<br>Then puedo cambiar mis datos.<br>**Escenario 2:**<br>Given que realizo cambios<br>When hago clic en “Guardar”<br>Then se actualiza la información.<br>**Escenario 3:**<br>Given que hay datos inválidos<br>When guardo<br>Then veo errores de validación.                                                   | EP-13                         |
| **US-14**         | Editar redes sociales            | Como proveedor turístico sostenible, quiero actualizar mis redes sociales para que los turistas puedan contactarme fácilmente. | **Escenario 1:**<br>Given que entro a editar perfil<br>When agrego un enlace a una red<br>Then se guarda correctamente.<br>**Escenario 2:**<br>Given que ya tengo redes<br>When edito o elimino<br>Then se refleja en mi perfil.<br>**Escenario 3:**<br>Given que pongo un enlace inválido<br>When intento guardar<br>Then veo error.                                                                | EP-14                         |



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
