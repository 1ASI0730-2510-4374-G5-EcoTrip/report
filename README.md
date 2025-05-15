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

---

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

Se realizo el diagram de clase

<div align="center">
  <img src="./img/Class_Diagrams.PNG" alt="ClassDiagrams" width="100%" />
</div>

4.7.2. Class Dictionary.

### 1. User Bounded Context

#### User (Aggregate)

La clase **User** contiene los datos de autenticación y los detalles generales de un usuario en la plataforma (ya sea un viajero o proveedor).

#### Atributos:

- `id: int` – Identificador único del usuario.
- `name: String` – Nombre completo del usuario.
- `email: String` – Correo electrónico del usuario, utilizado para el inicio de sesión.
- `password: String` – Contraseña cifrada del usuario.
- `preferredLanguage: String` – Idioma preferido del usuario para personalizar la interfaz.

#### Métodos:

- `register()` – Guarda los datos del usuario en la base de datos al momento de registrarse.
- `login()` – Verifica las credenciales del usuario para autenticarlo.
- `changeLanguage(language: String)` – Permite cambiar el idioma preferido del usuario.

### 2. Provider Bounded Context

#### Provider (Aggregate)

La clase **Provider** representa a un proveedor de servicios, como un eco-alojamiento o un guía turístico.

#### Atributos:

- `id: int` – Identificador único del proveedor.
- `name: String` – Nombre del negocio o servicio del proveedor.
- `type: String` – Tipo de proveedor, como "Lodge" (alojamiento) o "TourGuide" (guía turístico).
- `isVerified: boolean` – Indica si el proveedor ha sido verificado y aprobado por EcoTrip.

#### Métodos:

- `registerProvider()` – Crea un perfil nuevo para un proveedor en el sistema.
- `verify()` – Marca al proveedor como verificado para que pueda ofrecer sus servicios.

### Guide (Entidad, hereda de Provider)

La clase **Guide** representa a un guía turístico certificado.

#### Atributos:

- `languages: List<String>` – Idiomas que habla el guía (por ejemplo, ["Español", "Inglés"]).
- `specialty: String` – Especialidad del guía, como "Fauna" o "Patrimonio Cultural".
- `isAvailable: boolean` – Disponibilidad actual del guía para aceptar nuevas reservas.

#### Métodos:

- `acceptBooking(bookingId: int)` – Confirma la reserva realizada por un usuario.

### 3. Experience Bounded Context

#### Experience (Agregado)

La clase **Experience** representa una actividad de turismo sostenible que puede ser reservada por los usuarios.

#### Atributos:

- `id: int` – Identificador único de la experiencia.
- `name: String` – Nombre de la actividad (por ejemplo, "Caminata por la selva").
- `price: float` – Precio por persona para la experiencia.
- `maxCapacity: int` – Número máximo de participantes permitidos.
- `type: String` – Tipo de experiencia, como "Aventura" o "Cultural".

#### Métodos:

- `book(user: User)` – Crea una nueva reserva para un usuario.
- `updatePrice(newPrice: float)` – Permite actualizar el precio de la experiencia.

#### Location (Objeto de Valor)

La clase **Location** describe los detalles geográficos de una experiencia.

#### Atributos:

- `city: String` – Ciudad más cercana a la experiencia.
- `country: String` – País en el que se realiza la experiencia.
- `coordinates: String` – Coordenadas geográficas (latitud/longitud) del lugar.

#### Métodos:

- `getCoordinates():String` – Devolver las coordenadas

#### Itinerary (Agregado)

La clase **Itinerary** representa el itinerario de un viaje, que incluye una lista de experiencias que el usuario ha planeado realizar.

#### Atributos:

- `id: int` – Identificador único del itinerario.
- `name: String` – Nombre del itinerario (por ejemplo, "Aventura en la Selva").
- `startDate: Date` – Fecha de inicio del itinerario.
- `endDate: Date` – Fecha de finalización del itinerario.
- `budget: float` – Presupuesto total disponible para el itinerario.
- `experiences: List<Experience>` – Lista de experiencias reservadas para este itinerario.

#### Métodos:

- `addExperience(experience: Experience)` – Añade una nueva experiencia al itinerario.
- `removeExperience(experienceId: int)` – Elimina una experiencia del itinerario dado su identificador.
- `generateRecommendations()` – Genera una lista de experiencias recomendadas basadas en el itinerario.
- `calculateTotalCost()` – Calcula el costo total del itinerario, sumando los precios de todas las experiencias asociadas.

### 4. Booking Bounded Context

#### Booking (Agregado)

La clase **Booking** representa una reserva confirmada realizada por un usuario para una experiencia.

#### Atributos:

- `id: int` – Identificador único de la reserva.
- `status: String` – Estado de la reserva, que puede ser "Confirmada" o "Cancelada".
- `totalAmount: float` – Monto total de la reserva, incluyendo cualquier tarifa adicional.

#### Métodos:

- `cancel()` – Aplica la política de cancelación para realizar reembolsos según las reglas establecidas.

#### CancellationPolicy (Objeto de Valor)

La clase **CancellationPolicy** define las reglas para la cancelación de reservas.

#### Atributos:

- `maxCancellationDays: int` – El número máximo de días antes de la fecha de la experiencia para cancelar y obtener un reembolso completo.
- `refundPercentage: float` – Porcentaje de reembolso disponible si la cancelación se realiza después del período permitido.

### 5. Review Bounded Context

#### Review (Entidad)

La clase **Review** permite a los usuarios dejar comentarios y calificaciones sobre una experiencia.

#### Atributos:

- `environmentalScore: int` – Calificación de sostenibilidad de la experiencia (de 1 a 5).
- `culturalScore: int` – Calificación del impacto cultural de la experiencia.
- `comment: String` – Comentario escrito por el usuario sobre la experiencia.

#### Métodos:

- `calculateFinalScore()` – Calcula la calificación final promediando todas las puntuaciones recibidas (sostenibilidad, impacto cultural, etc.).

  4.8. Database Design.

  4.8.1. Database Diagram.

<div align="center">
  <img src="./img/Database_Diagram.PNG" alt="DatabaseDiagram" width="100%" />
</div>

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
