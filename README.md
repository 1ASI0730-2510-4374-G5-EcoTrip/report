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

3.2. User Stories.

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

## <a name="need-finding"></a> 2.3. Needfinding

Con el propósito de desarrollar una app que satisfaga las necesidades particulares de los usuarios, Ecotrip llevará a cabo la identificación del User persona, User Task Matrix, User Journey Maps y Empathy Mapping.

### <a name="user-personas"></a> 2.3.1. User Personas

Para esta sección se han creado personajes ficticios, cada uno diseñado para representar a un segmento específico de usuarios. La información utilizada para desarrollar estos "User personas" proviene de entrevistas previas realizadas a cada segmento objetivo. Estas entrevistas tenían como objetivo comprender mejor a las personas a las que se dirige la aplicación. Se consideraron datos demográficos, metas, motivaciones, frustraciones, marcas relacionadas con el tema de la aplicación, canales digitales más utilizados, entre otros. La creación de esta sección se llevó a cabo utilizando la plataforma UXPressia.

- **Segmento objetivo: Turista responsable**
  
![User Persona: Maria Fernandez](images/Maria.png)

- **Segmento objetivo: Proveedor turístico sostenible**
  
![User Persona: Pedro Rios](images/Pedro-Rios.png)


### <a name="user-task-matrix"></a> 2.3.2. User Task Matrix

En esta sección se presenta el User Task Matrix, una herramienta centrada en nuestros dos segmentos objetivos principales: el Turista Responsable y el Proveedor Turístico Sostenible. Esta matriz permite identificar y comparar las tareas clave que cada usuario realiza o espera realizar en la plataforma.


<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th><b><i>User Task Matrix</i></b></th>
    <th><b><i>Lucía (Turista Responsable)</i></b></th>
    <th><b><i>Pedro (Proveedor Turístico)</i></b></th>
  </tr>
  <tr>
    <td>Buscar experiencias sostenibles</td>
    <td style="text-align: center;"><i>Alta</i></td>
    <td style="text-align: center;"><i>No aplica</i></td>
  </tr>
  <tr>
    <td>Filtrar experiencias por ubicación/interés</td>
    <td style="text-align: center;"><i>Alta</i></td>
    <td style="text-align: center;"><i>No aplica</i></td>
  </tr>
  <tr>
    <td>Ver perfil y calificaciones del proveedor</td>
    <td style="text-align: center;"><i>Media</i></td>
    <td style="text-align: center;"><i>No aplica</i></td>
  </tr>
  <tr>
    <td>Reservar una experiencia</td>
    <td style="text-align: center;"><i>Alta</i></td>
    <td style="text-align: center;"><i>No aplica</i></td>
  </tr>
  <tr>
    <td>Crear y publicar una experiencia</td>
    <td style="text-align: center;"><i>No aplica</i></td>
    <td style="text-align: center;"><i>Alta</i></td>
  </tr>
  <tr>
    <td>Gestionar reservas recibidas</td>
    <td style="text-align: center;"><i>No aplica</i></td>
    <td style="text-align: center;"><i>Alta</i></td>
  </tr>
  <tr>
    <td>Recibir pagos por experiencias</td>
    <td style="text-align: center;"><i>No aplica</i></td>
    <td style="text-align: center;"><i>Alta</i></td>
  </tr>
  <tr>
    <td>Editar información de su perfil</td>
    <td style="text-align: center;"><i>Media</i></td>
    <td style="text-align: center;"><i>Media</i></td>
  </tr>
  <tr>
    <td>Chatear con otros usuarios</td>
    <td style="text-align: center;"><i>Media</i></td>
    <td style="text-align: center;"><i>Media</i></td>
  </tr>
  <tr>
    <td>Calificar experiencias</td>
    <td style="text-align: center;"><i>Alta</i></td>
    <td style="text-align: center;"><i>Baja</i></td>
  </tr>
  <tr>
    <td>Acceder a soporte o ayuda</td>
    <td style="text-align: center;"><i>Media</i></td>
    <td style="text-align: center;"><i>Media</i></td>
  </tr>
</table>



Esta clasificación facilita la priorización de características durante la construcción del Product Backlog, asegurando que se enfoquen primero las funcionalidades más relevantes para cada tipo de usuario. Además, el análisis comparativo permite visualizar las similitudes, diferencias, y oportunidades entre ambos perfiles.

### <a name="user-journey-mapping"></a> 2.3.3. User Journey Mapping

En esta sección, se describen en detalle los User Journey Mapping para dos perfiles distintos de usuarios de la plataforma de turismo responsable: los Turistas Ocasionales y los Turistas Frecuentes. Estos mapas proporcionan una visión integral del recorrido que cada tipo de usuario realiza dentro del sistema, desde el primer contacto con la plataforma hasta su uso habitual y su interacción continua con las funcionalidades ofrecidas. Se destacan las etapas clave, las emociones y necesidades específicas de cada usuario, para asegurar una comprensión clara de su experiencia global.

*Para Turista Responsable* 
- El recorrido de Lucía comienza motivado por su interés en descubrir experiencias sostenibles, auténticas y respetuosas con el entorno local. Su primer contacto con la plataforma suele darse a través de búsquedas en Google, recomendaciones de amigos o redes sociales.

- Una vez en la plataforma, explora experiencias disponibles, filtra por destino e impacto ambiental, y se registra para poder reservar. Lucía valora una navegación clara y confiable, con información transparente sobre sostenibilidad, seguridad y beneficios locales.
  
- Tras reservar y vivir la experiencia, suele dejar una reseña, evaluar al proveedor y, si su experiencia fue positiva, volver a utilizar la plataforma en futuros viajes. También le interesa guardar tours y recibir recomendaciones personalizadas según sus intereses.

*Para Proveedor Turístico Sostenible*
- El viaje de Pedro inicia cuando busca una forma de dar visibilidad a sus experiencias locales sin intermediarios tradicionales. Descubre la plataforma a través de un correo de invitación, recomendación de otro proveedor o una publicación en redes profesionales.
  
- Se registra y configura su perfil de proveedor. Publica sus experiencias detallando impacto social, logístico y ambiental. Necesita un panel sencillo para subir fotos, definir precios y gestionar reservas.
  
- Una vez que los turistas comienzan a reservar, Pedro gestiona la disponibilidad, responde consultas y organiza la logística. Después del tour, revisa las reseñas y ajusta su oferta según los comentarios. Busca construir una reputación confiable, ya que esto influye directamente en su visibilidad dentro de la plataforma.

Aunque tienen objetivos distintos, ambos comparten una motivación común: participar activamente en un turismo más consciente, auténtico y sostenible. Sus recorridos reflejan roles complementarios dentro del ecosistema de la plataforma.


- #### *Turista Responsable*
| Etapa                         | Acción del usuario (Turista ocasional)       | Emoción         | Canal                       | Oportunidad de mejora                           |
|------------------------------|----------------------------------------------|-----------------|-----------------------------|------------------------------------------------|
| Descubrimiento               | Encuentra la plataforma por redes o buscador | Curiosidad      | Web, redes sociales         | Mejorar posicionamiento SEO y contenido visual |
| Registro                     | Se registra para ver detalles de un tour     | Interés         | Página web                  | Simplificar el proceso de registro             |
| Exploración                  | Navega tours sin un objetivo claro           | Confusión       | Navegador                   | Sugerencias iniciales según localización       |
| Reserva                      | Selecciona y reserva un tour                 | Satisfacción    | Página de reservas          | Ofrecer asistencia en tiempo real              |
| Participación en el tour     | Asiste a la actividad                        | Entusiasmo      | Presencial                  | Recordatorios y checklist antes del tour       |
| Post-experiencia             | Puede dejar una reseña o no                  | Desconexión     | Email, web                  | Incentivar feedback con recompensas            |


- #### *Proveedor Turístico Sostenible*
| Etapa                         | Acción del usuario (Turista frecuente)       | Emoción         | Canal                       | Oportunidad de mejora                           |
|------------------------------|----------------------------------------------|-----------------|-----------------------------|------------------------------------------------|
| Descubrimiento               | Conoce la plataforma a través de otros guías, redes o invitaciones    | EntusCuriosidad, escepticismoasmo      | Facebook, WhatsApp, web                   | Campañas de captación con testimonios de otros proveedores                   |
| Registro                     | Se registra como proveedor, completa perfil y verifica identidad                                | Motivación, dudas técnicas       | Formulario, email de verificación                    | Proceso guiado, soporte en línea, validación rápida            |
| Publicación                  | Crea y publica una experiencia con fotos, texto y precio       | Creatividad, expectativa       | Dashboard proveedor             | Asistente de publicación, plantillas prediseñadas     |
| Gestión                      | Recibe reservas, responde dudas, organiza logística del tour                     | Organización, estrés  | Panel de reservas, mensajería                 | Sistema de alertas, app móvil para gestión rápida              |
| Entrega del tour     | Da la experiencia presencialmente                    | Entusiasmo      | WhatsApp, en persona                  | Confirmación previa, herramientas de check-in         |
| Retención          | Publica nuevas experiencias, busca subir su reputación           | Motivación, compromiso      | Email, plataforma           | Enviar reportes de desempeño, sugerencias automáticas            |


### <a name="empathy-mapping"></a> 2.3.4. Empathy Mapping

En esta sección se presenta el Empathy Mapping, una herramienta esencial para construir perfiles detallados de los dos principales user personas de la plataforma: Lucía, Turista Responsable, y Pedro, Proveedor Turístico Sostenible.

El objetivo es comprender de forma profunda sus pensamientos, emociones, comportamientos y motivaciones al interactuar con la plataforma. Para ello, se analiza lo que cada usuario ve, oye, dice, hace y siente, además de identificar sus dolores (pains) y beneficios esperados (gains).

Este ejercicio permite empatizar con sus contextos reales, facilitando el diseño de funcionalidades centradas en las verdaderas necesidades de cada segmento.

- **Segmento: Turista Responsable**

| Etapa                | Registro                           | Búsqueda de tours                           | Reserva                                   | Experiencia del tour                 | Revisión y seguimiento                   |
| -------------------- | ---------------------------------- | ------------------------------------------- | ----------------------------------------- | ------------------------------------ | ---------------------------------------- |
| **User goals**       | Acceder sin complicaciones         | Encontrar opciones auténticas y sostenibles | Reservar sin repetir pasos                | Vivir una experiencia local única    | Compartir su experiencia y evaluar       |
| **Touchpoints**      | Formulario simple, login social    | Buscador con filtros y etiquetas            | Pasarela intuitiva, historial de reservas | Confirmaciones, contacto con guía    | Email post-tour, botón para dejar reseña |
| **Customer Thought** | “Quiero empezar sin perder tiempo” | “¿Qué lugares realmente valen la pena?”     | “¿Mi pago está protegido?”                | “¿Será como lo prometieron?”         | “¿Cómo ayudo a otros viajeros como yo?”  |
| **Experience**       | 🙂 Fluida y amigable               | 🙂 Interesante y consciente                 | 😄 Confiable y directa                    | 😄 Auténtica y enriquecedora         | 😄 Gratificante y útil                   |
| **Ideas/Opps**       | Autocompletar desde Gmail          | Etiquetas como ‘eco-friendly’, ‘local’      | Pago en un clic con billetera digital     | Asistente virtual para dudas rápidas | Recompensa por dejar reseñas             |

- **Segmento: Proveedor Turístico Sostenible**

| Etapa                | Registro                             | Publicación de tour                  | Gestión de reservas                   | Ejecución del tour                      | Evaluación y continuidad                  |
| -------------------- | ------------------------------------ | ------------------------------------ | ------------------------------------- | --------------------------------------- | ----------------------------------------- |
| **User goals**       | Registrar su oferta fácilmente       | Describir su tour de forma atractiva | Organizar sin errores ni olvidos      | Dar una experiencia memorable y segura  | Recibir feedback, mejorar y seguir activo |
| **Touchpoints**      | Registro con ayuda paso a paso       | Panel con plantilla de tours         | Calendario, notificaciones, chat      | Checklist del día, contacto con turista | Plataforma de evaluación, estadísticas    |
| **Customer Thought** | “¿Será complicado llenar todo esto?” | “¿Mi tour llama la atención?”        | “¿Todo está confirmado y claro?”      | “¿Los turistas estarán satisfechos?”    | “¿Estoy creciendo en la plataforma?”      |
| **Experience**       | 🙂 Simple y bien guiada              | 🙂 Creativa pero necesita apoyo      | 🙂 Organizada y clara                 | 😄 Profesional y con buen feedback      | 😄 Motivadora y constructiva              |
| **Ideas/Opps**       | Tutorial interactivo                 | Asistente para redacción atractiva   | App móvil para gestión en tiempo real | Confirmación de llegada del turista     | Tips automáticos para mejorar perfil      |

### <a name="as-is"></a> 2.3.5. As-is Scenario Mapping
En esta sección se presenta el As-Is Scenario Mapping para cada uno de los segmentos objetivos identificados: Turista Responsable y Proveedor Turístico Sostenible. Este análisis tiene como objetivo visualizar cómo estos usuarios interactúan actualmente con plataformas digitales al planificar, ofrecer o reservar experiencias de viaje, y así detectar oportunidades de mejora, frustraciones comunes y necesidades no cubiertas.

Para este mapeo se han considerado cinco fases clave del recorrido del usuario: Descubrimiento, Evaluación, Reserva, Experiencia y Seguimiento. En cada etapa se identifican acciones típicas, aspectos positivos, dificultades experimentadas y oportunidades que pueden guiar el diseño de funcionalidades relevantes para nuestra plataforma de turismo responsable.

El análisis se basa en entrevistas y observaciones realizadas durante la fase de investigación, complementadas con supuestos validados por referencias externas, permitiendo entender el contexto actual y orientar decisiones estratégicas centradas en el usuario.


*As-is Scenario mapping: Turista Responsable*
  
  ![As-Is: frecuentes](images/Scenario-Mapping1.png)

*As-is Scenario mapping: Proveedor Turístico Sostenible*
  
  ![As-Is: frecuentes](images/Scenario-Mapping2.png)

