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

Con el objetivo de asegurar coherencia visual y comunicacional a lo largo de todos los puntos de contacto con los usuarios, se define una guía de estilo centralizada para el equipo de diseño y desarrollo. Esta guía permitirá mantener una presentación consistente tanto en plataformas web como móviles, alineada con los valores de sostenibilidad, inclusión y responsabilidad promovidos por EcoTrip.

4.1.1. General Style Guidelines.

Aquí se explica las decisiones y referencias visuales sobre conceptos generales básicos como Branding, Typography, Colors y Spacing, así como las dimensiones a adoptar para el tono de comunicación y lenguaje aplicado (Divertido/Serio, Formal/Casual, Respetuoso/Irreverente, Entusiasta/Sereno). Puede tomarse como referencia un Design System existente, sobre el cual se puede realizar adaptaciones.

#### Branding
EcoTrip comunica sostenibilidad, autenticidad y conexión con la naturaleza. Su identidad visual transmite cercanía, confianza y respeto cultural. El logotipo utiliza una tipografía moderna y amigable, evocando caminos y hojas que representan el viaje y la ecología.

#### Typography
Se utilizan fuentes limpias y legibles:

- **Primaria:** *Poppins* – utilizada para títulos y navegación, aporta modernidad y claridad.
- **Secundaria:** *Open Sans* – aplicada en cuerpos de texto, facilita la lectura prolongada.

Ambas fuentes están disponibles en Google Fonts, lo que facilita su integración en entornos web y móviles.

#### Colors
La paleta de colores se inspira en la naturaleza, transmitiendo calma y responsabilidad ambiental:

- **Verde Bosque (#4CAF50):** color principal que representa sostenibilidad y acción responsable.
- **Verde Lima (#C5E1A5):** secundario, aporta energía y frescura.
- **Beige Tierra (#FFF8E1):** fondo neutro y cálido, amigable a la vista.
- **Gris Suave (#757575):** utilizado en textos secundarios o de soporte.
- **Blanco (#FFFFFF):** proporciona limpieza visual y contraste.

#### Spacing
Se define una escala modular de espaciado basada en múltiplos de 8px (8, 16, 24, 32, etc.), lo cual facilita la organización de layouts consistentes y balanceados visualmente.

#### Tono y Lenguaje
EcoTrip adopta un lenguaje accesible y empático:

- **Tono:** cercano, optimista y comprometido con el usuario.
- **Lenguaje:**  
  - Entre **casual y respetuoso**, evitando tecnicismos innecesarios.  
  - **Entusiasta**, pero no invasivo.  
  - Inspirador y culturalmente sensible, especialmente en interacciones con comunidades locales.

**Ejemplo de voz:**

- ✅ “¿Listo para vivir una experiencia inolvidable en la selva amazónica?”
- ❌ “Reserva ya o te lo pierdes.”

---

4.1.2. Web Style Guidelines.

En esta sección se explica e ilustra las decisiones sobre los estándares visuales y de interacción para responsive web interfaces.

#### Diseño Responsive
EcoTrip utiliza un diseño adaptable que se ajusta a distintos dispositivos: computadoras, tablets y smartphones, manteniendo la coherencia visual.

#### Botones

- Forma: redondeados (12px de radio).
- Colores: uso del verde principal (#4CAF50) con texto blanco.
- Estados: `hover`, `active` y `disabled` definidos claramente.
- Iconografía: acompañados de íconos solo cuando añaden significado.

#### Navegación

- Barra superior fija con logo alineado a la izquierda.
- Enlaces principales: “Explorar”, “Mi Plan”, “Perfil”.
- Comportamiento: la barra cambia de color ligeramente al hacer scroll.

#### Accesibilidad

- Contraste de color superior a 4.5:1.
- Tipografía escalable sin romper diseño.
- Navegación con teclado y etiquetas `aria-label` para elementos interactivos.

#### Animaciones

- Transiciones suaves entre secciones (`0.3s a 0.5s`).
- Efectos sutiles de entrada y desplazamiento en los elementos clave.
- Sin uso excesivo de animaciones para no afectar el rendimiento ni distraer al usuario.

#### Sustento de diseño

Se toman como referencia principios del **Material Design** de Google y el sistema de diseño de **Airbnb**, por su enfoque en experiencias culturales, accesibilidad y claridad visual. Además, se adaptan las guías al contexto de turismo sostenible, garantizando:

- **Consistencia** visual entre pantallas.
- **Escalabilidad** del diseño a nuevas funcionalidades.
- **Usabilidad** y accesibilidad para todo tipo de usuarios.

---


4.2. Information Architecture.

En esta sección se definen las decisiones de arquitectura de información que dirigen cómo se organizará el contenido en las experiencias web de **EcoTrip**, incluyendo el Landing Page y futuras aplicaciones. El objetivo principal es garantizar que los visitantes y usuarios se adapten de manera intuitiva a la funcionalidad de cada producto, puedan encontrar fácilmente lo que necesitan y logren una navegación fluida y satisfactoria.

Las propuestas de arquitectura están diseñadas siguiendo principios de usabilidad, claridad y accesibilidad, abordando los siguientes componentes:

- **Organization Systems**
- **Labeling Systems**
- **SEO Tags and Meta Tags**
- **Searching Systems**
- **Navigation Systems**

4.2.1. Organization Systems.

Se establecen las siguientes decisiones sobre la organización del contenido:

####  Visual Hierarchy
Se aplicará una **jerarquía visual clara** en todas las páginas, priorizando:

- **Primero:** Secciones principales como "Explorar", "Mi Plan", "Reservas".
- **Luego:** Subcategorías como tipos de experiencias (Voluntariado, Ecotours, Aventura).
- **Finalmente:** Información detallada de cada actividad o guía.

El tamaño, color y peso de los elementos gráficos ayudarán a guiar la atención del usuario hacia lo más relevante.

####  Secuencial Organization
En procesos como:

- **Registro de Proveedores**
- **Creación de Itinerarios Personalizados**
- **Proceso de Reserva**

Se utilizará una organización **secuencial paso a paso**, facilitando al usuario completar acciones en un orden lógico y guiado.

Ejemplo de pasos en creación de itinerario:
1. Seleccionar actividades.
2. Escoger hospedaje.
3. Confirmar transporte.
4. Guardar y visualizar el plan.

####  Matricial Organization
Para listas de experiencias o actividades disponibles, se aplicará un modelo **matricial**, donde el usuario puede comparar varias opciones al mismo nivel mediante filtros (por precio, popularidad, impacto ambiental, tipo de actividad).

---

####  Esquemas de Categorización

Según el tipo de contenido, se emplearán:

- **Por tópicos:** experiencias agrupadas en categorías como "Aventura", "Cultural", "Voluntariado", "Ecológico".
- **Según audiencia:** filtrado de experiencias recomendadas para "Turistas Frecuentes" y "Turistas Ocasionales".
- **Cronológico:** para visualizar actividades próximas a realizarse (eventos en fechas específicas).
- **Alfabético:** listado de proveedores o guías por nombre, en catálogos extensos.

Estos esquemas permiten un acceso eficiente y adaptado a diferentes formas de búsqueda del usuario.

---

4.2.2. Labeling Systems.

La representación de los datos en la plataforma busca ser clara, intuitiva y evitar confusión. Para ello se establecen las siguientes directrices de etiquetado:

#### 🔹 Principios de Etiquetado

- Utilizar un **mínimo número de palabras**.
- Preferir términos **comunes** y **fáciles de comprender**.
- Mantener **consistencia** en la terminología a lo largo del sitio.

#### 🔹 Etiquetas principales propuestas

| Área                | Etiqueta asignada    | Propósito                          |
|---------------------|----------------------|------------------------------------|
| Exploración          | "Explorar"           | Navegar entre experiencias.        |
| Planificación        | "Mi Plan"            | Acceso al itinerario personalizado.|
| Reservas             | "Mis Reservas"       | Historial de reservas confirmadas. |
| Registro de Proveedores | "Conviértete en proveedor" | Registro de nuevos servicios. |
| Búsqueda             | "Buscar experiencias" | Entrada de texto para buscar.     |
| Perfil               | "Mi Perfil"          | Datos personales del usuario.      |

Además, las etiquetas dentro de los filtros utilizarán palabras clave simples como:

- "Tipo de experiencia"
- "Duración"
- "Nivel de impacto ecológico"
- "Idioma del guía"

Esto facilita al usuario la interpretación inmediata de las opciones disponibles.

---

4.2.3. SEO Tags and Meta Tags

Para optimizar la visibilidad y accesibilidad de EcoTrip en motores de búsqueda, se establecen los siguientes **SEO Tags** y **Meta Tags** que serán implementados tanto en el **Landing Page** como en la **Web Application**:

| Página             | Title                                    | Meta Description                                              | Meta Keywords                         | Author         |
|--------------------|------------------------------------------|---------------------------------------------------------------|---------------------------------------|----------------|
| Landing Page       | EcoTrip - Vive Experiencias Sostenibles  | Descubre y reserva experiencias de turismo ecológico auténtico alrededor del mundo con EcoTrip. | ecoturismo, turismo sostenible, experiencias eco, viajes responsables | Equipo EcoTrip |
| Web Application - Home | EcoTrip App - Tu Viaje Responsable Comienza Aquí | Organiza, personaliza y reserva experiencias sostenibles de forma sencilla y segura. | crear itinerario ecológico, plan de viaje sostenible, actividades eco | Equipo EcoTrip |
| Web Application - Perfil Usuario | EcoTrip - Mi Perfil | Gestiona tus datos, itinerarios y reservas ecológicas en EcoTrip. | perfil usuario EcoTrip, reservas turismo ecológico | Equipo EcoTrip |


4.2.4. Searching Systems.

Para mejorar la capacidad de búsqueda dentro del sitio y aplicación, se implementarán sistemas de búsqueda claros y efectivos.

####  Tipos de búsqueda ofrecidos

- **Búsqueda Global (Header Search Box):**
  - Visible en todas las páginas principales.
  - Permite buscar experiencias, guías o categorías.
  - Autocompletado con sugerencias relevantes.

- **Filtros de búsqueda en "Explorar experiencias":**
  - **Tipo de experiencia** (Voluntariado, Ecotour, Aventura, Cultura).
  - **Duración** (1 día, 2-5 días, +7 días).
  - **Nivel de impacto ecológico** (Certificado eco, Responsable, Sugerido).
  - **Ubicación** (continente, país o región).
  - **Idioma del guía**.

- **Búsqueda específica en el perfil de proveedores:**
  - Por nombre del proveedor.
  - Por calificación de usuarios.

####  Presentación de resultados

- **Resultados dinámicos:** a medida que se aplica un filtro o búsqueda, el listado se actualiza en tiempo real.
- **Organización matricial:** los resultados se mostrarán en tarjetas (cards) que incluyen:
  - Imagen de la experiencia o proveedor.
  - Nombre y categoría.
  - Valoración promedio.
  - Botón de acción (Agregar a plan, Reservar).

- **Resultados ordenables:** por relevancia, precio, valoración o fecha de disponibilidad.

---

4.2.5. Navigation Systems.

La navegación del producto EcoTrip está diseñada para guiar a los usuarios de manera fluida, asegurando que encuentren lo que buscan de manera natural e intuitiva.

####  Principios de navegación
- **Navegación principal fija:** barra superior presente en todo momento, accesible desde cualquier parte de la aplicación.
- **Accesos rápidos:** a las secciones principales: "Explorar", "Mi Plan", "Reservas", "Perfil".
- **Navegación progresiva:** acciones importantes (crear itinerario, reservar, contactar guía) se presentan en momentos contextuales apropiados, evitando saturación.
- **Pistas visuales:** utilización de colores, íconos y estados activos en menús para indicar dónde se encuentra el usuario.
- **Breadcrumbs:** en procesos secuenciales como la creación de itinerarios, para mostrar al usuario en qué etapa se encuentra.

####  Flujo de navegación en Landing Page

1. El visitante accede a la **Landing Page**.
2. Puede navegar rápidamente a:
   - Explorar experiencias
   - Conocer más sobre EcoTrip
   - Registrarse como turista o proveedor
3. Se invita a la acción con CTA claros como **"Empieza tu viaje responsable"**.

####  Flujo de navegación en la Web Application

1. Menú principal con íconos + texto (Inicio, Explorar, Mi Plan, Perfil).
2. En "Explorar", se filtra experiencias y se agregan al plan.
3. Desde "Mi Plan", se visualiza el itinerario y se procede a reservar.
4. En "Perfil", se gestionan datos, historial y configuraciones.

---

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
