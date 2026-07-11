![Logo UPC](report/assets/UPC_logo_transparente.png)
 
<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>
 
<h3 align="center">Carrera de Ingeniería de Software</h3>
 
<h3 align="center">1ASI0729</h3>
 
<h3 align="center">Desarrollo de Aplicaciones Open Source</h3>
 
<br>
<h4 align="center">NRC</h4>
<h4 align="center">11959</h4>
 
<br>
<h2 align="center">Informe del Trabajo Final</h2>
 
<br>
<h4 align="center">Docente</h4>
<h4 align="center">Mori Paiva, Hugo Allan</h4>
 
<br>
<h4 align="center">Equipo</h4>
<h4 align="center">AndesSmart</h4>
 
<br>
<h4 align="center">Proyecto</h4>
<h4 align="center">AgroTrack</h4>
 
<br>
## Integrantes
 
| Código      | Apellidos y Nombres                          |
|-------------|-----------------------------------------------|
| U20241A267  | Alfaro Mallma, Alberto Joaquin                 |
| U202120011  | Martínez Gaona, Pablo Afranio                  |
| U202324623  | Quispe Perez, Eder Edu                         |
| U20241A827  | Rodriguez Rojas, Miler Alexander               |
| U202323350  | Velasquez Laquihuanaco, Eduardo David          |
 
<br>
<h4 align="center">Período 202610</h4>
<h4 align="center">Abril 2026</h4>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| AV1 | 26/04/2026 | Alberto Joaquin Alfaro Mallma, Pablo Afranio Martínez Gaona, Eder Edu Quispe Perez, Miler Alexander Rodriguez Rojas, Eduardo David Velasquez Laquihuanaco | Para esta primera entrega, elaboramos los cinco capítulos iniciales del informe y desarrollamos la versión inicial del landing page de AgroTrack. |
| TB1 | 09/05/2026 | Alberto Joaquin Alfaro Mallma, Pablo Afranio Martínez Gaona, Eder Edu Quispe Perez, Miler Alexander Rodriguez Rojas, Eduardo David Velasquez Laquihuanaco | Para esta segunda entrega, se incorporó la sección 5.2.2 correspondiente al Sprint 2, incluyendo Sprint Planning, Aspect Leaders and Collaborators, Sprint Backlog, Development Evidence, Execution Evidence, Services Documentation Evidence, Software Deployment Evidence y Team Collaboration Insights. Asimismo, se desplegó una nueva versión del Landing Page y la primera versión del Frontend Web Application. Se corrigieron y mejoraron los Mock-ups y artefactos de entregas previas en base a la retroalimentación recibida. |
| AV2 | 20/06/2026 | Alberto Joaquin Alfaro Mallma, Pablo Afranio Martínez Gaona, Eder Edu Quispe Perez, Miler Alexander Rodriguez Rojas, Eduardo David Velasquez Laquihuanaco | Para esta tercera entrega, se incorporó la sección 5.2.3 correspondiente al Sprint 3, incluyendo Sprint Planning, Aspect Leaders and Collaborators, Sprint Backlog, Development Evidence, Execution Evidence, Services Documentation Evidence, Software Deployment Evidence y Team Collaboration Insights. Se implementó la primera versión del Web Service (RESTful API) de AgroTrack con Spring Boot bajo arquitectura DDD, cubriendo los bounded contexts de Identity, Farming, Soil Monitoring, Alerts y Support & Dashboard. El backend fue desplegado en Render con base de datos MySQL en Aiven. |
| TB2 | 10/07/2026 | Alberto Joaquin Alfaro Mallma, Eder Edu Quispe Perez, Miler Alexander Rodriguez Rojas, Eduardo David Velasquez Laquihuanaco | Para esta cuarta y última entrega, se incorporó la sección 5.2.4 correspondiente al Sprint 4, incluyendo Sprint Planning, Aspect Leaders and Collaborators, Sprint Backlog, Development Evidence, Execution Evidence y Services Documentation Evidence. Se implementó y desplegó el bounded context de Identity & Access Management, incorporando autenticación mediante sign-up/sign-in, gestión de roles y protección JWT sobre los endpoints de perfil de negocio, completando así los cinco bounded contexts planeados en el diseño original del backend. Se realizó el versionado semántico y la publicación de releases en GitHub para los repositorios de Landing Page, Web Application y Web Services. Finalmente, se redactó la sección de Conclusiones y Recomendaciones del informe, contrastando los Problem Statements, Assumptions e Hypothesis Statements planteados en el Lean UX Canvas con los resultados de las validaciones de usabilidad realizadas con usuarios reales durante el Sprint 3, y se elaboró la presentación de cierre resumiendo el trabajo de los cuatro sprints del proyecto. |
 


<br>
<br>

# Project Report Collaboration Insights

El Project Report del equipo se encuentra alojado en el repositorio de informes
dentro de la organización de GitHub del equipo:

- **Organización de GitHub:** https://github.com/AgroTrack-Project
- **Repositorio del Project Report:** https://github.com/AgroTrack-Project/report.git

El informe se elaboró de manera colaborativa utilizando Git y GitHub como
plataforma de control de versiones. Cada integrante trabajó las secciones
asignadas y registró sus aportes mediante commits al repositorio del informe,
lo cual queda evidenciado en los analíticos de colaboración de GitHub y en el
Registro de Versiones del Informe. A continuación, se describe el desarrollo
de las actividades por cada entrega.

![Foto de la colaboración](report/assets/contributors.png)


---

### Entrega AV1

Durante la primera entrega, el equipo se organizó mediante reuniones de
coordinación para distribuir los capítulos iniciales del informe. Las
actividades se desarrollaron entre el 14 y el 24 de abril, y la distribución
del trabajo fue la siguiente:

| Integrante | Tareas Designadas |
|------------|-------------------|
| Miler Alexander Rodriguez Rojas | Elaboró la carátula, el registro de versiones, la tabla de Collaboration Insights, el Student Outcome, la descripción del startup, los perfiles de los integrantes, la sección de antecedentes y problemática, los wireframes y mock-ups de la Landing Page, y el Big Picture Event Storming |
| Alberto Joaquin Alfaro Mallma | Desarrolló la sección de competidores, el análisis competitivo, las estrategias y tácticas frente a competidores, el diseño de entrevistas, las consideraciones metodológicas, el registro de las tres primeras entrevistas, el registro de la 4ta entrevista, y los Web Applications Wireframes, Mock-ups, User Flow Diagrams y Prototyping |
| Eduardo David Velasquez Laquihuanaco | Elaboró los Lean UX Problem Statements, Assumptions, Hypothesis Statements y el Lean UX Canvas; los User Stories, el Impact Mapping y el Product Backlog; las secciones de Software Configuration Management, Source Code Management y los diagramas de arquitectura (Context, Components), Class Diagrams y Database Diagrams; además del Design-Level EventStorming |
| Eder Edu Quispe Perez | Elaboró los User Persona, los Style Guidelines, el registro de la 5ta entrevista, el análisis de entrevistas, los User Task Matrix, el Labeling Systems, los SEO Tags and Meta Tags, los Searching Systems, los Navigation Systems, la introducción, las secciones de Source Code Style Guide & Coding Conventions, Software Deployment Configuration, Landing Page, Services & Applications Implementation y el Sprint 1; junto con los User Journey Mapping, los Empathy Mapping y el Ubiquitous Language |


**Evidencias de colaboración — AV1:**

*Analíticos de colaboración del repositorio:*

![Foto de la AV1](report/assets/AV1-1.png)

![Foto de la AV1](report/assets/AV1-2.png)

![Foto de la AV1](report/assets/AV1-3.png)

---

### Entrega TB1

Para la segunda entrega, el equipo se enfocó en corregir las observaciones
recibidas en la entrega anterior y en completar las secciones de diseño y
arquitectura de la solución. Las actividades se desarrollaron entre el 5 y
el 25 de mayo, con la siguiente participación:

| Integrante | Tareas Designadas |
|------------|-------------------|
| Eduardo David Velasquez Laquihuanaco | Corrigió el contenido del Capítulo 1, el Lean UX Process, los User Journey Mapping, los Empathy Maps, los Lean UX Problem Statements y los Assumptions; y añadió el Software Architecture Context Diagram, los Container Diagrams y los Components Diagrams |
| Alberto Joaquin Alfaro Mallma | Corrigió los Segmentos Objetivo, el Startup Profile, la sección de Competidores, el Registro de Versiones, el Project Report Collaboration Insights, las entrevistas, el Big Picture Event Storming y el Ubiquitous Language; actualizó los User Stories y añadió el Web Applications Prototyping, el Sprint 2 y los Landing Page Wireframes y Mock-ups |
| Miler Alexander Rodriguez Rojas | Corrigió el Solution Profile, la sección de Antecedentes y problemática, los User Stories, el Impact Mapping y el Product Backlog; actualizó los User Goals y el Software Configuration Management; además añadió la tabla de Software Configuration Management, el Source Code Management y el Software Deployment Configuration |
| Eder Edu Quispe Perez | Participó en la actualización de las secciones de implementación y documentación de la Landing Page y servicios iniciadas en la entrega anterior, y añadió los Web Applications User Flow Diagrams |



**Evidencias de colaboración — TB1:**

*Analíticos de colaboración del repositorio:*

![Foto de la colaboración](report/assets/TB1-COLABORATION.png)

---

### Entrega AV2

En la entrega final, el equipo completó el Sprint 3, las entrevistas de
validación, las evaluaciones heurísticas y las evidencias de despliegue,
además de realizar una revisión integral del documento. Las actividades se
desarrollaron entre el 26 de mayo y el 21 de junio, con la siguiente
participación:

| Integrante | Tareas Designadas |
|------------|-------------------|
| Eduardo David Velasquez Laquihuanaco | Corrigió los Sprint Backlog 1 y 2, el Development, Execution y Services Documentation Evidence for Sprint Review y el Design-Level EventStorming; actualizó las Technical Stories, la carátula, el video About The Team, los Sprint Planning y el Big Picture Event Storming; y añadió el Sprint 3, la 3ra entrevista de validación, los Validation Interviews y el Video About The Product |
| Alberto Joaquin Alfaro Mallma | Actualizó la Configuración de Firebase y la Publicación de la aplicación, los links de las entrevistas 1 y 3, y el Design-Level Event Storming; y añadió las secciones de Software Deployment Evidence y Services Documentation Evidence for Sprint Review, así como la 2da entrevista de evaluación |
| Eder Edu Quispe Perez | Añadió la 1ra entrevista de validación, las Evaluaciones según heurísticas y el video de demostración; actualizó el Sprint 3, el Execution Evidence for Sprint Review, el registro de la 2da entrevista y corrigió el 1er User Persona |
| Miler Alexander Rodriguez Rojas | Añadió la 4ta entrevista de validación, los Team Collaboration Insights de los Sprints 1, 2 y 3, el Student Outcome; corrigió la tabla de contenidos, el Hypothesis Statement y el Registro de Versiones del Informe en varias iteraciones; y actualizó los Lean UX Hypothesis Statements, el Lean UX Canvas, los segmentos objetivo, las estrategias y tácticas frente a competidores, las entrevistas, el glosario, el Product Backlog, la sección de Information Architecture, los Organization Systems, los Labeling Systems, la Landing Page UI Design y la Bibliografía |



**Evidencias de colaboración — AV2:**

*Analíticos de colaboración del repositorio:*

![Foto de la colaboración](report/assets/AV2-1.png)

![Foto de la colaboración](report/assets/AV2-2.png)

---

### Entrega TB2

Para esta entrega, el equipo desarrolló el Sprint 4, el cual se centró en la
mejora integral del Project Report atendiendo las indicaciones y observaciones
brindadas por el docente en las entregas anteriores. Las actividades se
desarrollaron entre el 21 de junio y el 8 de julio, e incluyeron la corrección
de secciones observadas, la actualización de evidencias y la consolidación del
Registro de Versiones del Informe. La participación de los integrantes fue la
siguiente:

| Integrante | Tareas Designadas |
|------------|-------------------|
| Miler Alexander Rodriguez Rojas | Corrigió la tabla de contenidos, el Hypothesis Statement y la tabla del Registro de Versiones del Informe en sucesivas iteraciones; añadió los Team Collaboration Insights de los Sprints 1, 2 y 3 y el Student Outcome; y actualizó los Lean UX Hypothesis Statements, el Lean UX Canvas, la sección de segmentos objetivo, las estrategias y tácticas frente a competidores, las entrevistas, el glosario, el Product Backlog, la sección de Information Architecture, los Organization Systems, los Labeling Systems, la sección de Landing Page UI Design y la Bibliografía |
| Alberto Joaquin Alfaro Mallma | Añadió el Software Deployment Evidence for Sprint Review y consolidó el Registro de Versiones del Informe añadiendo las versiones 0.1 a la 0.56; y actualizó los links de las entrevistas 1 y 3 |
| Eder Edu Quispe Perez | Actualizó el registro de la 2da entrevista y el Design-Level Event Storming, y corrigió el 1er User Persona conforme a las observaciones recibidas |
| Eduardo David Velasquez Laquihuanaco | Actualizó la carátula, el video About The Team, los Sprint Planning y el Big Picture Event Storming |

<br>

**Evidencias de colaboración — TB2:**

<br>

![Foto de la colaboración](report/assets/contributors-sprint-4-report-pulse.png)

![Foto de la colaboración](report/assets/contributors-sprint-4-report.png)


---


<br>
<br>

# Índice

# Capítulo I: Introducción
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

# Capítulo II: Requirements Elicitation & Analysis
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
- [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

# Capítulo III: Requirements Specification
- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

# Capítulo IV: Product Design
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
  - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
  - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
  - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagrams](#481-database-diagrams)

# Capítulo V: Product Implementation, Validation & Deployment
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.2.2. Sprint 2](#522-sprint-2)
    - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
    - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
    - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
    - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
    - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
    - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
    - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
    - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
  - [5.2.3. Sprint 3](#523-sprint-3)
    - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
    - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
    - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
    - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
    - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
    - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
    - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
    - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
  - [5.2.4. Sprint 4](#524-sprint-4)
    - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
    - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
    - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
    - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
    - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
    - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
    - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
    - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
- [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
- [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

# Conclusiones
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Validación de Problem Statements, Assumptions e Hypothesis Statements](#validación-de-problem-statements-assumptions-e-hypothesis-statements)
  - [Conclusiones por Sprint](#conclusiones-por-sprint)
    - [Sprint 1 – Investigación, problema y Landing Page](#sprint-1--investigación-problema-y-landing-page)
    - [Sprint 2 – Desarrollo del Frontend (Web Application)](#sprint-2--desarrollo-del-frontend-web-application)
    - [Sprint 3 – Desarrollo del Backend (Web Services)](#sprint-3--desarrollo-del-backend-web-services)
    - [Sprint 4 – Módulo IAM y consolidación del backend](#sprint-4--módulo-iam-y-consolidación-del-backend)
  - [Recomendaciones (Roadmap post-curso)](#recomendaciones-roadmap-post-curso)
- [Video About-the-Team](#video-about-the-team)

- [Bibliografía](#bibliografía)

# Anexos
- [Repositorios de Código Fuente](#repositorios-de-código-fuente)
- [Productos Desplegados](#productos-desplegados)
- [Gestión del Proyecto – Tableros Trello](#gestión-del-proyecto--tableros-trello)
- [Videos del Proyecto](#videos-del-proyecto)



<br>
<br>


# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET - EAC - Student Outcome 3, cuyo criterio es la capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET - EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | <br>**Alberto Joaquin Alfaro Mallma** <br> **AV1:** Realizó la entrevista N°6 al empresario agrícola Cristofer Ordalla (Piura), adaptando el lenguaje técnico a un perfil no especializado en tecnología para obtener información sobre la gestión de sus parcelas y sus expectativas frente a una solución digital. <br><br> **TB1:** Expuso ante el equipo las decisiones de implementación del bounded context Support & Dashboard en la Web Application, explicando oralmente cómo se estructuraron los componentes Angular para la visualización del panel de control y el módulo de soporte al usuario. <br><br> **AV2:** Explicó la implementación backend de los Bounded Contexts Support y Dashboard, presentando los servicios desarrollados para la gestión de tickets de soporte y la consulta de métricas relacionadas con rendimiento, pérdidas y consumo de agua. <br><br> **TB2:** Expuso ante el equipo la evolución del Bounded Context Support & Dashboard en el Frontend durante el Sprint 4, explicando cómo se integró el nuevo módulo de tickets de soporte con las analíticas del panel de control para centralizar la experiencia post-venta del usuario. <br><br> **Pablo Afranio Martinez Gaona** <br> **AV1:** Participó en la sesión colaborativa de Big Picture Event Storming, comunicando oralmente al equipo los eventos, comandos y actores del dominio agrícola identificados, facilitando la comprensión compartida del sistema entre miembros con distintos niveles de conocimiento del negocio. <br><br> **TB1:** Presentó al equipo el bounded context Soil Monitoring implementado en la Web Application, describiendo oralmente el flujo de visualización de datos de monitoreo de suelos y justificando las decisiones de diseño de componentes frente a los demás integrantes. <br><br> **AV2:** Explicó la implementación backend del Bounded Context Soil Monitoring, detallando el registro de lecturas de humedad y temperatura, la gestión de recomendaciones de riego, las validaciones del dominio y la integración preparada con Farming para eliminar los datos relacionados con una parcela. <br><br> **Eder Edu Quispe Perez** <br> **AV1:** Realizó las entrevistas N°2 y N°3 a las agricultoras Lucía Alarcón (Amazonas) y Luz Mamani (Arequipa), comunicando el propósito del proyecto de forma clara y accesible a usuarias con poca experiencia tecnológica, logrando que expresaran sus necesidades y frustraciones con confianza. <br><br> **TB1:** Sustentó ante el equipo las decisiones de implementación de los bounded contexts Identity y Farming en la Web Application, explicando oralmente cómo se estructuraron las vistas de autenticación y gestión de parcelas y cultivos en Angular para satisfacer las necesidades de los segmentos objetivo. <br><br> **AV2:** Explicó el funcionamiento del backend del Bounded Context Farming, incluyendo la gestión de parcelas y cultivos, sus principales reglas de negocio y la relación de este contexto con otros módulos del sistema. <br><br> **TB2:** Explicó ante el equipo la implementación del Bounded Context Monitoring en el Backend durante el Sprint 4, detallando el registro y seguimiento de las condiciones de las parcelas y sustentando su integración con los demás Bounded Contexts del sistema. <br><br> **Miler Alexander Rodriguez Rojas** <br> **AV1:** Realizó las entrevistas N°1 y N°4 al agricultor Walter Medina (Chachapoyas) y al empresario agrícola Renzo Quispe (Lima), ajustando el tono y el nivel de detalle de las preguntas según el perfil de cada entrevistado para facilitar respuestas claras y comparables. <br><br> **TB1:** Expuso ante el equipo el bounded context Climate Alerts implementado en la Web Application, comunicando oralmente el flujo de visualización y gestión de alertas climáticas en Angular y coordinando con los responsables de Soil Monitoring y Farming la coherencia visual y funcional entre módulos. <br><br> **AV2:** Presentó la implementación backend del Bounded Context Climate Alerts, explicando cómo se gestionan las alertas climáticas y cómo estas pueden ser consultadas por la aplicación web.<br><br> **TB2:** Sustentó ante el equipo el diseño del Bounded Context Alerts durante el Sprint 4, explicando cómo las reglas de alerta consumen la información generada por Monitoring para notificar a los agricultores según su plan contratado, manteniendo bajo acoplamiento entre ambos módulos. <br><br> **Eduardo David Velasquez Laquihuanaco** <br> **AV1:** Expuso ante el equipo los resultados del análisis de competidores (CropX, Trimble Ag, Agroptima), sintetizando verbalmente las diferencias estratégicas relevantes para orientar las decisiones de diseño del producto hacia el segmento peruano desatendido. <br><br> **TB1:** Comunicó oralmente al equipo el diseño e implementación del bounded context Identity en la Web Application, explicando las decisiones sobre las vistas de registro e inicio de sesión en Angular y articulando cómo este módulo actúa como punto de entrada transversal para los demás bounded contexts del sistema. <br><br> **AV2:** Explicó el desarrollo backend del Bounded Context Identity, incluyendo la gestión de usuarios, planes de suscripción y preferencias de alertas mediante endpoints REST. <br><br> **TB2:** Expuso ante el equipo la implementación del módulo de IAM dentro del Bounded Context Identity durante el Sprint 4, explicando el flujo de registro (sign-up), inicio de sesión (sign-in) y protección de endpoints mediante JWT, y sustentó las decisiones de diseño de la sección Home de la cuarta versión de la Landing Page. | El equipo demostró capacidad de comunicación oral efectiva al conducir seis entrevistas con agricultores y empresarios agrícolas de distintas regiones del Perú (Amazonas, Arequipa, Lima, Piura), adaptando el vocabulario y el nivel de detalle técnico según el perfil de cada entrevistado. En el TB1, cada integrante lideró la implementación de un bounded context en la Web Application y comunicó oralmente sus decisiones de diseño e implementación al resto del equipo, fortaleciendo la comprensión compartida de la arquitectura de la solución. En el AV2 el equipo comunicó de manera organizada los avances realizados en los distintos Bounded Contexts del backend, presentando las funcionalidades, endpoints y principales decisiones técnicas de cada implementación. En el TB2, cada integrante sustentó ante el equipo y en la evaluación síncrona final los avances del Bounded Context que lideró durante el Sprint 4, explicando las decisiones de diseño del módulo de autenticación (IAM), las alertas, el monitoreo de parcelas y el soporte al usuario, evidenciando comunicación oral efectiva en el cierre del ciclo de desarrollo del backend.|
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | <br>**Alberto Joaquin Alfaro Mallma** <br> **AV1:** Redactó las Style Guidelines del producto (tipografía, paleta de colores, espaciado, tono de voz), comunicando por escrito los criterios visuales y editoriales de AgroTrack de forma que sean comprensibles tanto para el equipo de desarrollo como para evaluadores externos. <br><br> **TB1:** Documentó por escrito la implementación del bounded context Support & Dashboard en la Web Application, redactando en el informe del Sprint 2 la descripción de los componentes Angular desarrollados y las vistas de panel de control y soporte, de forma comprensible para evaluadores técnicos y no técnicos.<br><br> **AV2:** Implementó y documentó los endpoints correspondientes a Support y Dashboard, registrando mediante commits el desarrollo de la gestión de tickets y de las métricas utilizadas por el dashboard. <br><br> **TB2:** Documentó por escrito la ampliación del Bounded Context Support & Dashboard para el informe del Sprint 4, registrando mediante commits el desarrollo del nuevo módulo de tickets de soporte y su integración con las métricas del panel de control. <br><br> **Pablo Afranio Martinez Gaona** <br> **AV1:** Redactó el análisis FODA de AgroTrack y las estrategias y tácticas frente a competidores, estructurando la información de forma clara para una audiencia de negocio que requiere argumentación estratégica y no solo descripción técnica del producto. <br><br> **TB1:** Documentó el bounded context Soil Monitoring en el informe del Sprint 2, describiendo por escrito los componentes Angular implementados para la visualización de datos de humedad y nutrientes del suelo, asegurando que la documentación sea interpretable por desarrolladores y evaluadores externos.<br><br> **AV2:** Implementó y documentó las Technical Stories del Bounded Context Soil Monitoring, correspondientes a los endpoints de lecturas de suelo y recomendaciones de riego. Asimismo, registró los avances mediante commits y documentó las reglas de negocio, validaciones, persistencia e integración con el BC Farming. <br><br> **Eder Edu Quispe Perez** <br> **AV1:** Desarrolló la Landing Page de AgroTrack con soporte bilingüe (EN/ES) mediante el sistema i18n implementado en JavaScript, garantizando que la propuesta de valor del producto se comunique por escrito de forma efectiva tanto a usuarios hispanohablantes como angloparlantes. <br><br> **TB1:** Redactó en el informe del Sprint 2 la documentación de los bounded contexts Identity y Farming implementados en la Web Application, detallando los componentes Angular de autenticación y gestión de parcelas y cultivos de forma clara para audiencias técnicas y evaluadores del curso.<br><br> **AV2:** Implementó y documentó los servicios REST del Bounded Context Farming para la gestión de parcelas y cultivos, incluyendo las operaciones necesarias para crear, consultar, actualizar y eliminar estos recursos. <br><br> **TB2:** Documentó por escrito la implementación del Bounded Context Monitoring para el informe del Sprint 4, incluyendo el registro y seguimiento de las condiciones de las parcelas, y redactó documentación técnica de los controladores y assemblers REST utilizados en la integración entre Bounded Contexts. <br><br> **Miler Alexander Rodriguez Rojas** <br> **AV1:** Redactó las secciones de Needfinding (User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping), traduciendo los hallazgos cualitativos de las entrevistas en documentos estructurados comprensibles para audiencias de diseño y de negocio. <br><br> **TB1:** Documentó el bounded context Climate Alerts en el informe del Sprint 2, redactando por escrito la descripción de los componentes Angular desarrollados para la visualización y gestión de alertas climáticas, garantizando que la especificación sea comprensible para desarrolladores y evaluadores con distintos niveles de familiaridad con el dominio agrícola.<br><br> **AV2:** Implementó y documentó los endpoints del Bounded Context Climate Alerts, dejando evidencia escrita de las funcionalidades desarrolladas para gestionar y consultar las alertas climáticas. <br><br> **TB2:** Documentó por escrito el diseño del Bounded Context Alerts para el informe del Sprint 4, describiendo las reglas de generación de alertas básicas y avanzadas según el plan contratado y su relación de bajo acoplamiento con el Bounded Context Monitoring. <br><br> **Eduardo David Velasquez Laquihuanaco** <br> **AV1:** Redactó el Ubiquitous Language y contribuyó a la especificación de User Stories y Technical Stories, asegurando que los términos del dominio agrícola (Plot, Crop, Soil Moisture, Weather Alert) estén definidos con precisión para audiencias técnicas y no técnicas por igual. <br><br> **TB1:** Documentó por escrito el bounded context Identity en el informe del Sprint 2, describiendo los componentes Angular de registro, inicio de sesión y gestión de perfiles implementados en la Web Application, comunicando las decisiones de implementación de forma clara para audiencias técnicas y evaluadores del curso. <br><br> **AV2:** Implementó y documentó los endpoints del Bounded Context Identity para usuarios, planes de suscripción y preferencias de alertas, incluyendo sus criterios de aceptación y contratos REST. <br><br> **TB2:** Documentó por escrito la implementación del módulo de IAM en el Bounded Context Identity para el informe del Sprint 4, incluyendo los endpoints de autenticación (sign-up, sign-in) protegidos con JWT en la sección de Services Documentation Evidence, y registró mediante commits el desarrollo de la sección Home de la cuarta versión de la Landing Page. | El equipo evidenció comunicación escrita efectiva a múltiples audiencias a lo largo del informe: los capítulos de introducción y problemática están redactados en lenguaje accesible orientado al lector no técnico, mientras que las secciones de User Stories, Technical Stories y especificaciones de API están dirigidas a una audiencia técnica especializada. La Landing Page, desarrollada en HTML/CSS/JS con soporte bilingüe (EN/ES), demuestra la capacidad del equipo de comunicar la propuesta de valor del producto de forma escrita clara y persuasiva a dos segmentos diferenciados de usuarios. En el TB1, cada integrante documentó por escrito su bounded context en el informe del Sprint 2, describiendo los componentes Angular desarrollados en la Web Application de forma comprensible para distintas audiencias. En el AV2, La documentación elaborada por los integrantes permitió dejar evidencia clara de las funcionalidades implementadas en cada Bounded Context. El uso de Technical Stories, criterios de aceptación, commits, documentación REST y evidencias de Swagger facilitó la revisión del trabajo, la integración de los módulos y la comprensión del backend por parte del equipo y de otros interesados en el proyecto. En el TB2, el equipo dejó evidencia escrita del cierre del Sprint 4 mediante la tabla de commits de Development Evidence, la documentación de endpoints vía Swagger para el módulo de IAM y las reflexiones individuales sobre el desarrollo colaborativo de Alerts, Monitoring y Support & Dashboard.|
 
<br>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Andes Smart es una startup enfocada en desarrollar soluciones
tecnológicas accesibles para el sector agrícola, especialmente para
pequeños y medianos agricultores que no cuentan con herramientas
digitales avanzadas. Nace con la intención de reducir la brecha
tecnológica en el campo y mejorar la toma de decisiones a través del uso
de datos.

Su producto principal, AgroTack, es una plataforma web que permite a los
agricultores registrar sus parcelas, ingresar información sobre sus
cultivos y recibir recomendaciones prácticas para optimizar el riego y
el cuidado de sus tierras. La propuesta busca reemplazar prácticas
tradicionales basadas en la intuición por decisiones más informadas y
eficientes.

A futuro, Andes Smart planea integrar tecnologías IoT, como sensores de
humedad y temperatura, que permitirán recolectar datos en tiempo real
directamente desde el campo. Esto no solo reducirá la carga manual del
agricultor, sino que también mejorará la precisión de las
recomendaciones, generando un impacto positivo en la productividad y el
uso responsable de los recursos.



### 1.1.2 Perfiles de integrantes del equipo 

|||
|------|-------------|
| ![Foto](report/assets/Joaquin_foto.png) | **Nombres y apellidos:** Alberto Joaquín Alfaro Mallma <br><br> **Código:** U20241A267 <br><br> **Descripción de carrera:** La ingeniería de software es una carrera enfocada en el diseño, desarrollo, prueba y mantenimiento de programas y aplicaciones informáticas. Los ingenieros de software aplican principios de ingeniería y métodos sistemáticos para crear soluciones de software eficientes, fiables y escalables que satisfacen las necesidades de usuarios y organizaciones. <br><br>**Principales conocimientos técnicos y habilidades:** Creatividad, trabajo en equipo, responsabilidad y conocimientos básicos en frameworks JavaScript, HTML, CSS, Angular 7 y Node.js |
| <br>![Foto](report/assets/Edu_foto.png) | <br>**Eder Edu Quispe Perez**<br><br> Código de Estudiante: U202324623<br><br>Me llamo Eder Edu Quispe Pérez, soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), manejo lenguajes como Python y C++, y en mi tiempo libre me gusta ver películas y series<br><br>|
| <br>![Foto](report/assets/Miler_foto.png) | <br> **Rodriguez Rojas, Miler Alexander U20241A827**<br><br>Soy estudiante de Ingeniería de Software de quinto ciclo, con 22 años, enfocado en el desarrollo de soluciones tecnológicas eficientes. Me considero una persona con liderazgo, capaz de trabajar en equipo y adaptarme rápidamente a distintos entornos y necesidades del proyecto.<br>Cuento con conocimientos en lenguajes y herramientas como SQL Server, C++, HTML, CSS y Python, los cuales aplico en el desarrollo de proyectos académicos y personales.<br>En mis tiempos libres disfruto jugar fútbol, escuchar música, programar y ver películas, actividades que complementan mi creatividad y disciplina.|
| <br>![Foto](report/assets/Pablo_foto.png) |<br> **Martinez Gaona, Pablo Afranio U202120011** <br><br> Tengo 24 años y estudio la carrera de Ingeniería de Software. Me considero alguien adaptable a la situación, así como alguien que trabaja muy bien en equipo. Manejo lenguajes de programación como C++ y Python. Busco aprender más acerca de la ciencia de datos asi como de la inteligencia artificial. Me gusta los videojuegos y escuchar música.
|<br>![Foto](report/assets/Eduardo_foto.png) |<br> **Velasquez Laquihuanaco, Eduardo David U202323350** <br><br> Mi nombre es Eduardo David Velasquez Laquihuanaco, tengo 20 años, estudio la carrera de Ingeniería de Software con un gran interés en la tecnología y la innovación con el objetivo de desarrollar soluciones que mejoren la vida de las personas. Actualmente estoy en el 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. <br> En mis ratos libres me gusta escuchar música, jugar en línea con amigos y programar.<br><br>|


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Para estructurar el análisis del problema central que dio origen a
AgroTrack, se utiliza el framework **5W2H**, que permite identificar con
claridad el contexto, los actores involucrados y la naturaleza del
problema.

------------------------------------------------------------------------

**What (¿Qué ocurre?)**

Los agricultores pequeños del Perú toman sus decisiones de riego
basándose principalmente en la intuición, la experiencia empírica o
rutinas heredadas de generaciones anteriores. Esta práctica, aunque
comprensible dado el contexto en que opera la mayoría de ellos, genera
consecuencias directas en la productividad: el exceso de riego provoca
encharcamiento y pérdida de nutrientes en el suelo, mientras que el
déficit hídrico produce estrés en los cultivos y merma la cosecha. En
ninguno de los dos casos el agricultor cuenta con información objetiva
que le permita actuar a tiempo.

A esto se suma la ausencia de herramientas de registro. La mayoría lleva
el seguimiento de sus parcelas en papel, en libretas personales o
simplemente de memoria. Cuando algo falla, es difícil rastrear qué salió
mal y cuándo. El conocimiento sobre el estado de la tierra no se acumula
ni se analiza, se pierde con cada temporada.

------------------------------------------------------------------------

**Why (¿Por qué sucede?)**

El problema tiene raíces estructurales. Las soluciones tecnológicas
disponibles en el mercado como CropX o Trimble Ag fueron diseñadas para
grandes operaciones agroindustriales con presupuestos elevados y equipos
técnicos especializados. Un agricultor pequeño en Cajamarca, Junín o Ica
no tiene acceso real a esas herramientas, no solo por su costo, sino
porque requieren infraestructura que no existe en zonas rurales.

Por otro lado, las iniciativas estatales orientadas a la digitalización
del agro peruano impulsadas por el MIDAGRI y la ANA aún no han logrado
traducirse en herramientas concretas y usables para el agricultor de a
pie. La brecha entre la política pública y la realidad del campo sigue
siendo grande.

A todo esto se agrega un factor cultural: el agricultor tradicional
tiende a desconfiar de herramientas que no comprende o que percibe como
ajenas a su trabajo. Si la tecnología no habla su idioma, no se adapta a
su ritmo y no le muestra un beneficio claro desde el primer uso,
simplemente no la adopta.

------------------------------------------------------------------------

**Who (¿A quiénes afecta?)**

El problema impacta principalmente a dos perfiles:

- **Agricultores pequeños e independientes**, hombres y mujeres de entre
  20 y 75 años que trabajan sus propias parcelas, muchas veces con apoyo
  familiar. Para ellos, una mala decisión de riego no es solo un error
  técnico, puede significar perder una temporada entera y comprometer el
  sustento del hogar.
- **Empresarios agrícolas con pequeñas y medianas empresas (PYMEs)**,
  que gestionan varias parcelas pero no cuentan con sistemas que les den
  visibilidad real sobre su producción. Su problema no es la falta de
  conocimiento agrícola, sino la ausencia de datos organizados que les
  permitan tomar decisiones de inversión más informadas.

Ambos perfiles comparten una necesidad común: necesitan información
útil, en el momento justo, sin tener que convertirse en especialistas en
tecnología para obtenerla.

------------------------------------------------------------------------

**Where (¿Dónde ocurre?)**

La problemática se concentra en las zonas agrícolas del Perú,
especialmente en regiones donde la agricultura de pequeña escala es la
actividad económica principal: la sierra central y norte, los valles
interandinos y algunas zonas de la costa. Son regiones con conectividad
limitada, escasa presencia de servicios tecnológicos y una fuerte
dependencia de métodos tradicionales de cultivo.

------------------------------------------------------------------------

**When (¿Cuándo se hace más evidente?)**

El problema se vuelve crítico durante los momentos de decisión: antes de
regar, cuando cambia el clima, cuando aparecen señales de deterioro en
el cultivo o cuando el agricultor necesita planificar la siguiente
siembra. Son momentos en que la falta de datos concretos obliga a actuar
por intuición, asumiendo riesgos que podrían evitarse con información
básica pero confiable.

------------------------------------------------------------------------

**How (¿Cómo se manifiesta el impacto?)**

Las consecuencias son visibles en tres dimensiones:

- **Económica**: el desperición de agua eleva los costos operativos, y
  los cultivos arruinados por riego inadecuado representan pérdidas
  directas para el agricultor.
- **Productiva**: la falta de seguimiento sistemático impide identificar
  patrones de mejora o deterioro en las parcelas, lo que limita la
  capacidad de optimizar la producción temporada a temporada.
- **Ambiental**: el uso ineficiente del agua en el agro peruano
  contribuye a la sobreexplotación de recursos hídricos, un problema
  cada vez más urgente en el contexto de variabilidad climática que vive
  el país.

------------------------------------------------------------------------

**How much (¿Cuál es la magnitud del problema?)**

Según datos del IV Censo Nacional Agropecuario (CENAGRO), más del 70% de
las unidades agropecuarias en el Perú tienen menos de 5 hectáreas. La
gran mayoría de estos productores no utiliza ningún tipo de herramienta
digital para gestionar sus cultivos. En paralelo, el Perú enfrenta una
creciente presión sobre sus recursos hídricos, y la agricultura es el
sector que más agua consume a nivel nacional. La ineficiencia en el
riego no es un problema menor: es uno de los principales factores que
limitan la productividad del agro peruano y el bienestar de las familias
que dependen de él.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

A partir del análisis de antecedentes y del Lean UX Canvas desarrollado
para AgroTrack, se identifican los siguientes problem statements que
guían el diseño de la solución:

------------------------------------------------------------------------

**Problem Statement 1 --- Agricultores pequeños**

Hemos observado que los agricultores pequeños en el Perú toman
decisiones de riego sin contar con información objetiva sobre el estado
real de su suelo. Esto genera un uso ineficiente del agua, pérdida de
cultivos y un impacto económico directo en sus familias.

¿Cómo podríamos brindar a los agricultores pequeños una herramienta
sencilla que les muestre, de forma clara y en su idioma, cuándo y cuánto
regar, para que puedan tomar mejores decisiones sin necesidad de ser
expertos en tecnología?

------------------------------------------------------------------------

**Problem Statement 2 --- Agricultores pequeños frente a eventos
climáticos**

Hemos observado que los agricultores pequeños no cuentan con alertas
anticipadas sobre cambios climáticos que puedan dañar sus cultivos.
Cuando se enteran de que viene una helada, una lluvia intensa o una
sequía prolongada, ya es demasiado tarde para actuar.

¿Cómo podríamos anticipar a los agricultores los eventos climáticos que
amenazan sus parcelas, con el tiempo suficiente para que puedan tomar
medidas preventivas y proteger su cosecha?

------------------------------------------------------------------------

**Problem Statement 3 --- Seguimiento y registro de cultivos**

Hemos observado que la mayoría de los agricultores pequeños lleva el
control de sus parcelas en papel, libretas o simplemente de memoria.
Esto hace imposible analizar qué funcionó y qué no en temporadas
anteriores, y obliga a repetir los mismos errores.

¿Cómo podríamos ofrecer a los agricultores un sistema de registro
digital simple y visual que reemplace el papel sin requerir habilidades
tecnológicas avanzadas, y que les permita llevar un historial útil de
sus cultivos?

------------------------------------------------------------------------

**Problem Statement 4 --- Empresarios agrícolas con PYMEs**

Hemos observado que los empresarios agrícolas que gestionan pequeñas y
medianas empresas no tienen visibilidad centralizada sobre el estado de
sus parcelas ni sobre el rendimiento de su inversión. Sus decisiones de
gestión se basan en reportes informales o en la memoria de sus
trabajadores.

¿Cómo podríamos dar a los empresarios agrícolas un panel de control que
les permita ver en un solo lugar el estado de todas sus parcelas, el
historial de cultivos y los indicadores clave para tomar decisiones más
informadas sobre su operación?

#### 1.2.2.2. Lean UX Assumptions

Para el desarrollo de AgroTrack, se plantean las siguientes suposiciones
iniciales basadas en el enfoque Lean UX:

- Creemos que los agricultores pequeños tienen dificultades para tomar
  decisiones de riego debido a la falta de información sobre el estado
  real de su suelo.
- Creemos que contar con datos como la humedad del suelo puede ayudar a
  los agricultores a tomar decisiones más acertadas sobre cuándo regar.
- Creemos que los agricultores valoran recibir alertas anticipadas sobre
  cambios climáticos que puedan afectar sus cultivos.
- Creemos que las recomendaciones automáticas basadas en datos del suelo
  y del clima pueden mejorar el uso del agua y reducir desperdicios.
- Creemos que los agricultores prefieren herramientas simples y visuales
  que les permitan entender fácilmente el estado de sus cultivos.
- Creemos que llevar un registro digital de sus cultivos facilitará el
  seguimiento y control de sus siembras en comparación con métodos
  tradicionales.
- Creemos que los agricultores estarán dispuestos a usar una plataforma
  web si perciben beneficios claros en su producción o ahorro de
  recursos.
- Creemos que, aunque inicialmente el ingreso de datos sea manual, los
  usuarios verán valor en la plataforma si reciben recomendaciones
  útiles.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que mostrar en tiempo real el nivel de humedad del suelo para
  agricultores pequeños con poco acceso a tecnología logrará que tomen
  mejores decisiones sobre cuándo regar. Sabremos que es verdad cuando
  al menos el 60% de usuarios consulte el monitoreo antes de regar
  durante las primeras 2 semanas de uso.

- Creemos que enviar alertas climáticas anticipadas para agricultores
  pequeños logrará que protejan sus cultivos antes de que ocurra un
  evento climático adverso. Sabremos que es verdad cuando veamos que el
  50% de usuarios que recibe una alerta toma alguna acción preventiva
  dentro de las siguientes 24 horas.

- Creemos que brindar recomendaciones automáticas de riego basadas en
  los datos del suelo y el clima logrará que reduzcan el desperdicio de
  agua en los cultivos. Sabremos que es verdad cuando veamos que los
  usuarios reportan una reducción en su consumo de agua después de 30
  días de uso.

- Creemos que ofrecer un registro visual y simple del estado de cada
  cultivo logrará que lleven un mejor seguimiento de sus siembras sin
  necesidad de papel o memoria. Sabremos que es verdad cuando veamos que
  al menos el 40% de usuarios registra sus cultivos activamente durante
  el primer mes.

### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas de AgroTrack](report/assets/Lean_UX_Canvas.jpg)

## 1.3. Segmentes Objetivo

- **Agricultores** Trabajadores en el sector agrícola del Perú entre 20
  y 75 años, con educación secundaria completa. Valoran la mano de obra,
  pero buscan la automatización y optimización.

- **Empresarios agrícolas** Empresarios dueños de PYMEs en el Perú, que
  gestionan cultivos y buscan optimizar su producción para maximizar sus
  ganancias y reducir mermas. Tienen entre 30 y 75 años y buscan
  herramientas que les den visibilidad sobre su inversión.

<br>
<br>


# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis Competitivo

A continuación se presenta el análisis competitivo de AgroTrack frente a las principales soluciones digitales existentes en el mercado agrícola.

**Competitive Analysis Landscape**

**¿Por qué llevar a cabo este análisis?**

Realizamos este análisis para identificar las fortalezas y debilidades de los competidores directos e indirectos de AgroTrack, con el fin de definir una propuesta de valor diferenciada y estrategias que nos permitan captar el segmento de agricultores pequeños y empresarios agrícolas en el Perú.

---

**Tabla de Análisis Competitivo**

|  | **AgroTrack** | **CropX** | **Trimble Ag** | **Agroptima** |
|---|---|---|---|---|
| **Logo** | *(Andes Smart)* | *(CropX Inc.)* | *(Trimble Inc.)* | *(Agroptima SL)* |
| **Perfil General** | Plataforma web de monitoreo agrícola orientada a pequeños agricultores y PYMEs del Perú, con alertas climáticas y recomendaciones de riego. | Solución IoT de sensores de suelo para monitoreo de humedad y temperatura, enfocada en grandes operaciones agrícolas. | Suite completa de gestión agrícola con GPS, maquinaria y análisis de datos para grandes productores. | App de gestión de cultivos para pequeños y medianos agricultores en España y Latinoamérica. |
| **Ventaja Competitiva** | Adaptado al contexto peruano, bajo costo de entrada, interfaz simple en español para usuarios con poca experiencia tecnológica. | Alta precisión de datos de suelo en tiempo real mediante sensores físicos instalados en campo. | Ecosistema integrado de hardware y software con décadas de experiencia en el sector. | Facilidad de uso y orientación a pequeños productores; registro de actividades y cuaderno de campo digital. |
| **Mercado Objetivo** | Agricultores pequeños y empresarios agrícolas PYMEs en Perú (20–75 años). | Grandes productores agrícolas en EE.UU., Australia, Israel y mercados emergentes. | Grandes y medianas empresas agroindustriales a nivel global. | Pequeños y medianos agricultores en España, México, Chile, Colombia y Perú. |
| **Estrategias de Marketing** | Redes sociales, landing page con demostración del producto, alianzas con asociaciones agrícolas locales. | Venta directa B2B, ferias agrícolas internacionales, demostraciones técnicas en campo. | Fuerza de ventas corporativa, distribuidores especializados, presencia en ferias globales (Agritechnica). | Marketing digital, prueba gratuita, modelo freemium con planes de pago por funcionalidades. |
| **Productos & Servicios** | Panel de control de parcelas, alertas climáticas, recomendaciones de riego, historial digital de cultivos. | Sensores de humedad/temperatura de suelo, plataforma de análisis de datos, informes predictivos. | Software de planificación de cultivos, gestión de maquinaria, mapas de rendimiento, telemetría GPS. | Cuaderno de campo digital, registro de actividades, control de fitosanitarios, análisis de costes. |
| **Precios & Costos** | Por definir (modelo freemium orientado a bajo costo para el mercado peruano). | Desde ~$500 USD por kit de sensor + suscripción mensual. | Licencias corporativas desde cientos de dólares anuales; alto costo de implementación. | Plan gratuito limitado; planes de pago desde ~10–30 EUR/mes. |
| **Canales de Distribución** | Web app directa, WhatsApp y redes sociales como canal de soporte y adquisición. | Venta directa, distribuidores agrícolas, integradores de tecnología. | Distribuidores autorizados Trimble, integradores de soluciones agro. | App Store, Google Play, sitio web oficial. |

---

**Análisis FODA de AgroTrack**

| | **Fortalezas** | **Debilidades** |
|---|---|---|
| | - Diseñado específicamente para el contexto peruano. | - Sin datos históricos propios ni base de usuarios establecida. |
| | - Interfaz simple en español, orientada a usuarios con bajo nivel tecnológico. | - Dependencia de conectividad a internet en zonas rurales con baja cobertura. |
| | - Bajo costo de entrada frente a soluciones internacionales. | - Equipo pequeño con recursos limitados para escalar rápidamente. |
| | - Panel visual de parcelas y alertas climáticas como diferenciador inmediato. | - Aún sin integración IoT real (entrada manual de datos en la fase inicial). |
| **Oportunidades** | **Amenazas** |
| | - Creciente digitalización del agro peruano impulsada por el Estado y ONG. | - Competidores internacionales con mayor respaldo financiero y tecnológico. |
| | - Bajo nivel de penetración de soluciones tecnológicas en el agro peruano. | - Agroptima ya tiene presencia en Latinoamérica con producto maduro. |
| | - Posibilidad de alianzas con el Ministerio de Agricultura (MIDAGRI) y ANA. | - Posible desconfianza del agricultor tradicional hacia herramientas digitales. |
| | - Expansión a otros países andinos con problemática similar (Bolivia, Ecuador). | - Riesgo de copia rápida de funcionalidades por startups con más recursos. |

---

### 2.1.2. Estrategias y Tácticas frente a Competidores

Frente al panorama competitivo analizado, AgroTrack adoptará las siguientes estrategias:

**Estrategia de Diferenciación por Contexto Local**

A diferencia de CropX y Trimble Ag, cuyas soluciones están diseñadas para grandes productores con alto poder adquisitivo, AgroTrack se posiciona como la alternativa accesible y adaptada al agricultor peruano. El uso de lenguaje sencillo, la interfaz en español y el modelo de bajo costo son barreras de entrada intencionales para captar al segmento desatendido.

**Estrategia de Penetración con Modelo Freemium**

Al igual que Agroptima, AgroTrack ofrecerá acceso gratuito a funcionalidades básicas (registro de parcelas, alertas climáticas) para reducir la fricción de adopción. Las funcionalidades avanzadas (historial analítico, recomendaciones personalizadas) estarán disponibles en planes de pago asequibles.

**Estrategia de Validación Temprana con Usuarios**

Antes de competir directamente con plataformas maduras, AgroTrack priorizará entrevistas de Needfinding y pruebas de prototipo con agricultores locales. Esto permite iterar el producto rápidamente con retroalimentación real antes de escalar, reduciendo el riesgo de construir funcionalidades que el usuario no adopte.

**Táctica de Alianzas Institucionales**

Se explorarán alianzas con el MIDAGRI, la ANA (Autoridad Nacional del Agua), y asociaciones de productores regionales para ganar credibilidad y acceso a base de usuarios sin depender exclusivamente de marketing digital.

**Táctica de Contenido Educativo**

Dado que el agricultor objetivo puede ser reticente a adoptar tecnología, AgroTrack desarrollará contenido educativo (tutoriales en video, guías en WhatsApp) que reduzca la curva de aprendizaje y genere confianza en la plataforma antes de la primera descarga.

### 2.1.2. Estrategias y Tácticas frente a Competidores

Frente al panorama competitivo analizado, AgroTrack adoptará las
siguientes estrategias:

**Estrategia de Diferenciación por Contexto Local**

A diferencia de CropX y Trimble Ag, cuyas soluciones están diseñadas
para grandes productores con alto poder adquisitivo, AgroTrack se
posiciona como la alternativa accesible y adaptada al agricultor
peruano. El uso de lenguaje sencillo, la interfaz en español y el modelo
de bajo costo son barreras de entrada intencionales para captar al
segmento desatendido.

**Estrategia de Penetración con Modelo Freemium**

Al igual que Agroptima, AgroTrack ofrecerá acceso gratuito a
funcionalidades básicas (registro de parcelas, alertas climáticas) para
reducir la fricción de adopción. Las funcionalidades avanzadas
(historial analítico, recomendaciones personalizadas) estarán
disponibles en planes de pago asequibles.

**Estrategia de Validación Temprana con Usuarios**

Antes de competir directamente con plataformas maduras, AgroTrack
priorizará entrevistas de Needfinding y pruebas de prototipo con
agricultores locales. Esto permite iterar el producto rápidamente con
retroalimentación real antes de escalar, reduciendo el riesgo de
construir funcionalidades que el usuario no adopte.

**Táctica de Alianzas Institucionales**

Se explorarán alianzas con el MIDAGRI, la ANA (Autoridad Nacional del
Agua), y asociaciones de productores regionales para ganar credibilidad
y acceso a base de usuarios sin depender exclusivamente de marketing
digital.

**Táctica de Contenido Educativo**

Dado que el agricultor objetivo puede ser reticente a adoptar
tecnología, AgroTrack desarrollará contenido educativo (tutoriales en
video, guías en WhatsApp) que reduzca la curva de aprendizaje y genere
confianza en la plataforma antes de la primera descarga.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

El objetivo de estas entrevistas es validar los puntos de dolor
relacionados con la gestión del riego y la disposición al uso de
herramientas digitales. Se han diseñado cuestionarios específicos para
cada segmento objetivo. - Preguntas para los agricultores: 1. ¿Qué
cultivos maneja actualmente y qué herramientas o maquinaria utiliza para
su mantenimiento diario? 2. ¿Qué aplicaciones utiliza con más frecuencia
en su celular y para qué fines (comunicación, entretenimiento, trabajo)?
3. ¿Cómo determina hoy, paso a paso, que una parcela necesita riego sin
usar sensores? 4. ¿Cuál ha sido su mayor frustración relacionada con la
pérdida de una cosecha en el último año? 5. ¿Cómo calcula la cantidad de
agua o fertilizante que debe comprar para una temporada? 6. ¿A quién
acude o qué medios consulta cuando tiene una duda técnica sobre sus
cultivos? 7. ¿Cómo lleva el registro de las fechas de siembra y cosecha
actualmente (papel, memoria, otros)? 8. Ante una alerta de helada o
sequía, ¿qué acciones preventivas suele tomar y con cuánto tiempo de
anticipación? 9. Si tuviera una herramienta que automatizara sus
registros, ¿qué es lo primero que le gustaría que hiciera por usted? 10.
¿Qué le convencería de que usar una plataforma web es mejor que seguir
su intuición de años? - Preguntas para los empresarios agricolas: 1.
¿Cómo está estructurada su empresa y qué metas de producción tiene para
este ciclo académico/fiscal? 2. ¿Qué dispositivos (Laptop, Tablet,
Smartphone) considera indispensables para gestionar su negocio? 3. ¿Qué
indicadores de rendimiento (KPIs) monitorea para saber si su inversión
en cultivos es rentable? 4. ¿De qué manera la falta de datos precisos
sobre el suelo ha afectado sus costos de operación anteriormente? 5. ¿En
qué información se basa para autorizar el presupuesto de riego y
mantenimiento de la temporada? 6. ¿Qué herramientas digitales conoce que
use su competencia y qué opina de ellas? 7. ¿Qué porcentaje de su
producción se pierde usualmente por factores climáticos y cómo intenta
reducirlo? 8. ¿Cómo recibe los reportes del estado de los cultivos por
parte del personal de campo? 9. ¿Qué valor le daría a tener datos en
tiempo real de sus campos sin depender del ingreso manual de su
personal? 10. ¿Qué ahorro mínimo en costos de agua o mejora en la
cosecha esperaría para considerar que esta plataforma es un éxito?

### 2.2.2. Registro de entrevistas

**Entrevista N° 1**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 26            **Distrito:**
  apellidos:** Walter                             Chachapoyas, Amazonas
  Medina Macedo                                   
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQA7Y8rY1pOWRIXG-iCyIG6oAZ2IIM0sMFGl20NuTco6qfI?e=YgDGTl&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D   entrevista:** 00:00     
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 1](report/assets/Entrevista-01.png)

**Resumen:** Walter, de 26 años y estudiante de Ingeniería de Sistemas,
proviene de una familia dedicada al cultivo de café. Utilizan
herramientas como motoguadañas, fumigadoras y mano de obra para el
mantenimiento. Gestiona la comunicación con WhatsApp y usa Excel para
organizar costos, mientras que los registros de cultivo se llevan
principalmente en papel. Las decisiones de riego se toman de forma
manual, observando el estado de las plantas. Ha sufrido pérdidas por
plagas y no cuenta con medidas preventivas sólidas ante cambios
climáticos. Se apoya en técnicos agrícolas y programas del Estado para
asesoría. Le gustaría una herramienta que mida la humedad del suelo,
automatice registros y genere reportes, siempre que sea fácil de usar y
más eficiente que sus métodos actuales.

------------------------------------------------------------------------

**Entrevista N° 2**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 25            **Distrito:** Cumba,
  apellidos:** Lucia                              Amazonas
  Alarcon                                         
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQDidGgCC_E9QIX1GOCVgAAOAVuK1pcpOl7TY5HJ6ZAcxlY?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=MifF7G   entrevista:** 00:00     
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 2](report/assets/Entrevista-02.png)

**Resumen:** Lucía, de 25 años y estudiante de Psicología, es una
agricultora que cultiva maíz y hortalizas como tomate y lechuga. Utiliza
herramientas básicas como pala, azadón y fumigadora manual, y
ocasionalmente alquila motocultores para la preparación de tierra.
Gestiona la comunicación con WhatsApp para contactar compradores y otros
agricultores, mientras que usa Facebook y YouTube para obtener
información agrícola y aprender sobre plagas. Los registros de siembra y
cosecha los lleva principalmente en un cuaderno, con ocasionales apuntes
en memoria. Las decisiones de riego se toman de forma manual, observando
la sequedad del suelo y el estado de las plantas. Ha sufrido pérdidas
significativas por plagas que no detectó a tiempo. Le gustaría una
herramienta que automatice los registros de riego, siembra y
fertilización, y se convencería de adoptarla si demuestra mejorar la
producción, reducir pérdidas y sea fácil de usar.

------------------------------------------------------------------------

**Entrevista N° 3**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 24            **Distrito:** Arequipa,
  apellidos:** Luz Mamani                         Perú
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQD12rOS9xukQKDOJngTl7w0Aa2RYMlbZo7YzQXCsVdR7tw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=u8jJHb   entrevista:** 00:00     
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 3](report/assets/Entrevista-03.png)

**Resumen:** Luz, de 24 años y estudiante de Psicología, es una
agricultora que se dedica al cultivo de frutas como mango, palta y
limón. Utiliza herramientas básicas como pala, machete, tijeras para
podar y ocasionalmente una motobomba para el riego. Gestiona la
comunicación con WhatsApp para contactar otros agricultores y
compradores, mientras que usa Facebook y YouTube para obtener
información y aprender sobre agricultura. Los registros de siembra y
cosecha los lleva principalmente en un cuaderno, aunque también confía
en su memoria. Ha sufrido pérdidas significativas por calor extremo y
falta de agua. Ante alertas de heladas o sequía, intenta adelantar el
riego o proteger las plantas, aunque reconoce que la falta de tiempo
anticipado dificulta tomar medidas preventivas efectivas. Le gustaría
una herramienta que le avise automáticamente cuándo regar o abonar y que
guarde registros sin anotar manualmente, siempre que sea fácil de usar y
no consuma mucho internet.

------------------------------------------------------------------------

**Entrevista N° 4**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 28            **Distrito:** Lima,
  apellidos:** Renzo                              Perú
  Quispe Mamani                                   
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQBpPA9-AgKuTYSsa7rfQ_3NAWt06SZe20fFxPk2vz_tj6o?e=cWepbS&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D   entrevista:** 00:00     
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 4](report/assets/Entrevista-04.png)

**Resumen:** Renzo Sebastián Quispe Mamani, de 28 años y egresado de la
Universidad de Lima, es fundador de Ecotrack, un emprendimiento agrícola
organizado en producción, logística y administración. Su objetivo es
aumentar la producción en un 15% manteniendo la calidad. Utiliza
celular, laptop y tablet para gestionar su negocio y monitorea KPIs como
rendimiento por hectárea, costos, consumo de agua, pérdidas y
rentabilidad. Enfrenta problemas por la falta de datos precisos del
suelo, lo que genera decisiones ineficientes y mayores costos.
Actualmente se basa en experiencia, reportes manuales y estimaciones
climáticas. Pierde entre 10% y 20% de producción por factores climáticos
y considera clave contar con datos en tiempo real. Espera como mínimo un
10% de ahorro de agua o un 15% de aumento en la producción para
considerar exitosa una solución tecnológica.

------------------------------------------------------------------------

**Entrevista N° 5**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 26            **Distrito:** Lima,
  apellidos:** Sofia                              Perú
  Martinez                                        
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQBALW19b-Z_SIeQbTrZUZ1fAUpuk-2I7KrrwWEJK9rsHi0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=lvIQ03   entrevista:** 00:00     
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 5](report/assets/Entrevista-05.png)

**Resumen:** Sofía, de 26 años y estudiante de Psicología, es una joven
empresaria agrícola en la empresa Viru. La empresa está estructurada en
tres áreas principales: producción, logística y administración, con
supervisores de campo y personal técnico. Su meta para este ciclo es
aumentar la producción un 15% y reducir costos mediante el uso de
tecnología. Monitorea indicadores clave como rendimiento por hectárea,
costos de riego, porcentajes de pérdidas y calidad del cultivo. Autoriza
presupuestos basándose en condiciones climáticas, historial de
producción y experiencia del personal. La falta de datos precisos sobre
el suelo ha generado uso innecesario de fertilizantes y menor
productividad. Pierde entre 10% y 30% de su producción por factores
climáticos. Actualmente recibe reportes mediante llamadas, WhatsApp y
reportes manuscritos del personal de campo. Consideraría exitosa una
plataforma que reduzca 15% el consumo de agua, aumente 10% la producción
y disminuya pérdidas en un 10%.

------------------------------------------------------------------------

**Entrevista N° 6**

  -----------------------------------------------------------------------
  **Nombres y             **Edad:** 29            **Distrito:** Piura,
  apellidos:** Cristofer                          Perú
  Ordalla                                         
  ----------------------- ----------------------- -----------------------

  -----------------------------------------------------------------------

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a267_upc_edu_pe/IQDZaXNASBtjSqMs6HKMKmKSAVUVdK2ce6BrVstfl1zh2gk?e=CN8ApV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D   entrevista:** 00:00     
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------- -----------------------

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Entrevista 5](report/assets/Entrevista-06.png)

**Resumen:** Christopher Ordalla, de 29 años, se integró hace
aproximadamente un año y medio a una pequeña empresa agrícola familiar
que cuenta con 5 hectáreas alquiladas. La empresa opera mediante un
contrato de colaboración con un vecino para el alquiler de máquinas y el
trabajo de la tierra. Su meta para este ciclo fiscal es alcanzar una
producción de 8 toneladas de maíz en unas 3 hectáreas y estabilizar la
rentabilidad, dado que actualmente manejan un presupuesto ajustado.
Considera indispensables el celular para la comunicación general, la
toma de fotos de los cultivos y la revisión del clima, así como una
laptop para llevar las cuentas de ingresos y egresos en Excel. Monitorea
indicadores clave (KPIs) como el rendimiento por hectárea, el costo
total por kilo producido y el margen neto después del riesgo de
fertilizantes. Autoriza presupuestos basándose empíricamente en la
experiencia de su padre, los pronósticos de lluvias y la observación de
cómo va creciendo el cultivo. La falta de datos precisos sobre el suelo
provocó que sembraran en un terreno arcilloso creyendo que era
homogéneo, lo que demandó un mayor uso de nitrógeno y les hizo perder un
25% de la producción esperada en ese lote. Conoce a un vecino de la zona
que utiliza un dron para obtener vistas macro de la plantación y datos
del suelo, herramienta que considera muy interesante. Pierden alrededor
de un 18% de su producción por factores climáticos adversos en el norte,
como granizo o sequías, e intentan mitigar el impacto revisando
aplicaciones del clima para anticiparse. Actualmente, visita el campo de
1 a 3 veces al mes y recibe reportes de la persona que los ayuda
mediante fotos y audios por WhatsApp, información que él mismo se
encarga de vaciar en Excel. Valora enormemente la posibilidad de obtener
datos en tiempo real de forma automática, ya que le ahorraría bastante
tiempo y los costos asociados a la persona que ingresa los datos
manualmente. Consideraría que la plataforma es un éxito si le ayuda a
generar un ahorro de entre el 10% y el 20% en costos de agua y
fertilizantes.

### 2.2.3. Análisis de entrevistas

**Segmento objetivo 1: Agricultores**

A partir de las entrevistas realizadas a Walter Medina, Lucía Alarcón y
Luz Mamani, se identifican los siguientes patrones comunes:

- Los tres entrevistados llevan registros de forma manual (papel o
  cuaderno) y toman decisiones de riego de manera empírica, observando
  el estado visual del suelo y las plantas.
- El uso de WhatsApp es universal como canal de comunicación, y
  plataformas como Facebook y YouTube son sus principales fuentes de
  información técnica.
- Todos han sufrido pérdidas por factores climáticos o plagas sin contar
  con alertas anticipadas.
- La disposición a adoptar una herramienta digital es alta, siempre que
  sea simple, en español, funcione con poca internet y demuestre
  resultados concretos en reducción de pérdidas.
- La función más demandada es la automatización de registros y las
  alertas de riego o eventos climáticos.

**Segmento objetivo 2: Empresarios agrícolas**

A partir de las entrevistas realizadas a Renzo Quispe y Sofía Martínez,
se identifican los siguientes patrones comunes:

- Ambos gestionan empresas con estructura formal (producción, logística,
  administración) y utilizan múltiples dispositivos (celular, laptop,
  tablet).
- Monitorean KPIs similares: rendimiento por hectárea, costos de riego,
  porcentaje de pérdidas y calidad del cultivo.
- La principal fricción es la dependencia de reportes manuales del
  personal de campo, lo que genera demoras y decisiones basadas en datos
  inexactos.
- Pierden entre 10% y 30% de producción por factores climáticos y
  valoran enormemente tener datos en tiempo real.
- El umbral de éxito para adoptar una solución tecnológica es claro: al
  menos 10% de ahorro en agua y 15% de mejora en producción.

## 2.3. Needfinding

### 2.3.1. User Personas

Los User Persona son perfiles que representan a nuestros usuarios
principales, creados a partir de información real recogida en
entrevistas. Esta herramienta nos ayuda a entender sus objetivos,
dificultades y necesidades clave. En AgroTrack, estos perfiles permiten
diseñar soluciones más adecuadas a las expectativas tanto de los
artistas como de sus posibles clientes.

**User persona - Agricultores**

![FOTO](report/assets/user_personaAgricultor.png)

<br>

**User persona - Empresarios Agrícolas**

![FOTO](report/assets/user_personaEmpresario.png)

### 2.3.2. User Task Matrix

Para diseñar una solución con valor, se consideraron dos segmentos del
sector agrícola los agricultores, que buscan automatizar y optimizar sus
labores para mejorar su productividad y los empresarios agrícolas, que
necesitan herramientas para controlar su inversión, reducir pérdidas y
aumentar sus ganancias. La propuesta busca brindar información clara y
útil para ambos perfiles.

![FOTO](report/assets/user_Agricola.png)

<br>

![FOTO](report/assets/user_empresario_agricola.png)

<br>

Los cuadros reflejan cómo para los agricultores, las tareas más
frecuentes y relevantes se centran en registrar información del cultivo,
monitorear el estado del suelo y tomar decisiones de riego, ya que estas
actividades impactan directamente en su producción diaria. En cambio,
los empresarios agrícolas se enfocan en monitorear indicadores, analizar
rendimiento y supervisar reportes, buscando optimizar costos y maximizar
resultados.

### 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Mapping de los dos
segmentos identificados agricultores y empresarios agrícolas. Se
describe el recorrido actual As-Is que siguen para gestionar sus
cultivos y tomar decisiones de riego, desde la identificación de una
necesidad hasta la evaluación de resultados. Estos journeys reflejan las
actividades, necesidades y dificultades que enfrentan actualmente sin el
uso de una solución tecnológica como AgroTrack.

**User Journey Mapping - Agricultor**

![FOTO](report/assets/Journey-agricultor.png)

**User Journey Mapping - Empresario Agrícola**
![FOTO](report/assets/journey-empresario.png)

### 2.3.4. Empathy Mapping

En esta sección se presentan los Empathy Maps desarrollados para
profundizar en la comprensión de los segmentos objetivo de AgroTrack.
Este análisis permite identificar los dolores y las motivaciones reales
de los usuarios finales.

**Empathy Mapping - Agricultor**

![Empathy map del agricultor](report/assets/empathy_Mapping_Agricultor.png)

**Empathy Mapping - Empresario Agricola**

![Empathy map del
empresario](report/assets/empathy_Mapping_EmpresarioAgricola.png)

### 2.4. Big Picture Event Storming

El equipo realizó una sesión colaborativa en Miro para entender el
dominio del negocio de alto nivel, identificando procesos clave y
eventos significativos de AgroTrack. La organización visual sigue una
línea de tiempo narrativa de izquierda a derecha.

![Big event storming image](report/assets/big_event_storming_Image.png)
https://miro.com/app/board/uXjVGhuhZ48=/?share_link_id=264887531428

Descripción del proceso modelado: \* **Exploración de Eventos
(Naranja):** Representan hechos que ya sucedieron en el sistema, como el
registro del usuario (User Registered), la creación de una parcela (Plot
Created) o el envío de una recomendación de riego (Recommendation Sent).
\* **Comandos (Azul):** Acciones que disparan los eventos, tales como
Register User, Create Plot e Irrigation. \* **Actores (Amarillo):**
Identificación de los perfiles que ejecutan las acciones: Farmer
(Agricultor) y SME Owner (Empresario Agrícola). \* **Sistemas Externos
(Rosado):** Se integraron servicios externos críticos como Weather API
(para la obtención de pronósticos) y Email/SMS Gateway (para el despacho
de alertas preventivas). \* **Puntos de Fricción (Rojo):** Se
identificaron áreas de mejora como el "Registro manual lento" y la
"Falta de conexión en campo", las cuales guían el diseño de la solución
hacia la futura implementación de IoT.

### 2.5. Ubiquitous Language

A continuación, se define el glosario de términos técnicos del dominio
del negocio para asegurar una comunicación sin ambigüedades entre los
miembros del equipo y los stakeholders.

- **Plot (Parcela):** Área de tierra física registrada por el usuario
  donde se realiza el cultivo y monitoreo.
- **Crop (Cultivo):** Especie vegetal sembrada en una parcela (maíz,
  tomate, etc.) con requisitos hídricos específicos.
- **Soil Moisture (Humedad del Suelo):** Cantidad de agua presente en el
  suelo, utilizada como indicador principal para el riego.
- **Weather Alert (Alerta Climática):** Notificación preventiva sobre
  eventos como heladas, sequías o lluvias intensas que amenazan la
  cosecha.
- **Irrigation Schedule (Cronograma de Riego):** Planificación de las
  actividades de riego recomendadas por la plataforma basadas en datos
  de suelo y clima.
- **Yield (Rendimiento):** Cantidad de producto cosechado por unidad de
  área, utilizado como KPI de éxito.
- **Waste (Desperdicio):** Uso ineficiente del recurso hídrico o pérdida
  de insumos por riego inadecuado.


<br>
<br>  


# Capítulo III: Requirements Specification

## 3.1. User Stories


| **Épica** | **Título** |
|-----------|------------|
| EP01 | Landing Page |
| EP02 | Autenticación y Gestión de Cuenta |
| EP03 | Gestión de Parcelas |
| EP04 | Gestión de Cultivos |
| EP05 | Monitoreo y Registro de Datos del Suelo |
| EP06 | Recomendaciones de Riego |
| EP07 | Alertas Climáticas |
| EP08 | Dashboard y Reportes |
| EP09 | RESTful API - Identity | 
| EP10 | RESTful API - Soil Monitoring |
| EP11 | RESTful API - Farming |
| EP12 | RESTful API - Alerts |
| EP13 | RESTful API - Support & Dashboard |
| EP14 | RESTful API - IAM (Autenticación y Seguridad) |


<br>
<br>

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
| EP01 / US01 | Ver propuesta de valor de AgroTrack | Como visitante, quiero ver claramente qué problema resuelve AgroTrack, para entender si la plataforma es útil para mí. | **Escenario 1: Visitante ve la propuesta de valor** <br> **Given** el visitante ingresa al landing page, <br> **When** la página carga correctamente, <br> **Then** se muestra una sección principal con el problema que resuelve AgroTrack y un botón de llamada a la acción. | EP01 |
| EP01 / US02 | Ver sección de funcionalidades principales | Como visitante, quiero ver las funcionalidades que ofrece AgroTrack, para evaluar si cubre mis necesidades como agricultor o empresario. | **Escenario 1: Visitante visualiza las funcionalidades** <br> **Given** el visitante está en el landing page, <br> **When** navega hacia la sección de funcionalidades, <br> **Then** se muestran al menos 4 funcionalidades con ícono, título y descripción breve cada una. | EP01 |
| EP01 / US03 | Ver los segmentos objetivo a los que va dirigido | Como visitante, quiero saber a quiénes va dirigida la plataforma, para identificar si pertenezco al público objetivo. | **Escenario 1: Visitante identifica su segmento** <br> **Given** el visitante está en el landing page, <br> **When** llega a la sección de segmentos, <br> **Then** se muestran los dos perfiles (Agricultor y Empresario Agrícola) con una descripción clara de cada uno. | EP01 |
| EP01 / US04 | Ver planes y precios disponibles | Como visitante, quiero conocer los planes y precios de AgroTrack, para decidir si puedo pagarlo. | **Escenario 1: Visitante revisa los planes disponibles** <br> **Given** el visitante está en el landing page, <br> **When** navega a la sección de precios, <br> **Then** se muestran los planes disponibles con sus funcionalidades y precio. | EP01 |
| EP01 / US05 | Solicitar demo o acceso anticipado | Como visitante interesado, quiero dejar mis datos para solicitar una demo, para probar la plataforma antes de registrarme formalmente. | **Escenario 1: Visitante envía solicitud de demo exitosamente** <br> **Given** el visitante completa el formulario de demo con nombre y correo válidos, <br> **When** envía el formulario <br> **Then** se muestra un mensaje de confirmación indicando que su solicitud fue recibida. <br><br> **Escenario 2: Visitante intenta enviar el formulario vacío** <br> **Given** el visitante no completa los campos del formulario, <br> **When** presiona el botón de enviar, <br> **Then** se muestran mensajes de error indicando los campos obligatorios. | EP01 |
| EP01 / US06 | Ver testimonios o casos de uso reales | Como visitante, quiero leer experiencias de otros usuarios, para ganar confianza en la plataforma antes de registrarme. | **Escenario 1: Visitante visualiza los testimonios** <br> **Given** el visitante está en el landing page, <br> **When** llega a la sección de testimonios, <br> **Then** se muestran al menos 2 testimonios con nombre, perfil y comentario del usuario. | EP01 |
| EP01 / US07 | Navegar desde un menú fijo de secciones | Como visitante, quiero un menú de navegación siempre visible, para acceder rápidamente a cualquier sección del landing page. | **Escenario 1: Visitante navega usando el menú fijo** <br> **Given** el visitante está en cualquier parte del landing page, <br> **When** hace clic en una opción del menú, <br> **Then** la página hace scroll automático hacia la sección correspondiente. <br><br> **Escenario 2: El menú permanece visible al hacer scroll** <br> **Given** el visitante está haciendo scroll en la página, <br> **When** baja por el contenido, <br> **Then** el menú de navegación permanece fijo en la parte superior. | EP01 |
| EP01 / US08 | Visualizar el landing page desde cualquier dispositivo | Como visitante, quiero que el landing page se adapte a mi celular o tablet, para poder verlo bien desde cualquier dispositivo. | **Escenario 1: Visitante accede desde un celular** <br> **Given** el visitante abre el landing page desde un dispositivo móvil, <br> **When** la página carga, <br> **Then** el contenido se reorganiza correctamente sin elementos cortados ni scroll horizontal. <br><br> **Escenario 2: Visitante accede desde una tablet** <br> **Given** el visitante abre el landing page desde una tablet, <br> **When** la página carga, <br> **Then** el diseño se adapta correctamente al tamaño de pantalla. | EP01 |
| EP02 / US09 | Registrar una cuenta nueva | Como usuario nuevo, quiero crear una cuenta en AgroTrack, para acceder a todas las funcionalidades de la plataforma. | **Escenario 1: Usuario se registra exitosamente** <br> **Given** el usuario completa todos los campos del formulario con datos válidos, <br> **When** presiona el botón de registrarse, <br> **Then** se crea su cuenta y es redirigido al dashboard principal. <br><br> **Escenario 2: Correo ya existente** <br> **Given** el usuario ingresa un correo que ya está registrado, <br> **When** presiona el botón de registrarse, <br> **Then** se muestra un mensaje de error indicando que el correo ya está en uso. <br><br> **Escenario 3: Campos obligatorios vacíos** <br> **Given** el usuario no completa todos los campos requeridos, <br> **When** presiona el botón de registrarse, <br> **Then** se resaltan los campos vacíos con un mensaje de error. | EP02 |
| EP02 / US10 | Iniciar sesión con correo y contraseña | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña, para acceder a mi cuenta y mis datos. | **Escenario 1: Usuario inicia sesión correctamente** <br> **Given** el usuario ingresa un correo y contraseña válidos, <br> **When** presiona el botón de iniciar sesión, <br> **Then** es redirigido a su dashboard principal. <br><br> **Escenario 2: Credenciales incorrectas** <br> **Given** el usuario ingresa un correo o contraseña incorrectos, <br> **When** presiona el botón de iniciar sesión, <br> **Then** se muestra un mensaje de error indicando que las credenciales son inválidas. | EP02 |
| EP02 / US11 | Cerrar sesión | Como usuario autenticado, quiero cerrar sesión, para proteger mi cuenta cuando dejo de usar la plataforma. | **Escenario 1: Usuario cierra sesión exitosamente** <br> **Given** el usuario está autenticado en la plataforma, <br> **When** presiona la opción de cerrar sesión, <br> **Then** su sesión termina y es redirigido a la página de inicio de sesión. | EP02 |
| EP02 / US12 | Recuperar contraseña olvidada | Como usuario, quiero recuperar mi contraseña si la olvidé, para volver a acceder a mi cuenta sin perder mis datos. | **Escenario 1: Recuperación con correo válido** <br> **Given** el usuario ingresa un correo registrado en el formulario de recuperación, <br> **When** presiona el botón de enviar, <br> **Then** se muestra un mensaje indicando que recibirá instrucciones en su correo. <br><br> **Escenario 2: Correo no registrado** <br> **Given** el usuario ingresa un correo que no existe en el sistema, <br> **When** presiona el botón de enviar, <br> **Then** se muestra un mensaje de error indicando que el correo no está registrado. | EP02 |
| EP02 / US13 | Editar datos del perfil personal | Como usuario registrado, quiero editar mi información de perfil, para mantener mis datos actualizados. | **Escenario 1: Usuario actualiza su perfil correctamente** <br> **Given** el usuario modifica uno o más campos de su perfil con datos válidos, <br> **When** presiona el botón de guardar cambios, <br> **Then** los datos se actualizan y se muestra un mensaje de confirmación. <br><br> **Escenario 2: Campos obligatorios vacíos** <br> **Given** el usuario borra un campo obligatorio de su perfil, <br> **When** presiona el botón de guardar cambios, <br> **Then** se muestra un mensaje de error indicando los campos requeridos. | EP02 |
| EP02 / US14 | Seleccionar tipo de usuario al registrarse (Agricultor o Empresario Agrícola) | Como usuario nuevo, quiero elegir si soy Agricultor o Empresario Agrícola al registrarme, para que la plataforma me muestre las funcionalidades que corresponden a mi perfil. | **Escenario 1: Usuario selecciona el tipo Agricultor** <br> **Given** el usuario está en el formulario de registro, <br> **When** selecciona el tipo "Agricultor" y completa el registro, <br> **Then** accede a un dashboard con funcionalidades orientadas al agricultor. <br><br> **Escenario 2: Usuario selecciona el tipo Empresario Agrícola** <br> **Given** el usuario está en el formulario de registro, <br> **When** selecciona el tipo "Empresario Agrícola" y completa el registro, <br> **Then** accede a un dashboard con funcionalidades de gestión empresarial y métricas. | EP02 |
| EP03 / US15 | Registrar una nueva parcela | Como agricultor, quiero registrar una nueva parcela en la plataforma, para comenzar a hacer seguimiento de mis cultivos en ese terreno. | **Escenario 1: Parcela registrada exitosamente** <br> **Given** el agricultor completa el formulario con nombre, ubicación y tamaño de la parcela, <br> **When** presiona el botón de guardar, <br> **Then** la parcela queda registrada y aparece en su listado. <br><br> **Escenario 2: Nombre de parcela vacío** <br> **Given** el agricultor deja el campo nombre vacío, <br> **When** presiona el botón de guardar, <br> **Then** se muestra un mensaje de error indicando que el nombre es obligatorio. | EP03 |
| EP03 / US16 | Ver listado de mis parcelas | Como agricultor, quiero ver todas mis parcelas registradas en un solo lugar, para tener una vista general de mis terrenos. | **Escenario 1: Agricultor visualiza su listado de parcelas** <br> **Given** el agricultor tiene al menos una parcela registrada, <br> **When** accede a la sección de parcelas, <br> **Then** se muestran todas sus parcelas con nombre, ubicación y estado actual. <br><br> **Escenario 2: Sin parcelas registradas** <br> **Given** el agricultor no ha registrado ninguna parcela, <br> **When** accede a la sección de parcelas, <br> **Then** se muestra un mensaje indicando que no tiene parcelas y un botón para crear la primera. | EP03 |
| EP03 / US17 | Editar información de una parcela | Como agricultor, quiero editar los datos de una parcela, para corregir o actualizar su información cuando sea necesario. | **Escenario 1: Parcela editada exitosamente** <br> **Given** el agricultor selecciona una parcela y modifica sus datos con información válida, <br> **When** presiona el botón de guardar cambios, <br> **Then** los datos actualizados se guardan y se muestra un mensaje de confirmación. | EP03 |
| EP03 / US18 | Eliminar una parcela registrada | Como agricultor, quiero eliminar una parcela que ya no uso, para mantener mi listado limpio y organizado. | **Escenario 1: Parcela eliminada exitosamente** <br> **Given** el agricultor selecciona la opción de eliminar en una parcela, <br> **When** confirma la acción en el mensaje de advertencia, <br> **Then** la parcela desaparece del listado permanentemente. <br><br> **Escenario 2: Agricultor cancela la eliminación** <br> **Given** el agricultor selecciona la opción de eliminar en una parcela, <br> **When** cancela la acción en el mensaje de advertencia, <br> **Then** la parcela se mantiene en el listado sin cambios. | EP03 |
| EP03 / US19 | Ver detalle de una parcela específica | Como agricultor, quiero ver el detalle completo de una parcela, para revisar toda su información y el estado de sus cultivos. | **Escenario 1: Agricultor accede al detalle de una parcela** <br> **Given** el agricultor selecciona una parcela de su listado, <br> **When** la página de detalle carga, <br> **Then** se muestra la información completa de la parcela junto con sus cultivos activos y el estado del suelo. | EP03 |
| EP04 / US20 | Registrar un cultivo en una parcela | Como agricultor, quiero registrar un nuevo cultivo en una de mis parcelas, para llevar un control digital de lo que estoy sembrando. | **Escenario 1: Cultivo registrado exitosamente** <br> **Given** el agricultor selecciona una parcela y completa el formulario con tipo de cultivo y fecha de siembra, <br> **When** presiona el botón de guardar, <br> **Then** el cultivo queda registrado y aparece en el detalle de la parcela. <br><br> **Escenario 2: Campo tipo de cultivo vacío** <br> **Given** el agricultor deja el campo tipo de cultivo vacío, <br> **When** presiona el botón de guardar, <br> **Then** se muestra un mensaje de error indicando que el campo es obligatorio. | EP04 |
| EP04 / US21 | Ver los cultivos activos de una parcela | Como agricultor, quiero ver los cultivos activos de una parcela, para saber qué estoy cultivando actualmente en ese terreno. | **Escenario 1: Agricultor visualiza cultivos activos** <br> **Given** el agricultor tiene al menos un cultivo activo en una parcela, <br> **When** accede al detalle de esa parcela, <br> **Then** se muestran todos los cultivos activos con su tipo, fecha de siembra y estado. <br><br> **Escenario 2: Parcela sin cultivos activos** <br> **Given** la parcela no tiene cultivos activos registrados, <br> **When** el agricultor accede a su detalle, <br> **Then** se muestra un mensaje indicando que no hay cultivos activos y un botón para agregar uno. | EP04 |
| EP04 / US22 | Editar información de un cultivo | Como agricultor, quiero editar los datos de un cultivo registrado, para corregir errores o actualizar su información. | **Escenario 1: Cultivo editado exitosamente** <br> **Given** el agricultor selecciona un cultivo y modifica sus datos con información válida, <br> **When** presiona guardar cambios, <br> **Then** los nuevos datos quedan guardados y se muestra un mensaje de confirmación. | EP04 |
| EP04 / US23 | Marcar un cultivo como cosechado o finalizado | Como agricultor, quiero marcar un cultivo como finalizado, para registrar que ese ciclo de siembra ya terminó. | **Escenario 1: Cultivo finalizado exitosamente** <br> **Given** el agricultor selecciona un cultivo activo y elige la opción de marcar como cosechado, <br> **When** confirma la acción, <br> **Then** el cultivo cambia su estado a "Finalizado" y se mueve al historial de la parcela. <br><br> **Escenario 2: Cultivo ya finalizado** <br> **Given** el agricultor accede a un cultivo con estado "Finalizado", <br> **When** revisa sus opciones, <br> **Then** la opción de marcar como cosechado no está disponible. | EP04 |
| EP04 / US24 | Ver historial de cultivos anteriores por parcela | Como agricultor, quiero ver el historial de cultivos pasados de una parcela, para analizar qué sembré en temporadas anteriores y qué resultados tuve. | **Escenario 1: Agricultor revisa el historial de cultivos** <br> **Given** el agricultor tiene al menos un cultivo finalizado en una parcela, <br> **When** accede a la sección de historial de esa parcela, <br> **Then** se muestran los cultivos finalizados con su tipo, fecha de siembra y fecha de cosecha. | EP04 |
| EP05 / US25 | Ingresar manualmente datos de humedad del suelo | Como agricultor, quiero registrar manualmente el nivel de humedad del suelo de mi parcela, para que la plataforma pueda darme recomendaciones basadas en datos reales. | **Escenario 1: Humedad registrada exitosamente** <br> **Given** el agricultor ingresa un valor numérico de humedad entre 0 y 100, <br> **When** presiona el botón de guardar registro, <br> **Then** el dato queda almacenado con la fecha y hora del registro. <br><br> **Escenario 2: Valor fuera del rango permitido** <br> **Given** el agricultor ingresa un valor menor a 0 o mayor a 100, <br> **When** presiona el botón de guardar registro, <br> **Then** se muestra un mensaje de error indicando que el valor debe estar entre 0 y 100. | EP05 |
| EP05 / US26 | Ingresar manualmente datos de temperatura del suelo | Como agricultor, quiero registrar la temperatura del suelo de mi parcela, para tener un historial de condiciones del terreno. | **Escenario 1: Temperatura registrada exitosamente** <br> **Given** el agricultor ingresa un valor numérico de temperatura válido, <br> **When** presiona el botón de guardar registro, <br> **Then** el dato queda almacenado con la fecha y hora del registro. <br><br> **Escenario 2: Valor no numérico** <br> **Given** el agricultor ingresa letras o caracteres especiales en el campo de temperatura, <br> **When** presiona el botón de guardar registro, <br> **Then** se muestra un mensaje de error indicando que el valor debe ser numérico. | EP05 |
| EP05 / US27 | Ver el estado actual del suelo de una parcela | Como agricultor, quiero ver el estado actual del suelo de mi parcela, para saber si necesita riego o está en condiciones adecuadas. | **Escenario 1: Agricultor visualiza el estado actual del suelo** <br> **Given** el agricultor tiene al menos un registro de suelo en su parcela, <br> **When** accede al detalle de esa parcela, <br> **Then** se muestra el último valor de humedad y temperatura registrados junto con un indicador visual de estado (bajo, normal, alto). <br><br> **Escenario 2: Sin registros de suelo** <br> **Given** la parcela no tiene registros de suelo, <br> **When** el agricultor accede a su detalle, <br> **Then** se muestra un mensaje indicando que aún no hay datos del suelo registrados. | EP05 |
| EP05 / US28 | Ver historial de registros del suelo por parcela | Como agricultor, quiero ver el historial de datos del suelo de una parcela, para identificar cómo han variado las condiciones con el tiempo. | **Escenario 1: Agricultor revisa el historial del suelo** <br> **Given** el agricultor tiene múltiples registros de suelo en una parcela, <br> **When** accede a la sección de historial del suelo, <br> **Then** se muestran los registros ordenados del más reciente al más antiguo con fecha, humedad y temperatura. | EP05 |
| EP06 / US29 | Recibir recomendación de riego basada en datos del suelo | Como agricultor, quiero recibir una recomendación de riego según el nivel de humedad registrado, para tomar decisiones más informadas y no basarme solo en mi intuición. | **Escenario 1: Humedad baja genera recomendación de riego** <br> **Given** el agricultor registra un nivel de humedad menor al 40%, <br> **When** el sistema procesa el dato, <br> **Then** se muestra una recomendación indicando que la parcela necesita riego. <br><br> **Escenario 2: Humedad normal sin recomendación** <br> **Given** el agricultor registra un nivel de humedad entre 40% y 70%, <br> **When** el sistema procesa el dato, <br> **Then** se muestra un mensaje indicando que la parcela está en condiciones adecuadas. <br><br> **Escenario 3: Humedad alta genera advertencia** <br> **Given** el agricultor registra un nivel de humedad mayor al 70%, <br> **When** el sistema procesa el dato, <br> **Then** se muestra una advertencia indicando que el suelo tiene exceso de humedad y no debe regarse. | EP06 |
| EP06 / US30 | Ver el cronograma de riego sugerido por la plataforma | Como agricultor, quiero ver un cronograma de riego recomendado para mi parcela, para planificar mis actividades de riego con anticipación. | **Escenario 1: Agricultor visualiza el cronograma de riego** <br> **Given** el agricultor accede a la sección de cronograma de riego de una parcela, <br> **When** la sección carga, <br> **Then** se muestra una lista de fechas y horarios sugeridos de riego basados en los datos del suelo registrados. | EP06 |
| EP06 / US31 | Confirmar o rechazar una recomendación de riego | Como agricultor, quiero poder confirmar o rechazar una recomendación de riego, para registrar si seguí o no el consejo de la plataforma. | **Escenario 1: Agricultor confirma una recomendación** <br> **Given** el agricultor recibe una recomendación de riego, <br> **When** presiona el botón de confirmar, <br> **Then** la recomendación queda registrada como aplicada en el historial. <br><br> **Escenario 2: Agricultor rechaza una recomendación** <br> **Given** el agricultor recibe una recomendación de riego, <br> **When** presiona el botón de rechazar, <br> **Then** la recomendación queda registrada como no aplicada en el historial. | EP06 |
| EP06 / US32 | Ver historial de riegos aplicados en una parcela | Como agricultor, quiero ver el historial de riegos que apliqué en una parcela, para revisar con qué frecuencia regué y si seguí las recomendaciones. | **Escenario 1: Agricultor revisa su historial de riegos** <br> **Given** el agricultor tiene al menos un riego confirmado en una parcela, <br> **When** accede a la sección de historial de riegos, <br> **Then** se muestran los registros con fecha, hora y si la recomendación fue seguida o no. | EP06 |
| EP07 / US33 | Recibir alerta ante riesgo de helada | Como agricultor, quiero recibir una alerta cuando se pronostique una helada en mi zona, para proteger mis cultivos con anticipación. | **Escenario 1: Sistema detecta riesgo de helada** <br> **Given** el sistema obtiene un pronóstico de temperatura menor a 0°C en la zona de una parcela, <br> **When** se procesa la alerta, <br> **Then** se muestra una notificación visible en el dashboard indicando el riesgo de helada y la fecha estimada. <br><br> **Escenario 2: Sin riesgo de helada** <br> **Given** el pronóstico de temperatura en la zona es mayor a 0°C, <br> **When** el sistema revisa las condiciones, <br> **Then** no se genera ninguna alerta de helada. | EP07 |
| EP07 / US34 | Recibir alerta ante riesgo de sequía | Como agricultor, quiero recibir una alerta cuando se pronostique un período de sequía prolongada, para anticipar mis decisiones de riego. | **Escenario 1: Sistema detecta riesgo de sequía** <br> **Given** el sistema detecta un pronóstico de ausencia de lluvias por más de 7 días consecutivos, <br> **When** se procesa la alerta, <br> **Then** se muestra una notificación en el dashboard indicando el riesgo de sequía y los días proyectados sin lluvia. | EP07 |
| EP07 / US35 | Recibir alerta ante lluvias intensas previstas | Como agricultor, quiero recibir una alerta cuando se esperen lluvias intensas, para evitar el exceso de riego y proteger mis cultivos. | **Escenario 1: Sistema detecta lluvia intensa** <br> **Given** el pronóstico indica precipitaciones intensas en la zona de la parcela, <br> **When** el sistema procesa la alerta, <br> **Then** se muestra una notificación en el dashboard indicando la lluvia esperada y recomendando pausar el riego. | EP07 |
| EP07 / US36 | Ver historial de alertas climáticas recibidas | Como agricultor, quiero ver todas las alertas climáticas que recibí, para revisar qué eventos ocurrieron y cómo respondí ante ellos. | **Escenario 1: Agricultor revisa su historial de alertas** <br> **Given** el agricultor tiene al menos una alerta registrada, <br> **When** accede a la sección de historial de alertas, <br> **Then** se muestran las alertas ordenadas por fecha con tipo de alerta y descripción. <br><br> **Escenario 2: Sin alertas registradas** <br> **Given** el agricultor no tiene alertas registradas, <br> **When** accede al historial de alertas, <br> **Then** se muestra un mensaje indicando que no hay alertas registradas hasta el momento. | EP07 |
| EP07 / US37 | Configurar qué tipo de alertas quiero recibir | Como agricultor, quiero elegir qué tipos de alertas climáticas quiero recibir, para no saturarme de notificaciones que no me sean útiles. | **Escenario 1: Agricultor activa un tipo de alerta** <br> **Given** el agricultor accede a la configuración de alertas, <br> **When** activa la opción de un tipo de alerta específico, <br> **Then** ese tipo de alerta queda habilitado y el sistema lo incluirá en las notificaciones futuras. <br><br> **Escenario 2: Agricultor desactiva un tipo de alerta** <br> **Given** el agricultor accede a la configuración de alertas, <br> **When** desactiva la opción de un tipo de alerta específico, <br> **Then** ese tipo de alerta queda deshabilitado y el sistema dejará de generarla. | EP07 |
| EP08 / US38 | Ver panel de control con resumen de todas mis parcelas | Como empresario agrícola, quiero ver un panel de control con el estado de todas mis parcelas, para tener visibilidad centralizada de mi operación sin depender de reportes manuales. | **Escenario 1: Empresario visualiza el panel con parcelas** <br> **Given** el empresario tiene al menos una parcela registrada, <br> **When** accede a su dashboard principal, <br> **Then** se muestra un resumen de cada parcela con su estado actual de humedad, cultivo activo y última alerta recibida. <br><br> **Escenario 2: Empresario sin parcelas registradas** <br> **Given** el empresario no tiene parcelas registradas, <br> **When** accede a su dashboard principal, <br> **Then** se muestra un mensaje invitándolo a registrar su primera parcela. | EP08 |
| EP08 / US39 | Ver rendimiento por parcela | Como empresario agrícola, quiero ver el rendimiento de cada parcela, para identificar cuáles están siendo más productivas y tomar decisiones de inversión. | **Escenario 1: Empresario visualiza el rendimiento de sus parcelas** <br> **Given** el empresario tiene cultivos finalizados con datos registrados, <br> **When** accede a la sección de rendimiento, <br> **Then** se muestran métricas de producción por parcela ordenadas de mayor a menor rendimiento. | EP08 |
| EP08 / US40 | Ver porcentaje de pérdidas estimadas por parcela | Como empresario agrícola, quiero ver el porcentaje de pérdidas estimadas por parcela, para identificar dónde estoy perdiendo más y tomar acciones correctivas. | **Escenario 1: Empresario visualiza las pérdidas estimadas** <br> **Given** el empresario tiene registros de producción en sus parcelas, <br> **When** accede a la sección de pérdidas, <br> **Then** se muestra el porcentaje de pérdidas estimado por parcela junto con las causas registradas. | EP08 |
| EP08 / US41 | Ver consumo de agua registrado por temporada | Como empresario agrícola, quiero ver cuánta agua se ha consumido por temporada en cada parcela, para evaluar la eficiencia del riego y reducir costos operativos. | **Escenario 1: Empresario revisa el consumo de agua** <br> **Given** el empresario tiene registros de riego en sus parcelas, <br> **When** accede a la sección de consumo de agua, <br> **Then** se muestra el consumo total de agua por parcela agrupado por temporada. | EP08 |
| EP08 / US42 | Exportar reporte de producción en formato PDF o Excel | Como empresario agrícola, quiero exportar un reporte de producción de mis parcelas, para compartirlo con mi equipo o analizarlo fuera de la plataforma. | **Escenario 1: Exportación en PDF exitosa** <br> **Given** el empresario accede a la sección de reportes y selecciona el formato PDF, <br> **When** presiona el botón de exportar, <br> **Then** se descarga un archivo PDF con el resumen de producción de sus parcelas. <br><br> **Escenario 2: Exportación en Excel exitosa** <br> **Given** el empresario accede a la sección de reportes y selecciona el formato Excel, <br> **When** presiona el botón de exportar, <br> **Then** se descarga un archivo Excel con los datos de producción organizados por parcela y temporada. <br><br> **Escenario 3: Sin datos para exportar** <br> **Given** el empresario no tiene registros de producción, <br> **When** intenta exportar el reporte, <br> **Then** se muestra un mensaje indicando que no hay datos disponibles para generar el reporte. | EP08 |
| EP09 / TS01 | Endpoint para registrar un usuario | Como developer, quiero un endpoint POST /users para registrar un nuevo usuario, para que el frontend pueda crear cuentas desde el formulario de registro. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con datos válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el objeto del usuario creado, además de crear automáticamente una AlertPreference para ese usuario. <br><br> **Escenario 2: Correo ya registrado** <br> **Given** el developer envía una solicitud POST con un correo ya existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 409 indicando conflicto de correo duplicado. <br><br> **Escenario 3: Campos obligatorios faltantes** <br> **Given** el developer envía una solicitud POST con campos requeridos vacíos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 y un mensaje indicando los campos faltantes. | EP09 |
| EP09 / TS02 | Endpoint para obtener un usuario por ID | Como developer, quiero un endpoint GET /users/{id} para obtener los datos de un usuario específico, para que el frontend pueda cargar el perfil del usuario autenticado. | **Escenario 1: Usuario encontrado** <br> **Given** el developer envía una solicitud GET con un ID de usuario válido, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y los datos del usuario. <br><br> **Escenario 2: Usuario no encontrado** <br> **Given** el developer envía una solicitud GET con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP09 |
| EP09 / TS03 | Endpoint para actualizar un usuario | Como developer, quiero un endpoint PUT /users/{id} para actualizar los datos de un usuario, para que el frontend pueda permitir al usuario editar su perfil. | **Escenario 1: Actualización exitosa** <br> **Given** el developer envía una solicitud PUT con datos válidos y un ID existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el objeto actualizado con el campo updated_at renovado. <br><br> **Escenario 2: Usuario no encontrado** <br> **Given** el developer envía una solicitud PUT con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP09 |
| EP09 / TS04 | Endpoint para listar planes de suscripción | Como developer, quiero un endpoint GET /plans para obtener todos los planes disponibles, para que el frontend pueda mostrar las opciones de suscripción al usuario. | **Escenario 1: Listado exitoso** <br> **Given** el developer envía una solicitud GET a /plans, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un array con los 3 planes (BASIC, PRO, ENTERPRISE) con sus características (precio, máximo de parcelas, funcionalidades habilitadas). | EP09 |
| EP09 / TS05 | Endpoint para obtener preferencias de alertas | Como developer, quiero un endpoint GET /alert_preferences con filtro opcional por user_id, para que el frontend pueda cargar las preferencias de alerta del usuario activo. | **Escenario 1: Filtrado por user_id** <br> **Given** el developer envía una solicitud GET con el parámetro user_id, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y la preferencia de alerta correspondiente al usuario. <br><br> **Escenario 2: Sin filtro** <br> **Given** el developer envía una solicitud GET sin parámetros, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y todas las preferencias de alerta registradas. | EP09 |
| EP09 / TS06 | Endpoint para actualizar preferencias de alertas | Como developer, quiero un endpoint PUT /alert_preferences/{id} para actualizar los toggles de alerta de un usuario, para que el frontend pueda guardar las preferencias de notificación configuradas por el usuario. | **Escenario 1: Actualización exitosa** <br> **Given** el developer envía una solicitud PUT con los valores de los toggles y un ID existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el objeto de preferencias actualizado. <br><br> **Escenario 2: Preferencia no encontrada** <br> **Given** el developer envía una solicitud PUT con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP09 |
| EP10 / TS07 | Endpoint para registrar una lectura de suelo | Como developer, quiero un endpoint POST /soil_records para registrar la humedad y temperatura de una parcela, para que el frontend pueda almacenar las mediciones realizadas desde la pestaña Soil. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con un plot_id, humedad y temperatura válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el objeto de la lectura de suelo creada, incluyendo su identificador y fecha de registro. <br><br> **Escenario 2: Campos obligatorios faltantes** <br> **Given** el developer envía una solicitud POST sin plot_id, humedad o temperatura, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 y un mensaje indicando los datos inválidos o faltantes. <br><br> **Escenario 3: Humedad fuera del rango permitido** <br> **Given** el developer envía una humedad menor que 0 o mayor que 100, <br> **When** el servidor valida la solicitud, <br> **Then** responde con status 400 indicando que la humedad debe encontrarse entre 0 y 100. | EP10 |
| EP10 / TS08 | Endpoint para listar lecturas de suelo | Como developer, quiero un endpoint GET /soil_records con filtro opcional por plot_id, para que el frontend pueda cargar el historial de lecturas de la parcela seleccionada. | **Escenario 1: Filtrado por parcela** <br> **Given** el developer envía una solicitud GET con el parámetro plot_id, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y las lecturas correspondientes a esa parcela, ordenadas desde la más reciente. <br><br> **Escenario 2: Consulta sin filtro** <br> **Given** el developer envía una solicitud GET sin parámetros, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y todas las lecturas de suelo registradas. <br><br> **Escenario 3: Parcela sin lecturas** <br> **Given** el developer consulta un plot_id que no tiene lecturas registradas, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un arreglo vacío. | EP10 |
| EP10 / TS09 | Endpoint para eliminar una lectura de suelo | Como developer, quiero un endpoint DELETE /soil_records/{id} para eliminar una lectura de suelo, para que el sistema pueda retirar registros que ya no deben mantenerse. | **Escenario 1: Eliminación exitosa** <br> **Given** el developer envía una solicitud DELETE con el ID de una lectura existente, <br> **When** el servidor procesa la solicitud, <br> **Then** elimina la lectura y responde con status 200 y un mensaje de confirmación. <br><br> **Escenario 2: Lectura no encontrada** <br> **Given** el developer envía una solicitud DELETE con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404 indicando que la lectura de suelo no fue encontrada. | EP10 |
| EP10 / TS10 | Endpoint para registrar una recomendación de riego | Como developer, quiero un endpoint POST /irrigation_recommendations para registrar una recomendación asociada a una parcela y una lectura de suelo, para que el frontend pueda guardar las decisiones de riego del usuario. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con plot_id, soil_record_id, mensaje, urgencia y estado válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el objeto de la recomendación de riego creada. <br><br> **Escenario 2: Lectura de suelo inexistente** <br> **Given** el developer envía una solicitud POST con un soil_record_id que no existe, <br> **When** el servidor valida la solicitud, <br> **Then** responde con status 400 indicando que la lectura de suelo no existe. <br><br> **Escenario 3: Estado o urgencia inválidos** <br> **Given** el developer envía un estado o nivel de urgencia que no pertenece a los valores permitidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 indicando que los datos enviados son inválidos. | EP10 |
| EP10 / TS11 | Endpoint para listar recomendaciones de riego | Como developer, quiero un endpoint GET /irrigation_recommendations con filtro opcional por plot_id, para que el frontend pueda cargar el historial de recomendaciones y decisiones de riego de una parcela. | **Escenario 1: Filtrado por parcela** <br> **Given** el developer envía una solicitud GET con el parámetro plot_id, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y las recomendaciones asociadas a esa parcela, ordenadas desde la más reciente. <br><br> **Escenario 2: Consulta sin filtro** <br> **Given** el developer envía una solicitud GET sin parámetros, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y todas las recomendaciones de riego registradas. <br><br> **Escenario 3: Parcela sin recomendaciones** <br> **Given** el developer consulta un plot_id que no tiene recomendaciones registradas, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un arreglo vacío. | EP10 |
| EP10 / TS12 | Endpoint para actualizar una recomendación de riego | Como developer, quiero un endpoint PUT /irrigation_recommendations/{id} para actualizar el estado de una recomendación, para que el frontend pueda registrar si el usuario confirmó o rechazó la asesoría de riego. | **Escenario 1: Confirmación exitosa** <br> **Given** el developer envía una solicitud PUT con un ID existente y el estado CONFIRMED, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y la recomendación actualizada, incluyendo la fecha de respuesta. <br><br> **Escenario 2: Rechazo exitoso** <br> **Given** el developer envía una solicitud PUT con un ID existente y el estado REJECTED, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y la recomendación actualizada, incluyendo la fecha de respuesta. <br><br> **Escenario 3: Recomendación no encontrada** <br> **Given** el developer envía una solicitud PUT con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404 indicando que la recomendación no fue encontrada. <br><br> **Escenario 4: Estado inválido** <br> **Given** el developer envía una solicitud PUT con un estado no permitido, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 indicando que el estado enviado es inválido. | EP10 |
| EP10 / TS13 | Endpoint para eliminar una recomendación de riego | Como developer, quiero un endpoint DELETE /irrigation_recommendations/{id} para eliminar una recomendación de riego, para que el sistema pueda retirar registros que ya no deben conservarse. | **Escenario 1: Eliminación exitosa** <br> **Given** el developer envía una solicitud DELETE con el ID de una recomendación existente, <br> **When** el servidor procesa la solicitud, <br> **Then** elimina la recomendación y responde con status 200 y un mensaje de confirmación. <br><br> **Escenario 2: Recomendación no encontrada** <br> **Given** el developer envía una solicitud DELETE con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404 indicando que la recomendación de riego no fue encontrada. | EP10 |
| EP11 / TS14 | Endpoint para listar parcelas | Como developer, quiero un endpoint GET /plots con filtro opcional por userId, para que el frontend pueda cargar todas las parcelas registradas y filtrarlas por usuario. | **Escenario 1: Listado exitoso sin filtro** <br> **Given** el developer envía una solicitud GET a /plots sin parámetros, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un array con todas las parcelas registradas. <br><br> **Escenario 2: Filtrado por userId** <br> **Given** el developer envía una solicitud GET con el parámetro userId, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y solo las parcelas del usuario indicado. <br><br> **Escenario 3: Sin parcelas registradas** <br> **Given** no existen parcelas en el sistema, <br> **When** el developer envía la solicitud, <br> **Then** responde con status 200 y un arreglo vacío. | EP11 |
| EP11 / TS15 | Endpoint para registrar una parcela | Como developer, quiero un endpoint POST /plots para registrar una nueva parcela, para que el frontend pueda crear parcelas desde el formulario de gestión del usuario. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con userId, name, location y sizeHectares válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el objeto de la parcela creada con estado ACTIVE. <br><br> **Escenario 2: Campos obligatorios faltantes** <br> **Given** el developer envía una solicitud POST sin algún campo requerido, <br> **When** el servidor valida la solicitud, <br> **Then** responde con status 400 indicando los campos faltantes o inválidos. | EP11 |
| EP11 / TS16 | Endpoint para actualizar una parcela | Como developer, quiero un endpoint PUT /plots/{id} para actualizar los datos de una parcela, para que el frontend pueda guardar cambios en el nombre, ubicación o tamaño de la parcela. | **Escenario 1: Actualización exitosa** <br> **Given** el developer envía una solicitud PUT con datos válidos y un ID de parcela existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el objeto de la parcela actualizado. <br><br> **Escenario 2: Parcela no encontrada** <br> **Given** el developer envía una solicitud PUT con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP11 |
| EP11 / TS17 | Endpoint para desactivar una parcela | Como developer, quiero un endpoint DELETE /plots/{id} para desactivar una parcela, para que el frontend pueda retirar parcelas del listado activo del usuario cambiando su estado a DELETED. | **Escenario 1: Desactivación exitosa** <br> **Given** el developer envía una solicitud DELETE con un ID de parcela existente, <br> **When** el servidor procesa la solicitud, <br> **Then** cambia el estado de la parcela a DELETED y responde con status 204. <br><br> **Escenario 2: Parcela no encontrada** <br> **Given** el developer envía una solicitud DELETE con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP11 |
| EP11 / TS18 | Endpoint para listar cultivos | Como developer, quiero un endpoint GET /crops con filtro opcional por plotId, para que el frontend pueda cargar todos los cultivos registrados y filtrarlos por parcela en memoria. | **Escenario 1: Listado exitoso sin filtro** <br> **Given** el developer envía una solicitud GET a /crops sin parámetros, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un array con todos los cultivos registrados. <br><br> **Escenario 2: Filtrado por plotId** <br> **Given** el developer envía una solicitud GET con el parámetro plotId, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y solo los cultivos de la parcela indicada. <br><br> **Escenario 3: Sin cultivos registrados** <br> **Given** no existen cultivos en el sistema, <br> **When** el developer envía la solicitud, <br> **Then** responde con status 200 y un arreglo vacío. | EP11 |
| EP11 / TS19 | Endpoint para registrar un cultivo | Como developer, quiero un endpoint POST /crops para registrar un cultivo en una parcela, para que el frontend pueda asociar un nuevo cultivo a la parcela seleccionada por el usuario. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con plotId, type y sowingDate válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el objeto del cultivo creado con estado ACTIVE. <br><br> **Escenario 2: Campos obligatorios faltantes** <br> **Given** el developer envía una solicitud POST sin algún campo requerido, <br> **When** el servidor valida la solicitud, <br> **Then** responde con status 400 indicando los campos faltantes o inválidos. | EP11 |
| EP11 / TS20 | Endpoint para actualizar un cultivo | Como developer, quiero un endpoint PUT /crops/{id} para actualizar los datos de un cultivo, para que el frontend pueda guardar cambios en el tipo, estado o fechas del cultivo registrado. | **Escenario 1: Actualización exitosa** <br> **Given** el developer envía una solicitud PUT con datos válidos y un ID de cultivo existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el objeto del cultivo actualizado. <br><br> **Escenario 2: Cultivo no encontrado** <br> **Given** el developer envía una solicitud PUT con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP11 |
| EP11 / TS21 | Endpoint para eliminar un cultivo | Como developer, quiero un endpoint DELETE /crops/{id} para eliminar un cultivo, para que el sistema pueda retirar cultivos del listado de la parcela cuando el usuario los elimine. | **Escenario 1: Eliminación exitosa** <br> **Given** el developer envía una solicitud DELETE con el ID de un cultivo existente, <br> **When** el servidor procesa la solicitud, <br> **Then** elimina el cultivo y responde con status 204. <br><br> **Escenario 2: Cultivo no encontrado** <br> **Given** el developer envía una solicitud DELETE con un ID inexistente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP11 |
| EP12 / TS22 | Endpoint para obtener alertas climáticas por ciudad | Como developer, quiero un endpoint GET /alerts?city={city} que consulte la API de OpenWeather y devuelva alertas climáticas generadas, para que el frontend pueda mostrar al usuario los riesgos climáticos actuales sin exponer la API key en el cliente. | **Escenario 1: Ciudad con alertas** <br> **Given** el developer envía una solicitud GET con un nombre de ciudad válido, <br> **When** el servidor consulta OpenWeather y detecta condiciones de riesgo, <br> **Then** responde con status 200 y un array de alertas con título, descripción, urgencia y timestamp de generación. <br><br> **Escenario 2: Ciudad sin alertas activas** <br> **Given** el developer envía una solicitud GET con una ciudad con condiciones climáticas normales, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y un arreglo vacío. <br><br> **Escenario 3: Ciudad no encontrada** <br> **Given** el developer envía una solicitud GET con un nombre de ciudad que no existe en OpenWeather, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404 indicando que la ciudad no fue encontrada. <br><br> **Escenario 4: Parámetro city faltante** <br> **Given** el developer envía una solicitud GET sin el parámetro city, <br> **When** el servidor valida la solicitud, <br> **Then** responde con status 400 indicando que el nombre de la ciudad es requerido. | EP12 |
| EP13 / TS23 | Endpoint para listar resúmenes de rendimiento | Como developer, quiero un endpoint GET `/yield_summaries` para obtener todos los resúmenes de rendimiento agrícola filtrando opcionalmente por `user_id`, para que el frontend pueda mostrar las métricas de rendimiento por hectárea y temporada en el dashboard. | **Escenario 1: Listado exitoso**<br>**Given** el developer envía una solicitud GET a `/yield_summaries` con un `user_id` existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array de resúmenes de rendimiento (`id`, `plot_id`, `yield_per_hectare`, `season`, `calculated_at`) asociados a ese usuario.<br><br>**Escenario 2: Usuario sin resúmenes**<br>**Given** el developer envía una solicitud GET a `/yield_summaries` con un `user_id` que no tiene registros,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array vacío. | EP13 |
| EP13 / TS24 | Endpoint para obtener resumen de rendimiento por ID | Como developer, quiero un endpoint GET `/yield_summaries/{id}` para recuperar un resumen de rendimiento específico por su identificador, para que el frontend pueda mostrar el detalle completo de una métrica individual. | **Escenario 1: Consulta exitosa**<br>**Given** el developer envía una solicitud GET a `/yield_summaries/{id}` con un ID existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y el objeto completo (`plot_id`, `yield_per_hectare`, `season`, `calculated_at`).<br><br>**Escenario 2: Resumen no encontrado**<br>**Given** el developer envía una solicitud GET a `/yield_summaries/{id}` con un ID inexistente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 404. | EP13 |
| EP13 / TS25 | Endpoint para listar resúmenes de pérdidas | Como developer, quiero un endpoint GET `/loss_summaries` para obtener todos los resúmenes de pérdidas agrícolas filtrando opcionalmente por `user_id`, para que el frontend pueda mostrar el porcentaje de pérdida y su causa por temporada en el dashboard. | **Escenario 1: Listado exitoso**<br>**Given** el developer envía una solicitud GET a `/loss_summaries` con un `user_id` existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array de resúmenes de pérdidas (`id`, `plot_id`, `loss_percentage`, `cause`, `season`, `calculated_at`).<br><br>**Escenario 2: Usuario sin resúmenes**<br>**Given** el developer envía una solicitud GET a `/loss_summaries` con un `user_id` que no tiene registros,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array vacío. | EP13 |
| EP13 / TS26 | Endpoint para obtener resumen de pérdidas por ID | Como developer, quiero un endpoint GET `/loss_summaries/{id}` para recuperar un resumen de pérdidas específico por su identificador, para que el frontend pueda mostrar el detalle de una métrica de pérdida individual. | **Escenario 1: Consulta exitosa**<br>**Given** el developer envía una solicitud GET a `/loss_summaries/{id}` con un ID existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y el objeto completo (`loss_percentage`, `cause`, `season`, `calculated_at`).<br><br>**Escenario 2: Resumen no encontrado**<br>**Given** el developer envía una solicitud GET a `/loss_summaries/{id}` con un ID inexistente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 404. | EP13 |
| EP13 / TS27 | Endpoint para listar consumos de agua | Como developer, quiero un endpoint GET `/water_consumptions` para obtener todos los registros de consumo de agua filtrando opcionalmente por `user_id`, para que el frontend pueda mostrar el total de litros consumidos por parcela y temporada en el dashboard. | **Escenario 1: Listado exitoso**<br>**Given** el developer envía una solicitud GET a `/water_consumptions` con un `user_id` existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array de consumos de agua (`id`, `plot_id`, `total_liters`, `season`, `calculated_at`).<br><br>**Escenario 2: Usuario sin registros**<br>**Given** el developer envía una solicitud GET a `/water_consumptions` con un `user_id` que no tiene registros,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array vacío. | EP13 |
| EP13 / TS28 | Endpoint para obtener consumo de agua por ID | Como developer, quiero un endpoint GET `/water_consumptions/{id}` para recuperar un registro de consumo de agua específico por su identificador, para que el frontend pueda mostrar el detalle de un consumo individual. | **Escenario 1: Consulta exitosa**<br>**Given** el developer envía una solicitud GET a `/water_consumptions/{id}` con un ID existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y el objeto completo (`plot_id`, `total_liters`, `season`, `calculated_at`).<br><br>**Escenario 2: Registro no encontrado**<br>**Given** el developer envía una solicitud GET a `/water_consumptions/{id}` con un ID inexistente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 404. | EP13 |
| EP13 / TS29 | Endpoint para listar tickets de soporte | Como developer, quiero un endpoint GET `/support_tickets` para obtener todos los tickets de soporte filtrando opcionalmente por `user_id`, para que el frontend pueda mostrar el historial completo de solicitudes de soporte del agricultor con su estado actual. | **Escenario 1: Listado exitoso**<br>**Given** el developer envía una solicitud GET a `/support_tickets` con un `user_id` existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array de tickets (`id`, `user_id`, `subject`, `message`, `status`, `created_at`, `responded_at`).<br><br>**Escenario 2: Usuario sin tickets**<br>**Given** el developer envía una solicitud GET a `/support_tickets` con un `user_id` que no tiene tickets registrados,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y un array vacío. | EP13 |
| EP13 / TS30 | Endpoint para obtener ticket de soporte por ID | Como developer, quiero un endpoint GET `/support_tickets/{id}` para recuperar un ticket de soporte específico por su identificador, para que el frontend pueda mostrar el detalle completo de un ticket. | **Escenario 1: Consulta exitosa**<br>**Given** el developer envía una solicitud GET a `/support_tickets/{id}` con un ID existente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 200 y el objeto completo (`subject`, `message`, `status`, `created_at`, `responded_at`).<br><br>**Escenario 2: Ticket no encontrado**<br>**Given** el developer envía una solicitud GET a `/support_tickets/{id}` con un ID inexistente,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 404. | EP13 |
| EP13 / TS31 | Endpoint para crear un ticket de soporte | Como developer, quiero un endpoint POST `/support_tickets` con body `{ user_id, subject, message }` para registrar un nuevo ticket de soporte con estado inicial OPEN, para que el frontend pueda permitir al usuario enviar una solicitud de ayuda al equipo de soporte. | **Escenario 1: Creación exitosa**<br>**Given** el developer envía una solicitud POST a `/support_tickets` con `user_id`, `subject` y `message` válidos,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 201 y el ticket creado con `status: OPEN` y `created_at` poblado.<br><br>**Escenario 2: Datos inválidos**<br>**Given** el developer envía una solicitud POST a `/support_tickets` sin `subject` o `message`,<br>**When** el servidor procesa la solicitud,<br>**Then** responde con status 400 indicando los campos requeridos faltantes. | EP13 |
| EP14 / TS32 | Endpoint para registrar credenciales de una cuenta (sign-up) | Como developer, quiero un endpoint POST /authentication/sign-up que reciba email, password y plan, para que el frontend pueda crear la credencial de acceso de un usuario nuevo y recibir de inmediato un token de sesión. | **Escenario 1: Registro exitoso** <br> **Given** el developer envía una solicitud POST con email, password y plan válidos (BASIC/PRO/ENTERPRISE), <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 y el id de la credencial creada, el email, los roles derivados del plan (FARMER para BASIC/PRO, AGRICULTURAL_MANAGER para ENTERPRISE) y un token JWT. <br><br> **Escenario 2: Email ya registrado** <br> **Given** el developer envía un email que ya existe como credencial IAM, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 409 indicando conflicto de correo duplicado. <br><br> **Escenario 3: Campos obligatorios faltantes** <br> **Given** el developer envía la solicitud sin email, password o plan, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 indicando los campos faltantes. | EP14 |
| EP14 / TS33 | Endpoint para iniciar sesión (sign-in) | Como developer, quiero un endpoint POST /authentication/sign-in que reciba email y password, para que el frontend pueda autenticar a un usuario ya registrado y obtener su token de sesión. | **Escenario 1: Login exitoso** <br> **Given** el developer envía una solicitud POST con email y password válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el id, email, roles y token JWT del usuario. <br><br> **Escenario 2: Password incorrecto** <br> **Given** el email existe pero el password no coincide, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 400 indicando credenciales inválidas. <br><br> **Escenario 3: Email no registrado** <br> **Given** el email no corresponde a ninguna credencial existente, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. | EP14 |
| EP14 / TS34 | Endpoint para listar los roles disponibles | Como developer, quiero un endpoint GET /roles que devuelva todos los roles IAM sembrados en el sistema, para que el frontend pueda mostrarlos o validarlos donde se requiera. | **Escenario 1: Listado exitoso** <br> **Given** el sistema tiene los roles sembrados al arrancar (ROLE_FARMER, ROLE_AGRICULTURAL_MANAGER, ROLE_ADMIN), <br> **When** el developer envía una solicitud GET a /roles, <br> **Then** responde con status 200 y el arreglo con los roles disponibles. | EP14 |
| EP14 / TS35 | Endpoint para completar el perfil de negocio de una cuenta registrada | Como developer, quiero un endpoint POST /users que reciba el iam_user_id devuelto por sign-up junto con nombre, plan y empresa, para que el frontend pueda completar el perfil de negocio de una cuenta ya autenticada, sin duplicar la creación de credenciales. | **Escenario 1: Perfil creado exitosamente** <br> **Given** el developer envía una solicitud POST con token válido, y un iam_user_id existente que aún no tiene perfil, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 201 con el perfil creado (incluyendo el user_type derivado del plan) y crea automáticamente una AlertPreference para ese usuario. <br><br> **Escenario 2: iam_user_id inexistente** <br> **Given** el iam_user_id enviado no corresponde a ninguna credencial IAM, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 404. <br><br> **Escenario 3: Perfil ya existente para esa credencial** <br> **Given** el iam_user_id enviado ya tiene un perfil de negocio enlazado, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 409. <br><br> **Escenario 4: Solicitud sin token** <br> **Given** la solicitud no incluye el header Authorization, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 401. | EP14 |
| EP14 / TS36 | Endpoint para obtener el perfil propio a partir de la sesión activa | Como developer, quiero un endpoint GET /users/by-iam-user/{iamUserId} protegido, para que el frontend pueda traer el perfil completo del usuario justo después del login, usando el id de cuenta que devuelve sign-in o sign-up. | **Escenario 1: Consulta exitosa** <br> **Given** el token enviado pertenece al mismo iamUserId solicitado en la URL, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 200 y el perfil completo del usuario. <br><br> **Escenario 2: Intento de ver el perfil de otra cuenta** <br> **Given** el iamUserId de la URL no coincide con el del dueño del token, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 403. <br><br> **Escenario 3: Solicitud sin token** <br> **Given** la solicitud no incluye el header Authorization, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 401. | EP14 |
| EP14 / TS37 | Protección de los endpoints de perfil con autenticación JWT | Como developer, quiero que todos los endpoints bajo /users/** exijan un token JWT válido, para evitar que cualquiera consulte o modifique perfiles de negocio de otros usuarios sin haberse autenticado primero. | **Escenario 1: Acceso sin token** <br> **Given** un cliente llama a cualquier endpoint de /users/** sin el header Authorization, <br> **When** el servidor procesa la solicitud, <br> **Then** responde con status 401. <br><br> **Escenario 2: Acceso con token válido** <br> **Given** un cliente incluye un token JWT válido y no expirado, <br> **When** el servidor procesa la solicitud, <br> **Then** la solicitud continúa normalmente hacia el controlador correspondiente. | EP14 |


### 3.2. Impact Mapping

Este artefacto estratégico permite al equipo de Andes Smart asegurar que cada funcionalidad del Product Backlog esté directamente vinculada a un objetivo de negocio medible, evitando el desarrollo de características que no aporten valor real al usuario final.

**Segmento Agricultor**

![FOTO](report/assets/Claudia_Sanchez_Impact_Map.png)

<br>

**Segmento Empresario Agricola**

![FOTO](report/assets/Luis_Alberto_Impact_Map.png)


## 3.3. Product Backlog

| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
|--------|---------------|--------|-------------|--------------------------|
| **1** | **US01** | Ver propuesta de valor de AgroTrack | Como visitante, quiero ver claramente qué problema resuelve AgroTrack, para entender si la plataforma es útil para mí. | **1** |
| **2** | **US02** | Ver sección de funcionalidades principales | Como visitante, quiero ver las funcionalidades que ofrece AgroTrack, para evaluar si cubre mis necesidades como agricultor o empresario. | **1** |
| **3** | **US03** | Ver los segmentos objetivo a los que va dirigido | Como visitante, quiero saber a quiénes va dirigida la plataforma, para identificar si pertenezco al público objetivo. | **1** |
| **4** | **US04** | Ver planes y precios disponibles | Como visitante, quiero conocer los planes y precios de AgroTrack, para decidir si puedo pagarlo. | **2** |
| **5** | **US05** | Solicitar demo o acceso anticipado | Como visitante interesado, quiero dejar mis datos para solicitar una demo, para probar la plataforma antes de registrarme formalmente. | **3** |
| **6** | **US06** | Ver testimonios o casos de uso reales | Como visitante, quiero leer experiencias de otros usuarios, para ganar confianza en la plataforma antes de registrarme. | **1** |
| **7** | **US07** | Navegar desde un menú fijo de secciones | Como visitante, quiero un menú de navegación siempre visible, para acceder rápidamente a cualquier sección del landing page. | **2** |
| **8** | **US08** | Visualizar el landing page desde cualquier dispositivo | Como visitante, quiero que el landing page se adapte a mi celular o tablet, para poder verlo bien desde cualquier dispositivo. | **3** |
| **9** | **US09** | Registrar una cuenta nueva | Como usuario nuevo, quiero crear una cuenta en AgroTrack, para acceder a todas las funcionalidades de la plataforma. | **3** |
| **10** | **US10** | Iniciar sesión con correo y contraseña | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña, para acceder a mi cuenta y mis datos. | **3** |
| **11** | **US11** | Cerrar sesión | Como usuario autenticado, quiero cerrar sesión, para proteger mi cuenta cuando dejo de usar la plataforma. | **1** |
| **12** | **US12** | Recuperar contraseña olvidada | Como usuario, quiero recuperar mi contraseña si la olvidé, para volver a acceder a mi cuenta sin perder mis datos. | **3** |
| **13** | **US13** | Editar datos del perfil personal | Como usuario registrado, quiero editar mi información de perfil, para mantener mis datos actualizados. | **3** |
| **14** | **US14** | Seleccionar tipo de usuario al registrarse (Agricultor o Empresario Agrícola) | Como usuario nuevo, quiero elegir si soy Agricultor o Empresario Agrícola al registrarme, para que la plataforma me muestre las funcionalidades que corresponden a mi perfil. | **2** |
| **15** | **US15** | Registrar una nueva parcela | Como agricultor, quiero registrar una nueva parcela en la plataforma, para comenzar a hacer seguimiento de mis cultivos en ese terreno. | **3** |
| **16** | **US16** | Ver listado de mis parcelas | Como agricultor, quiero ver todas mis parcelas registradas en un solo lugar, para tener una vista general de mis terrenos. | **2** |
| **17** | **US17** | Editar información de una parcela | Como agricultor, quiero editar los datos de una parcela, para corregir o actualizar su información cuando sea necesario. | **3** |
| **18** | **US18** | Eliminar una parcela registrada | Como agricultor, quiero eliminar una parcela que ya no uso, para mantener mi listado limpio y organizado. | **2** |
| **19** | **US19** | Ver detalle de una parcela específica | Como agricultor, quiero ver el detalle completo de una parcela, para revisar toda su información y el estado de sus cultivos. | **3** |
| **20** | **US20** | Registrar un cultivo en una parcela | Como agricultor, quiero registrar un nuevo cultivo en una de mis parcelas, para llevar un control digital de lo que estoy sembrando. | **3** |
| **21** | **US21** | Ver los cultivos activos de una parcela | Como agricultor, quiero ver los cultivos activos de una parcela, para saber qué estoy cultivando actualmente en ese terreno. | **2** |
| **22** | **US22** | Editar información de un cultivo | Como agricultor, quiero editar los datos de un cultivo registrado, para corregir errores o actualizar su información. | **3** |
| **23** | **US23** | Marcar un cultivo como cosechado o finalizado | Como agricultor, quiero marcar un cultivo como finalizado, para registrar que ese ciclo de siembra ya terminó. | **3** |
| **24** | **US24** | Ver historial de cultivos anteriores por parcela | Como agricultor, quiero ver el historial de cultivos pasados de una parcela, para analizar qué sembré en temporadas anteriores y qué resultados tuve. | **2** |
| **25** | **US25** | Ingresar manualmente datos de humedad del suelo | Como agricultor, quiero registrar manualmente el nivel de humedad del suelo de mi parcela, para que la plataforma pueda darme recomendaciones basadas en datos reales. | **3** |
| **26** | **US26** | Ingresar manualmente datos de temperatura del suelo | Como agricultor, quiero registrar la temperatura del suelo de mi parcela, para tener un historial de condiciones del terreno. | **3** |
| **27** | **US27** | Ver el estado actual del suelo de una parcela | Como agricultor, quiero ver el estado actual del suelo de mi parcela, para saber si necesita riego o está en condiciones adecuadas. | **3** |
| **28** | **US28** | Ver historial de registros del suelo por parcela | Como agricultor, quiero ver el historial de datos del suelo de una parcela, para identificar cómo han variado las condiciones con el tiempo. | **2** |
| **29** | **US29** | Recibir recomendación de riego basada en datos del suelo | Como agricultor, quiero recibir una recomendación de riego según el nivel de humedad registrado, para tomar decisiones más informadas y no basarme solo en mi intuición. | **5** |
| **30** | **US30** | Ver el cronograma de riego sugerido por la plataforma | Como agricultor, quiero ver un cronograma de riego recomendado para mi parcela, para planificar mis actividades de riego con anticipación. | **5** |
| **31** | **US31** | Confirmar o rechazar una recomendación de riego | Como agricultor, quiero poder confirmar o rechazar una recomendación de riego, para registrar si seguí o no el consejo de la plataforma. | **3** |
| **32** | **US32** | Ver historial de riegos aplicados en una parcela | Como agricultor, quiero ver el historial de riegos que apliqué en una parcela, para revisar con qué frecuencia regué y si seguí las recomendaciones. | **2** |
| **33** | **US33** | Recibir alerta ante riesgo de helada | Como agricultor, quiero recibir una alerta cuando se pronostique una helada en mi zona, para proteger mis cultivos con anticipación. | **5** |
| **34** | **US34** | Recibir alerta ante riesgo de sequía | Como agricultor, quiero recibir una alerta cuando se pronostique un período de sequía prolongada, para anticipar mis decisiones de riego. | **5** |
| **35** | **US35** | Recibir alerta ante lluvias intensas previstas | Como agricultor, quiero recibir una alerta cuando se esperen lluvias intensas, para evitar el exceso de riego y proteger mis cultivos. | **5** |
| **36** | **US36** | Ver historial de alertas climáticas recibidas | Como agricultor, quiero ver todas las alertas climáticas que recibí, para revisar qué eventos ocurrieron y cómo respondí ante ellos. | **2** |
| **37** | **US37** | Configurar qué tipo de alertas quiero recibir | Como agricultor, quiero elegir qué tipos de alertas climáticas quiero recibir, para no saturarme de notificaciones que no me sean útiles. | **3** |
| **38** | **US38** | Ver panel de control con resumen de todas mis parcelas | Como empresario agrícola, quiero ver un panel de control con el estado de todas mis parcelas, para tener visibilidad centralizada de mi operación sin depender de reportes manuales. | **8** |
| **39** | **US39** | Ver rendimiento por parcela | Como empresario agrícola, quiero ver el rendimiento de cada parcela, para identificar cuáles están siendo más productivas y tomar decisiones de inversión. | **8** |
| **40** | **US40** | Ver porcentaje de pérdidas estimadas por parcela | Como empresario agrícola, quiero ver el porcentaje de pérdidas estimadas por parcela, para identificar dónde estoy perdiendo más y tomar acciones correctivas. | **8** |
| **41** | **US41** | Ver consumo de agua registrado por temporada | Como empresario agrícola, quiero ver cuánta agua se ha consumido por temporada en cada parcela, para evaluar la eficiencia del riego y reducir costos operativos. | **5** |
| **42** | **US42** | Exportar reporte de producción en formato PDF o Excel | Como empresario agrícola, quiero exportar un reporte de producción de mis parcelas, para compartirlo con mi equipo o analizarlo fuera de la plataforma. | **8** |

<br><br><br>

| # Orden | Technical Story Id | Título | Descripción | Story Points (1 / 2 / 3 / 5 / 8) |
|--------|--------------------|--------|-------------|----------------------------------|
| **1** | **TS01** | Endpoint para registrar un usuario | Como developer, quiero un endpoint POST /users para registrar un nuevo usuario, para que el frontend pueda crear cuentas desde el formulario de registro. | **3** |
| **2** | **TS02** | Endpoint para obtener un usuario por ID | Como developer, quiero un endpoint GET /users/{id} para obtener los datos de un usuario específico, para que el frontend pueda cargar el perfil del usuario autenticado. | **2** |
| **3** | **TS03** | Endpoint para actualizar un usuario | Como developer, quiero un endpoint PUT /users/{id} para actualizar los datos de un usuario, para que el frontend pueda permitir al usuario editar su perfil. | **2** |
| **4** | **TS04** | Endpoint para listar planes de suscripción | Como developer, quiero un endpoint GET /plans para obtener todos los planes disponibles, para que el frontend pueda mostrar las opciones de suscripción al usuario. | **1** |
| **5** | **TS05** | Endpoint para obtener preferencias de alertas | Como developer, quiero un endpoint GET /alert_preferences con filtro opcional por user_id, para que el frontend pueda cargar las preferencias de alerta del usuario activo. | **2** |
| **6** | **TS06** | Endpoint para actualizar preferencias de alertas | Como developer, quiero un endpoint PUT /alert_preferences/{id} para actualizar los toggles de alerta de un usuario, para que el frontend pueda guardar las preferencias de notificación configuradas por el usuario. | **2** |
| **7** | **TS07** | Endpoint para registrar una lectura de suelo | Como developer, quiero un endpoint POST /soil_records para registrar la humedad y temperatura de una parcela, para que el frontend pueda almacenar las mediciones realizadas desde la pestaña Soil. | **3** |
| **8** | **TS08** | Endpoint para listar lecturas de suelo | Como developer, quiero un endpoint GET /soil_records con filtro opcional por plot_id, para que el frontend pueda cargar el historial de lecturas de la parcela seleccionada. | **2** |
| **9** | **TS09** | Endpoint para eliminar una lectura de suelo | Como developer, quiero un endpoint DELETE /soil_records/{id} para eliminar una lectura de suelo, para que el sistema pueda retirar registros que ya no deben mantenerse. | **1** |
| **10** | **TS10** | Endpoint para registrar una recomendación de riego | Como developer, quiero un endpoint POST /irrigation_recommendations para registrar una recomendación asociada a una parcela y una lectura de suelo, para que el frontend pueda guardar las decisiones de riego del usuario. | **3** |
| **11** | **TS11** | Endpoint para listar recomendaciones de riego | Como developer, quiero un endpoint GET /irrigation_recommendations con filtro opcional por plot_id, para que el frontend pueda cargar el historial de recomendaciones y decisiones de riego de una parcela. | **2** |
| **12** | **TS12** | Endpoint para actualizar una recomendación de riego | Como developer, quiero un endpoint PUT /irrigation_recommendations/{id} para actualizar su estado, para que el frontend pueda registrar si el usuario confirmó o rechazó la asesoría. | **2** |
| **13** | **TS13** | Endpoint para eliminar una recomendación de riego |Como developer, quiero un endpoint DELETE /irrigation_recommendations/{id} para eliminar una recomendación de riego, para que el sistema pueda retirar registros que ya no deben conservarse.  | **1** |
| **14** | **TS14** | Endpoint para listar parcelas | Como developer, quiero un endpoint GET /plots con filtro opcional por userId, para que el frontend pueda cargar todas las parcelas registradas y filtrarlas por usuario. | **2** |
| **15** | **TS15** | Endpoint para registrar una parcela | Como developer, quiero un endpoint POST /plots para registrar una nueva parcela, para que el frontend pueda crear parcelas desde el formulario de gestión del usuario. | **3** |
| **16** | **TS16** | Endpoint para actualizar una parcela | Como developer, quiero un endpoint PUT /plots/{id} para actualizar los datos de una parcela, para que el frontend pueda guardar cambios en el nombre, ubicación o tamaño de la parcela. | **2** |
| **17** | **TS17** | Endpoint para desactivar una parcela | Como developer, quiero un endpoint DELETE /plots/{id} para desactivar una parcela, para que el frontend pueda retirar parcelas del listado activo del usuario cambiando su estado a DELETED. | **1** |
| **18** | **TS18** | Endpoint para listar cultivos | Como developer, quiero un endpoint GET /crops con filtro opcional por plotId, para que el frontend pueda cargar todos los cultivos registrados y filtrarlos por parcela en memoria. | **2** |
| **19** | **TS19** | Endpoint para registrar un cultivo | Como developer, quiero un endpoint POST /crops para registrar un cultivo en una parcela, para que el frontend pueda asociar un nuevo cultivo a la parcela seleccionada por el usuario. | **3** |
| **20** | **TS20** | Endpoint para actualizar un cultivo | Como developer, quiero un endpoint PUT /crops/{id} para actualizar los datos de un cultivo, para que el frontend pueda guardar cambios en el tipo, estado o fechas del cultivo registrado. | **2** |
| **21** | **TS21** | Endpoint para eliminar un cultivo | Como developer, quiero un endpoint DELETE /crops/{id} para eliminar un cultivo, para que el sistema pueda retirar cultivos del listado de la parcela cuando el usuario los elimine. | **1** |
| **22** | **TS22** | Endpoint para obtener alertas climáticas por ciudad | Como developer, quiero un endpoint GET /alerts?city={city} que consulte OpenWeather y devuelva alertas generadas, para que el frontend muestre riesgos climáticos sin exponer la API key. | **3** |
| **23** | **TS23** | Endpoint para listar resúmenes de rendimiento | Como developer, quiero un endpoint GET `/yield_summaries?user_id={userId}` para obtener todos los resúmenes de rendimiento agrícola filtrando opcionalmente por usuario, para que el frontend pueda mostrar las métricas de rendimiento por hectárea y temporada en el dashboard. | **3** |
| **24** | **TS24** | Endpoint para obtener resumen de rendimiento por ID | Como developer, quiero un endpoint GET `/yield_summaries/{id}` para recuperar un resumen de rendimiento específico por su identificador, para que el frontend pueda mostrar el detalle completo de una métrica de rendimiento individual. | **2** |
| **25** | **TS25** | Endpoint para listar resúmenes de pérdidas | Como developer, quiero un endpoint GET `/loss_summaries?user_id={userId}` para obtener todos los resúmenes de pérdidas agrícolas filtrando opcionalmente por usuario, para que el frontend pueda mostrar el porcentaje de pérdida y su causa por temporada en el dashboard. | **3** |
| **26** | **TS26** | Endpoint para obtener resumen de pérdidas por ID | Como developer, quiero un endpoint GET `/loss_summaries/{id}` para recuperar un resumen de pérdidas específico por su identificador, para que el frontend pueda mostrar el detalle de una métrica de pérdida individual. | **2** |
| **27** | **TS27** | Endpoint para listar consumos de agua | Como developer, quiero un endpoint GET `/water_consumptions?user_id={userId}` para obtener todos los registros de consumo de agua filtrando opcionalmente por usuario, para que el frontend pueda mostrar el total de litros consumidos por parcela y temporada en el dashboard. | **3** |
| **28** | **TS28** | Endpoint para obtener consumo de agua por ID | Como developer, quiero un endpoint GET `/water_consumptions/{id}` para recuperar un registro de consumo de agua específico por su identificador, para que el frontend pueda mostrar el detalle de un consumo individual. | **2** |
| **29** | **TS29** | Endpoint para listar tickets de soporte | Como developer, quiero un endpoint GET `/support_tickets?user_id={userId}` para obtener todos los tickets de soporte filtrando opcionalmente por usuario, para que el frontend pueda mostrar el historial completo de solicitudes de soporte del agricultor con su estado actual. | **2** |
| **30** | **TS30** | Endpoint para obtener ticket de soporte por ID | Como developer, quiero un endpoint GET `/support_tickets/{id}` para recuperar un ticket de soporte específico por su identificador, para que el frontend pueda mostrar el detalle completo de un ticket. | **2** |
| **31** | **TS31** | Endpoint para crear un ticket de soporte | Como developer, quiero un endpoint POST `/support_tickets` con body `{ user_id, subject, message }` para registrar un nuevo ticket de soporte con estado inicial OPEN, para que el frontend pueda permitir al usuario enviar una solicitud de ayuda al equipo de soporte. | **3** |
| **32** | **TS32** | Endpoint para registrar credenciales de una cuenta (sign-up) | Como developer, quiero un endpoint POST /authentication/sign-up que reciba email, password y plan, para que el frontend pueda crear la credencial de acceso de un usuario nuevo y recibir de inmediato un token de sesión. | **3** |
| **33** | **TS33** | Endpoint para iniciar sesión (sign-in) | Como developer, quiero un endpoint POST /authentication/sign-in que reciba email y password, para que el frontend pueda autenticar a un usuario ya registrado y obtener su token de sesión. | **2** |
| **34** | **TS34** | Endpoint para listar los roles disponibles | Como developer, quiero un endpoint GET /roles que devuelva todos los roles IAM sembrados en el sistema, para que el frontend pueda mostrarlos o validarlos donde se requiera. | **1** |
| **35** | **TS35** | Endpoint para completar el perfil de negocio de una cuenta registrada | Como developer, quiero un endpoint POST /users que reciba el iam_user_id devuelto por sign-up junto con nombre, plan y empresa, para que el frontend pueda completar el perfil de negocio de una cuenta ya autenticada, sin duplicar la creación de credenciales. | **3** |
| **36** | **TS36** | Endpoint para obtener el perfil propio a partir de la sesión activa | Como developer, quiero un endpoint GET /users/by-iam-user/{iamUserId} protegido, para que el frontend pueda traer el perfil completo del usuario justo después del login, usando el id de cuenta que devuelve sign-in o sign-up. | **2** |
| **37** | **TS37** | Protección de los endpoints de perfil con autenticación JWT | Como developer, quiero que todos los endpoints bajo /users/** exijan un token JWT válido, para evitar que cualquiera consulte o modifique perfiles de negocio de otros usuarios sin haberse autenticado primero. | **2** |


<br>
<br>


# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

#### Branding

- **Nombre del producto:** AgroTrack
- **Tagline:** *Cultiva mejor con datos reales.*
- **Identidad visual:** AgroTrack busca transmitir confianza, cercanía y
  modernidad accesible para el agricultor peruano. La identidad visual
  combina elementos naturales (tierra, agua, cultivos) con una estética
  limpia y funcional, adaptada a usuarios con poca experiencia
  tecnológica.
- **Logo:** El logotipo está compuesto por un ícono que representa una
  hoja o planta estilizada acompañada del nombre "AgroTrack" en
  tipografía sans-serif legible, reflejando el equilibrio entre el campo
  y la tecnología.
- **Valores visuales:** Confianza, simplicidad, eficiencia y cercanía
  con el campo.

![Logo de AgroTrack](report/assets/agrotrack-logo.png)

------------------------------------------------------------------------

#### Typography

- **Tipografía principal:** **Inter** (sans-serif), elegida por su alta
  legibilidad en pantallas, especialmente en dispositivos móviles con
  conectividad limitada. Usada en títulos y encabezados.
- **Tipografía secundaria:** **Roboto** (sans-serif), empleada en
  cuerpos de texto, etiquetas y elementos de interfaz por su claridad en
  tamaños pequeños.

**Jerarquía tipográfica:** \* **Títulos (H1):** 32--40 px \*
**Subtítulos (H2):** 24--28 px \* **Texto base:** 16 px \* **Botones y
etiquetas:** 14--16 px, en mayúsculas o negrita según jerarquía.

> **Principio aplicado:** Legibilidad máxima para usuarios con baja
> experiencia tecnológica, sin recursos decorativos que dificulten la
> lectura rápida en campo.

------------------------------------------------------------------------

#### Colors

La paleta cromática busca evocar el entorno natural del campo peruano
(tierra, vegetación y agua) combinada con tonos neutros que transmiten
confianza y claridad de información.

![Paleta de colores de AgroTrack](report/assets/colores_agotrack.png)

La tabla a continuación resume la paleta con su aplicación principal:

  --------------------------------------------------------------------------
  Tipo                 Nombre            Código            Aplicación
                                                           principal
  -------------------- ----------------- ----------------- -----------------
  **Primario**         Verde campo       `#2D7A3A`         Botones
                                                           principales,
                                                           íconos activos,
                                                           encabezados

  **Secundario**       Verde suave       `#5DAB72`         Estados
                                                           positivos,
                                                           confirmaciones,
                                                           alertas de riego
                                                           OK

  **Complementario**   Azul agua         `#4A90D9`         Indicadores de
                                                           humedad, datos
                                                           del suelo,
                                                           gráficos

  **Neutro claro**     Fondo tierra      `#F5F0E8`         Fondos de
                                                           páginas, tarjetas
                                                           de parcela

  **Neutro oscuro**    Texto oscuro      `#2C3E2D`         Texto principal y
                                                           encabezados

  **Borde/divisor**    Verde pálido      `#D9EDD9`         Líneas,
                                                           contenedores,
                                                           separadores
  --------------------------------------------------------------------------

*Figura 14. Paleta de colores institucional de AgroTrack. Nota.
Elaboración propia.*

------------------------------------------------------------------------

#### Spacing y Layout

- **Márgenes y paddings:** Uniformes (mínimo 16 px).
- **Bordes:** Redondeados entre **4--8 px** para suavizar la interfaz y
  dar sensación de accesibilidad.
- **Grillas:** Uso de sistema de grillas (*grid system*) adaptable a
  distintos tamaños de pantalla.
- **Distribución:**
  - **Mobile:** Una sola columna.
  - **Desktop:** Dos o tres columnas para optimizar legibilidad y ritmo
    visual.
- **Interactividad:** Especial atención al tamaño de los elementos
  interactivos (botones, campos) para facilitar el uso táctil en campo.

------------------------------------------------------------------------

#### Tone of Voice

- **Dimensión tonal:** Cercano, claro y alentador.
- **Lenguaje:** Directo, sencillo y sin tecnicismos, hablando el mismo
  idioma que el agricultor.
- **Estilo comunicativo:** Práctico y orientado a la acción, generando
  confianza inmediata desde el primer uso.

**Ejemplos de tono de acción:** \* *"Tu parcela necesita riego hoy."* \*
*"Registra tu cultivo en segundos."* \* *"Recibe alertas antes de que
llegue la helada."*

### 4.1.2. Web Style Guidelines

#### Diseño Responsivo

- **Breakpoints definidos:**
  - Móvil: ≤768 px
  - Tablet: 769--1024 px
  - Desktop: ≥1025 px

![Tamaños de Breakpoints](report/assets/breakpoints.png)

*Figura 15. Tamaños de Breakpoints definidos para AgroTrack. Nota.
Elaboración propia.*

- **Comportamiento adaptativo:**
  - En móvil, se prioriza la visualización vertical con menú hamburguesa
    y tarjetas de parcelas apiladas.
  - En desktop, se emplea una distribución horizontal con estructura de
    dos o tres columnas.
  - El diseño mantiene jerarquía visual y lenguaje cromático consistente
    en todos los dispositivos.

------------------------------------------------------------------------

#### Componentes Web

- **Botones (CTAs):**
  - **Primario:** Fondo verde `#2D7A3A`, texto blanco, borde redondeado
    (8--12 px).
  - **Secundario:** Fondo blanco, borde verde `#5DAB72`, texto verde.
  - **Estados:** *hover* (tono más oscuro), *active* (sombra ligera),
    *disabled* (opacidad reducida).

![Variantes de botones CTA](report/assets/var_botones.png)

*Figura 16. Variantes de botones CTA de AgroTrack. Nota. Elaboración
propia.*

- **Formularios:**
  - Campos con bordes finos y feedback visual al error o validación.
  - Etiquetas visibles y mensajes de error en texto rojo o ícono de
    advertencia.
  - Campos de ingreso de datos del suelo (humedad, temperatura) con
    validación de rango inmediata.
- **Navegación:**
  - Barra superior fija (*sticky header*) con logo, enlaces principales
    y CTA de registro.
  - Menú desplegable para secciones secundarias.
  - En móvil, menú tipo hamburguesa con ícono fácilmente reconocible.
- **Cards (tarjetas de parcela):**
  - Secciones por parcela con nombre, cultivo activo, estado del suelo e
    última alerta.
  - Bordes suaves, sin sombra pesada, márgenes consistentes de 16 px.
  - Indicador de estado del suelo con color semántico: verde (normal),
    amarillo (atención), rojo (crítico).

------------------------------------------------------------------------

#### Interacción y Accesibilidad

- **Animaciones:** Transiciones suaves de 0.2 s para interacciones con
  botones o cambios de vista.
- **Indicadores de carga:** Ícono circular o barra de progreso visible
  durante procesos de espera.
- **Accesibilidad (WCAG 2.1):**
  - Contraste mínimo AA en texto e íconos.
  - Navegación mediante teclado.
  - Etiquetas alternativas (*alt text*) en imágenes y gráficos de
    parcelas.
- **Microinteracciones:** Animaciones sutiles al hacer clic y
  retroalimentación visual al confirmar una acción (p.ej. registro de
  riego exitoso).

# 4.2. Information Architecture

## 4.2.1. Organization Systems

El equipo de AgroTrack definió los sistemas de organización del
contenido considerando los dos segmentos objetivo ---agricultores y
empresarios agrícolas--- y la naturaleza de cada experiencia: Landing
Page y Web Application.

**Landing Page**\*

La Landing Page organiza su contenido de forma **secuencial
(top-to-bottom)**, guiando al visitante a través de un flujo narrativo
que va desde la presentación del problema hasta la conversión:

1.  Hero / Propuesta de valor
2.  Funcionalidades principales
3.  Segmentos objetivo (Agricultor / Empresario Agrícola)
4.  Planes y precios
5.  Testimonios
6.  Formulario de demo / CTA final Este orden responde a la lógica de
    persuasión progresiva: el visitante primero entiende el problema,
    luego ve la solución, se identifica con su perfil y, finalmente,
    toma acción. No se aplica organización matricial ni alfabética, ya
    que el contenido es narrativo y no enciclopédico.

La categorización del contenido se realiza **por audiencia**: cada
sección comunica diferencialmente a agricultores individuales y a
empresarios de PYMEs, usando ejemplos y lenguaje adaptado a cada perfil.

**Web Application**

Dentro de la aplicación web, se combinan tres esquemas de organización
según el tipo de información:

**Organización jerárquica (visual hierarchy)** Se aplica en el Dashboard
principal y en la vista de detalle de parcela. El contenido más crítico
(estado del suelo, alertas activas, recomendación de riego) ocupa la
posición y tamaño visual más prominente. Los datos secundarios
(historial, configuración de alertas) se muestran en niveles inferiores
de la jerarquía.

**Organización secuencial (step-by-step)** Se aplica en los flujos de
registro y configuración: - Registro de cuenta → selección de perfil →
acceso al dashboard - Creación de parcela → registro de cultivo →
ingreso de datos del suelo → recepción de recomendación - Solicitud de
demo desde la Landing Page (formulario en pasos) Este esquema es
especialmente importante para el segmento de agricultores, que puede
tener poca experiencia tecnológica y necesita una guía clara paso a
paso.

**Organización por tópicos** Se aplica en la navegación general de la
aplicación. El contenido se agrupa en módulos funcionales claramente
diferenciados: - Mis Parcelas - Mis Cultivos - Estado del Suelo -
Recomendaciones de Riego - Alertas Climáticas - Dashboard / Reportes
(exclusivo para Empresarios Agrícolas) **Organización cronológica** Se
aplica en secciones de historial, donde la información más reciente
siempre aparece primero: - Historial de registros del suelo - Historial
de cultivos anteriores - Historial de riegos aplicados - Historial de
alertas climáticas recibidas **Categorización por audiencia** El
dashboard y las funcionalidades disponibles varían según el tipo de
usuario seleccionado al registrarse. El perfil **Agricultor** accede a
vistas orientadas al registro y seguimiento de su parcela individual. El
perfil **Empresario Agrícola** accede adicionalmente a vistas de
rendimiento centralizado, métricas de pérdidas, consumo de agua por
temporada y exportación de reportes.

## 4.2.2. Labeling Systems

El equipo definió etiquetas breves, en lenguaje directo y sin
tecnicismos, alineadas con el tono de voz de AgroTrack: cercano, claro y
práctico. Se priorizó el uso de términos que el agricultor peruano
reconoce en su práctica cotidiana.

\*\*\* Etiquetas de Navegación Principal (Web Application) \*\*\*

  Sección                                           Etiqueta
  ------------------------------------------------- ------------------------------
  Vista general de todas las parcelas del usuario   **Mis Parcelas**
  Lista de cultivos activos por parcela             **Mis Cultivos**
  Registros de humedad y temperatura                **Estado del Suelo**
  Sugerencias de cuándo y cuánto regar              **Recomendaciones de Riego**
  Notificaciones de helada, sequía o lluvia         **Alertas Climáticas**
  Vista centralizada de métricas (Empresario)       **Panel de Control**
  Exportación de datos de producción                **Reportes**
  Datos personales y preferencias                   **Mi Perfil**
  Preferencias de notificaciones                    **Configuración**

\*\*\* Etiquetas de Acciones Principales (CTAs) \*\*\*

  -----------------------------------------------------------------------
  Acción                              Etiqueta
  ----------------------------------- -----------------------------------
  Crear una nueva parcela             **+ Nueva Parcela**

  Agregar un cultivo a una parcela    **+ Registrar Cultivo**

  Ingresar datos de humedad o         **Registrar Datos del Suelo**
  temperatura                         

  Marcar un cultivo como terminado    **Marcar como Cosechado**

  Aceptar una sugerencia de riego     **Confirmar Riego**

  Rechazar una sugerencia de riego    **No Aplicado**

  Descargar reporte en PDF o Excel    **Exportar Reporte**

  Completar formulario de contacto en **Solicitar Demo**
  Landing Page                        

  Crear cuenta                        **Crear Cuenta**

  Entrar a la plataforma              **Iniciar Sesión**

  Salir de la cuenta                  **Cerrar Sesión**
  -----------------------------------------------------------------------

\*\*\* Etiquetas de Estado del Suelo \*\*\*

Los indicadores visuales del estado de la parcela usan colores
semánticos (verde, amarillo, rojo) acompañados de etiquetas de texto
para garantizar accesibilidad:

  Estado                        Etiqueta                Color
  ----------------------------- ----------------------- -----------------
  Humedad entre 40 % y 70 %     **Normal**              Verde `#5DAB72`
  Humedad por debajo del 40 %   **Necesita Riego**      Amarillo
  Humedad por encima del 70 %   **Exceso de Humedad**   Rojo

\*\*\* Etiquetas de Tipo de Alerta Climática \*\*\*

  Evento                                  Etiqueta
  --------------------------------------- ----------------------
  Temperatura pronosticada \< 0 °C        **Riesgo de Helada**
  Ausencia de lluvias por más de 7 días   **Riesgo de Sequía**
  Precipitaciones intensas previstas      **Lluvias Intensas**

\*\*\* Etiquetas de Estado de Cultivo \*\*\*

  Estado                          Etiqueta
  ------------------------------- ----------------
  Cultivo en curso                **Activo**
  Cultivo terminado y cosechado   **Finalizado**

\*\*\* Etiquetas de Formularios y Campos \*\*\*

  -----------------------------------------------------------------------
  Campo                               Etiqueta
  ----------------------------------- -----------------------------------
  Nombre de la parcela                **Nombre**

  Extensión del terreno               **Tamaño (ha)**

  Coordenadas o lugar                 **Ubicación**

  Tipo de planta sembrada             **Tipo de Cultivo**

  Fecha de inicio de la siembra       **Fecha de Siembra**

  Porcentaje de agua en el suelo      **Humedad del Suelo (%)**

  Grados del suelo al momento del     **Temperatura del Suelo (°C)**
  registro                            

  Correo electrónico del usuario      **Correo**

  Clave de acceso                     **Contraseña**

  Tipo de cuenta del usuario          **Soy...** (`Agricultor` /
                                      `Empresario Agrícola`)
  -----------------------------------------------------------------------

\*\*\* Etiquetas de la Landing Page \*\*\*

  -----------------------------------------------------------------------
  Sección                             Etiqueta visible
  ----------------------------------- -----------------------------------
  Bloque principal con propuesta de   **Cultiva mejor con datos reales**
  valor                               

  Lista de funciones del producto     **¿Qué puedes hacer con
                                      AgroTrack?**

  Descripción de perfiles de usuario  **¿Para quién es AgroTrack?**

  Tabla de planes disponibles         **Planes y Precios**

  Opiniones de usuarios               **Lo que dicen nuestros usuarios**

  Formulario de interés               **Solicita tu demo gratuita**

  Enlace a registro                   **Empieza ahora**
  -----------------------------------------------------------------------

### 4.2.3 SEO Tags and Meta Tags

Los SEO Tags y Meta Tags de AgroTrack se definen con el objetivo de
mejorar la visibilidad del producto en motores de búsqueda y facilitar
que agricultores, empresarios agrícolas y visitantes interesados
comprendan rápidamente el propósito de la solución. Estos metadatos se
aplican tanto al Landing Page como a la futura Web Application,
manteniendo una comunicación clara, directa y alineada con la propuesta
de valor del producto: ayudar a tomar decisiones agrícolas con datos
reales, especialmente en el registro de parcelas, monitoreo del suelo,
recomendaciones de riego y alertas climáticas. AgroTrack está orientado
a pequeños agricultores y empresarios agrícolas del Perú que necesitan
herramientas simples para registrar sus cultivos, monitorear el estado
del suelo y tomar decisiones más informadas sobre el riego y la gestión
de sus parcelas. Esta orientación se basa en el perfil del producto,
definido como una plataforma web para registrar parcelas, ingresar
información de cultivos y recibir recomendaciones prácticas para
optimizar el riego.

#### **Landing Page SEO & Meta Tags**

La Landing Page tiene una finalidad informativa y comercial. Por ello,
los meta tags se enfocan en comunicar la propuesta de valor de
AgroTrack, presentar sus funcionalidades principales y atraer a
visitantes interesados en digitalizar la gestión agrícola.

``` html
<title>AgroTrack | Grow better with real data</title>

<meta
    name="description"
    content="AgroTrack helps farmers and agricultural SMEs register plots, monitor soil conditions, receive irrigation recommendations and manage climate alerts using real data."
/>

<meta
    name="keywords"
    content="AgroTrack, agriculture technology, smart farming, soil monitoring, irrigation recommendations, climate alerts, crop management, agricultural SMEs, farmers Peru"
/>

<meta name="author" content="Andes Smart Team" />

<meta name="robots" content="index, follow" />

<meta
    property="og:title"
    content="AgroTrack | Grow better with real data"
/>

<meta
    property="og:description"
    content="Register your plots, monitor soil conditions and receive clear irrigation recommendations with AgroTrack."
/>

<meta
    property="og:image"
    content="https://www.agrotrack.com/assets/agrotrack-og-image.jpg"
/>

<meta
    property="og:url"
    content="https://www.agrotrack.com"
/>

<meta property="og:type" content="website" />
```

------------------------------------------------------------------------

#### **Web Application SEO & Meta Tags**

La Web Application está orientada a usuarios registrados, como
agricultores y empresarios agrícolas. En este caso, los meta tags se
enfocan en la funcionalidad principal de la plataforma: gestión de
parcelas, cultivos, suelo, riego, alertas y reportes. Aunque muchas
pantallas internas pueden requerir autenticación, estos metadatos ayudan
a mantener una identidad clara del producto dentro del navegador y en
páginas públicas o accesibles desde la aplicación.

``` html
<title>AgroTrack | Agricultural management platform</title>

<meta
    name="description"
    content="Access AgroTrack to manage plots, crops, soil records, irrigation recommendations, climate alerts, dashboards and agricultural reports from one platform."
/>

<meta
    name="keywords"
    content="AgroTrack platform, plot management, crop tracking, soil records, irrigation schedule, weather alerts, agricultural dashboard, farming reports"
/>

<meta name="author" content="Andes Smart Team" />

<meta name="robots" content="index, follow" />

<meta
    property="og:title"
    content="AgroTrack | Agricultural management platform"
/>

<meta
    property="og:description"
    content="Manage your agricultural operation with plot tracking, soil monitoring, irrigation recommendations, climate alerts and reports."
/>

<meta
    property="og:image"
    content="https://app.agrotrack.com/assets/agrotrack-app-og-image.jpg"
/>

<meta
    property="og:url"
    content="https://app.agrotrack.com"
/>

<meta property="og:type" content="website" />
```

### 4.2.4 Searching Systems

Dentro de la plataforma AgroTrack, los sistemas de búsqueda han sido
diseñados para facilitar el acceso rápido y eficiente a la información
relacionada con la gestión agrícola. Debido al manejo constante de datos
vinculados con parcelas, alertas, usuarios, configuraciones y registros
operativos, se contempla un sistema de búsqueda que permita a los
usuarios localizar información relevante de manera inmediata y mantener
un control ordenado de sus actividades. El sistema permitirá realizar
búsquedas dentro de los distintos módulos de la plataforma mediante:

- Palabras clave (nombre de parcela, ubicación, tipo de registro, nombre
  de usuario o descripción relacionada).
- Filtros por categoría (parcelas, alertas, configuraciones, perfiles o
  registros administrativos).
- Estados del registro (activo, pendiente, completado o actualizado).
- Identificadores internos asociados a parcelas, usuarios o elementos
  registrados dentro del sistema.

Este sistema será especialmente útil para:

- Ahorrar tiempo en la localización de parcelas, configuraciones o
  registros específicos sin necesidad de navegar manualmente entre
  módulos.

- Encontrar rápidamente información relacionada con parcelas agrícolas,
  alertas emitidas o datos administrativos.

- Mejorar la organización operativa mediante el acceso inmediato a
  información previamente registrada.

- Facilitar la gestión diaria del usuario al mantener una navegación más
  ágil y ordenada dentro de la plataforma.

- Una vez realizada la búsqueda, los resultados se mostrarán de forma
  estructurada dentro de listas, tablas o formularios interactivos según
  el módulo correspondiente, permitiendo visualizar, editar o gestionar
  la información de acuerdo con los permisos asignados al usuario.

### 4.2.5 Navigation Systems

Para el sistema de navegación otorgamos libertad y facilidad al usuario
dentro de la plataforma con diversas interfaces de navegación:

***PRIMERA NAVEGACIÓN:*** Acceso a apartados para cada tipo de usuario y
herramientas de registro e inicio de sesión. Este navegador global se
encuentra en la parte superior de la pantalla permitiendo que el usuario
pueda acceder en todo momento a las funciones principales del sitio sin
la necesidad de scrollear.

![Navigation](report/assets/landing-page-navigation.png)

*Fuente: Propia.*

***SEGUNDA NAVEGACIÓN:*** Sección de registro continúa al apartado de
contenido principal. Esta sección de registro que va luego de que el
usuario haya visto el contenido principal del sitio, le ayuda a tomar
decisiones como agricultor.

![Registration](report/assets/landing-page-registration.png)

*Fuente: Propia.*

***TERCERA NAVEGACIÓN:*** Pie de página con información complementaria.
Esta sección reúne enlaces de interés tanto para agricultores como para
empresarios agrícolas, permitiendo que los usuarios que llegaron al
final del sitio continúen navegando fácilmente sin necesidad de regresar
al inicio.

![Footer](report/assets/landing-page-footer.png)

*Fuente: Propia.*

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

Para la landing page se realizaron los Wireframes en figma de toda la
página web

![Wirefram1](report/assets/wireframe1.png) ![Wirefram2](report/assets/wireframe2.png)

*Nota: Elaboración propia. Elaborado en:
https://www.figma.com/design/tQSFHjZZpLcvBWkbzUfWLw/Untitled?node-id=0-1&p=f&t=rDZhOjwZFkCWZdXw-0*

### 4.3.2. Landing Page Mock-up

<br>

**Desktop Web Browser**

![Mock Up 1](report/assets/mockup1.png) ![Mock Up 2](report/assets/mockup2.png)

<br>

**Mobile Web Browser**

![Mock Up 1](report/assets/mockupMobile1.png) ![Mock Up
2](report/assets/mockupMobile2.png) ![Mock Up 2](report/assets/mockupMobile3.png)

<br> 

*Elaborado en:
https://www.figma.com/design/tQSFHjZZpLcvBWkbzUfWLw/Untitled?node-id=0-1&p=f&t=rDZhOjwZFkCWZdXw-0*

### 4.4.1. Web Applications Wireframes

![Wireframe 1](report/assets/wireframe-maqueta.png) ![Wireframe
2](report/assets/wireframe-maqueta2.png) ![Wireframe
3](report/assets/wireframe-maqueta3.png) ![Wireframe
4](report/assets/wireframe-maqueta4.png) ![Wireframe
5](report/assets/wireframe-maqueta5.png)

### 4.4.2. Web Applications Wireflow Diagrams

Los Web Applications Wireflow Diagrams son representaciones visuales de
los flujos de navegación y la arquitectura de una aplicación web. Estos
diagramas combinan elementos de wireframes y diagramas de flujo para
proporcionar una vista general de cómo los usuarios navegarán a través
de la aplicación y cómo interactuarán con ella.

![Wireflow Diagram](report/assets/wireflowdiagrams.png)

### 4.4.3. Web Applications Mock-ups

![Mock-up 1](report/assets/web-mockups.png) ![Mock-up
2](report/assets/web-mockups2.png) ![Mock-up 3](report/assets/web-mockups3.png)
![Mock-up 4](report/assets/web-mockups4.png)

### 4.4.4. Web Applications User Flow Diagrams

El diagrama de flujo de usuario es una representación visual de los
pasos que un usuario sigue al interactuar con una aplicación o sitio
web. Muestra la secuencia de acciones que el usuario realiza para
completar una tarea específica, lo que nos ayuda a identificar posibles
puntos de fricción y a optimizar la experiencia del usuario.

![User Flow Diagram 1](report/assets/userflow.png) ![User Flow Diagram
2](report/assets/userflow2.png) ![User Flow Diagram 3](report/assets/userflow3.png)

### 4.5. Web Applications Prototyping

Prototipo de la aplicación web AgroTrack en Figma:
https://www.figma.com/design/tQSFHjZZpLcvBWkbzUfWLw/Untitled?node-id=0-1&p=f&t=VDnBfHM1uPU4jdXO-0

![FLUJO-PROTOTIPO](report/assets/FLUJO-PROTOTIPO.png)

Video del flujo del prototipo:
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a267_upc_edu_pe/IQBGdqAI0J_NR7IAsWPnBl3TAe0ieQNo8cg4MmurJ2Owfuc?e=2yMdi8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### 4.6. Domain-Driven Software Architecture.

En esta sección se presenta la arquitectura de software de AgroTrack
desde el enfoque de Domain-Driven Design, tomando como base el Big
Picture Event Storming desarrollado previamente. A partir de dicho
análisis, se identificaron eventos, comandos, actores y sistemas
externos relevantes para el dominio agrícola, como el registro de
usuarios, la creación de parcelas, el ingreso de datos del suelo, las
recomendaciones de riego y las alertas climáticas. Con esta información,
el sistema se organizará en Bounded Contexts que separan las principales
responsabilidades del producto, como autenticación, gestión de parcelas
y cultivos, monitoreo del suelo, recomendaciones climaticas y de riego y
reportes. Esta división permite representar con mayor claridad cada
parte del dominio y mantener relación con el lenguaje ubicuo definido
para AgroTrack, donde se incluyen términos como Plot, Crop, Soil
Moisture, Weather Alert e Irrigation Schedule.

### 4.6.1. Design-Level Event Storming.

**Identity & Access Management**

![Identity&AccesManagement](report/assets/Identity&AccesManagement.png)

**Farm Management**

![FarmManagementBC](report/assets/FarmManagementBC.png)

**Soil Monitoring**

![SoilMonitoringBC](report/assets/SoilMonitoringBC.png)

**Irrigation & Weather Advisory**

![IrrigationAndWeatherBC](report/assets/IrrigationAndWeatherBC.png)

**Analytics & Reporting**

![Analytics&Reporting](report/assets/Analytics&Reporting.png)

Miro:
https://miro.com/app/board/uXjVHcOGric=/?share_link_id=857544303236

### 4.6.2. Software Architecture Context Diagram.

![SystemContext-AgroTrack](report/assets/SystemContext-AgroTrack.png)

### 4.6.3. Software Architecture Container Diagrams.

![ContainerDiagram-AgroTrack](report/assets/ContainerDiagram-AgroTrack.png)

### 4.6.4. Software Architecture Components Diagrams.

**Identity & Access Management**

![IAMC4](report/assets/IAMC4.png)

**Farm Management**

![FarmManagementC4](report/assets/FarmManagementC4.png)

**Soil Monitoring**

![SoilMonitoringC4](report/assets/SoilMonitoringC4.png)

**Irrigation & Weather Advisory**

![IrrigationWeatherAdvisoryC4](report/assets/IrrigationWeatherAdvisoryC4.png)

**Analytics & Reporting**

![AnalyticsReportingC4](report/assets/AnalyticsReportingC4.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

``` plantuml
@startuml AgroTrack_ClassDiagram

'BOUNDED CONTEXT: User & Auth
package "Identity.domain.model" {

  interface Plan {
    +getMaxPlots() : int
    +getPrice() : double
    +isEnterpriseDashboardEnabled() : boolean
    +isExportEnabled() : boolean
    +hasPrioritySupport(): boolean
  }

  class BasicPlan {
    -price : double
    -maxPlots : int
    +getMaxPlots() : int
    +getPrice() : double
    +isEnterpriseDashboardEnabled() : boolean
    +isExportEnabled() : boolean
    +hasPrioritySupport() : boolean
  }

  class ProPlan
  {
    - price: double
    - maxPlots: int
    + getMaxPlots() : int
    + getPrice() : double
    + isEnterpriseDashboardEnabled(): boolean
    + isExportEnabled(): boolean
    + hasPrioritySupport() : boolean
  }

  class EnterprisePlan {
    -price : double
    -maxPlots : int
    +getMaxPlots() : int
    +getPrice() : double
    +isEnterpriseDashboardEnabled() : boolean
    +isExportEnabled() : boolean
    +hasPrioritySupport(): boolean
  }
   
  class UserId
  {
    *value: UUID
  }

  abstract class User {
    *id : UserId
    #name : String
    -email : String
    -passwordHash : String
    #plan : Plan
    -createdAt : LocalDateTime
    -updatedAt : LocalDateTime
    +updateProfile(name: String, email: String) : void
    +changePlan(plan: Plan) : void
    +getId() : UserId
    +getEmail() : String
    +getPlan() : Plan
  }

  class Farmer {
    -plots : List<Plot>
    +getPlots() : List<Plot>
    +addPlot(plot: Plot) : void
    +removePlot(plotId: PlotId) : void
  }

  class AgriculturalManager {
    -companyName : String
    -managedPlots : List<Plot>
    +getDashboard() : Dashboard
    +exportReport(format: ReportFormat) : byte[]
    +getYieldSummary() : List<YieldSummary>
    +getLossSummary() : List<LossSummary>
    +getWaterConsumption() : List<WaterConsumption>
  }

  class AlertPreferenceId
  {
    *value: UUID
  }

  class AlertPreference {
    *id : AlertPreferenceId
    -userId : UserId
    -frostEnabled : boolean
    -droughtEnabled : boolean
    -heavyRainEnabled : boolean
    +update(frost: boolean, drought: boolean, rain: boolean) : void
    +isEnabled(type: AlertType) : boolean
    +getUserId() : UserId
  }

  AlertPreference o--> "1" AlertPreferenceId : has >
  User o--> "1" UserId : has >
  User <|-- Farmer
  User <|-- AgriculturalManager
  Plan <|.. BasicPlan
  Plan <|.. ProPlan
  Plan <|.. EnterprisePlan
  User "1" --> "1" Plan : subscribes to >
  User "1" *-- "0..1" AlertPreference : configures > 
}


' Support
package Support.domain.model{

    class SupportTicketId
    {
        *value: UUID
    }
    class SupportTicket {
      *id : SupportTicketId
      -userId : UserId
      -subject : String
      -message : String
      -status : TicketStatus
      -createdAt : LocalDateTime
      -respondedAt : LocalDateTime
      +create(subject: String, message: String) : SupportTicket
      +close() : void
      +getId() : SupportTicketId
      +getStatus() : TicketStatus
    }

    enum TicketStatus {
      OPEN
      IN_PROGRESS
      CLOSED
    }
    SupportTicket o--> "1" SupportTicketId : has >
    SupportTicket "1" --> "1" TicketStatus : has >
}


' BOUNDED CONTEXT: Plot & Crop

package "Plot & Crop.domain.model" {

  enum PlotStatus {
    ACTIVE
    INACTIVE
    DELETED
  }

  enum CropStatus {
    ACTIVE
    HARVESTED
    LOST
  }

  class PlotId
  {
    *value: UUID
  }

  class Plot {
    *id: PlotId
    -name : String
    -location : String
    -sizeHectares : double
    -status : PlotStatus
    -userId : UserId
    -createdAt : LocalDateTime
    +register(name: String, location: String, size: double) : Plot
    +update(name: String, location: String, size: double) : void
    +delete() : void
    +getId() : PlotId
    +getName() : String
    +getStatus() : PlotStatus
    +getActiveCrops() : List<Crop>
    +getCropHistory() : List<Crop>
    +getCurrentSoilStatus() : SoilStatus
  }

  class CropId
  {
    *value: UUID
  }

  class Crop {
    *id : CropId
    -type : String
    -sowingDate : LocalDate
    -harvestDate : LocalDate
    -status : CropStatus
    -plotId : PlotId
    +register(type: String, sowingDate: LocalDate, plotId: PlotId) : Crop
    +update(type: String, sowingDate: LocalDate) : void
    +markAsHarvested(harvestDate: LocalDate) : void
    +getId() : CropId
    +getType() : String
    +getStatus() : CropStatus
    +isActive() : boolean
  }

  Crop o--> "1" CropId : has >
  Plot o--> "1" PlotId : has >
  Plot "1" --> "1" PlotStatus : has >
  Plot "1" *-- "0..*" Crop : contains >
  Crop "1" --> "1" CropStatus : has >
}


' BOUNDED CONTEXT: Soil Monitoring

package "Soil Monitoring.domain.model" {

  enum SoilStatus {
    LOW
    NORMAL
    HIGH
  }

  enum UrgencyLevel {
    LOW
    MEDIUM
    HIGH
    CRITICAL
  }

  enum RecommendationStatus {
    PENDING
    CONFIRMED
    REJECTED
  }

  enum ScheduleStatus {
    PENDING
    COMPLETED
    SKIPPED
  }

  class SoilRecordId
  {
    *value: UUID
  }

  class SoilRecord {
    *id : SoilRecordId
    -humidity : double
    -temperature : double
    -recordedAt : LocalDateTime
    -plotId : PlotId
    +register(humidity: double, temperature: double, plotId: PlotId) : SoilRecord
    +getId() : SoilRecordId
    +getHumidity() : double
    +getTemperature() : double
    +getRecordedAt() : LocalDateTime
    +getSoilStatus() : SoilStatus
  }

  class IrrigationRecommendationId
  {
    *value: UUID
  }

  class IrrigationRecommendation {
    *id : IrrigationRecommendationId
    -message : String
    -urgency : UrgencyLevel
    -status : RecommendationStatus
    -plotId : PlotId
    -generatedAt : LocalDateTime
    -respondedAt : LocalDateTime
    +generate(soilRecord: SoilRecord) : IrrigationRecommendation
    +confirm() : void
    +reject() : void
    +getId() : IrrigationRecommendationId
    +getStatus() : RecommendationStatus
    +getUrgency() : UrgencyLevel
  }

  class IrrigationScheduleId
  {
    *value:UUID
  }

  class IrrigationSchedule {
    *id : IrrigationScheduleId
    -suggestedAt : LocalDateTime
    -durationMinutes : int
    -plotId : PlotId
    -status : ScheduleStatus
    +create(plotId: PlotId, suggestedAt: LocalDateTime) : IrrigationSchedule
    +getId() : IrrigationScheduleId
    +getSuggestedAt() : LocalDateTime
    +getStatus() : ScheduleStatus
  }

  interface RecommendationEngine {
    +evaluate(soilRecord: SoilRecord) : IrrigationRecommendation
    +generateSchedule(plot: Plot) : IrrigationSchedule
  }

  class SoilBasedRecommendationEngine {
    -lowThreshold : double
    -highThreshold : double
    +evaluate(soilRecord: SoilRecord) : IrrigationRecommendation
    +generateSchedule(plot: Plot) : IrrigationSchedule
    -classifyHumidity(humidity: double) : SoilStatus
    -calculateUrgency(humidity: double) : UrgencyLevel
  }


  IrrigationSchedule o--> "1" IrrigationScheduleId : has >
  IrrigationRecommendation o--> "1" IrrigationRecommendationId : has >
  SoilRecord o--> "1" SoilRecordId : has >
  SoilRecord "1" --> "1" SoilStatus : evaluates to >
  IrrigationRecommendation "1" --> "1" RecommendationStatus : has >
  IrrigationRecommendation "1" --> "1" UrgencyLevel : has >
  IrrigationSchedule "1" --> "1" ScheduleStatus : has >
  RecommendationEngine <|.. SoilBasedRecommendationEngine
  SoilBasedRecommendationEngine ..> SoilRecord : uses >
  SoilBasedRecommendationEngine ..> IrrigationRecommendation : produces >
  SoilBasedRecommendationEngine ..> IrrigationSchedule : produces >
  SoilBasedRecommendationEngine ..> SoilStatus : uses >
  SoilBasedRecommendationEngine ..> UrgencyLevel : uses >
}


' BOUNDED CONTEXT: Climate Alerts

package "Climate Alerts.domain.model" {

  enum AlertType {
    FROST
    DROUGHT
    HEAVY_RAIN
  }

  enum AlertStatus {
    ACTIVE
    DISMISSED
    EXPIRED
  }

  class ClimateAlertId
  {
    *value: UUID
  }

  class ClimateAlert {
    *id : ClimateAlertId
    -type : AlertType
    -description : String
    -alertDate : LocalDate
    -status : AlertStatus
    -plotId : PlotId
    +create(type: AlertType, plotId: PlotId) : ClimateAlert
    +dismiss() : void
    +getId() : ClimateAlertId
    +getType() : AlertType
    +getStatus() : AlertStatus
  }

  class WeatherForecast {
    -location : String
    -minTemperature : double
    -maxTemperature : double
    -precipitationMm : double
    -daysWithoutRain : int
    -forecastDate : LocalDate
    +getMinTemperature() : double
    +getPrecipitationMm() : double
    +getDaysWithoutRain() : int
    +hasFrostRisk() : boolean
    +hasDroughtRisk() : boolean
    +hasHeavyRainRisk() : boolean
  }

  interface WeatherService {
    +getForecast(location: String) : WeatherForecast
    +checkFrostRisk(location: String) : boolean
    +checkDroughtRisk(location: String) : boolean
    +checkHeavyRainRisk(location: String) : boolean
  }

  ClimateAlert o--> "1" ClimateAlertId : has >
  ClimateAlert "1" --> "1" AlertType : has >
  ClimateAlert "1" --> "1" AlertStatus : has >
  WeatherService ..> WeatherForecast : returns >
  WeatherForecast ..> ClimateAlert : triggers >
  AlertPreference ..> AlertType : filters >
}


' BOUNDED CONTEXT: Enterprise Dashboard

package "Dashboard.domain.model" {

  class Dashboard {
    -plots : List<Plot>
    -yieldSummaries : List<YieldSummary>
    -lossSummaries : List<LossSummary>
    -waterConsumptions : List<WaterConsumption>
    +getPlotsSummary() : List<Plot>
    +getYieldSummary() : List<YieldSummary>
    +getLossSummary() : List<LossSummary>
    +getWaterSummary() : List<WaterConsumption>
    +exportPDF() : byte[]
    +exportExcel() : byte[]
  }

  class YieldSummary {
    -plotId : PlotId
    -plotName : String
    -yieldPerHectare : double
    -season : String
    +getPlotId() : PlotId
    +getYieldPerHectare() : double
    +getSeason() : String
  }

  class LossSummary {
    -plotId : PlotId
    -plotName : String
    -lossPercentage : double
    -cause : String
    +getPlotId() : PlotId
    +getLossPercentage() : double
    +getCause() : String
  }

  class WaterConsumption {
    -plotId : PlotId
    -plotName : String
    -totalLiters : double
    -season : String
    +getPlotId() : PlotId
    +getTotalLiters() : double
    +getSeason() : String
  }

  User "1" ..> "0..1" Dashboard : views if Pro or Enterprise >
  Dashboard "1" *-- "0..*" YieldSummary : contains >
  Dashboard "1" *-- "0..*" LossSummary : contains >
  Dashboard "1" *-- "0..*" WaterConsumption : contains >
}


' RELACIONES ENTRE BOUNDED CONTEXTS

Farmer "1" --> "0..*" Plot : owns >
AgriculturalManager "1" --> "0..*" Plot : manages >
Plot "1" *-- "0..*" SoilRecord : records >
Plot "1" *-- "0..*" IrrigationRecommendation : receives >
Plot "1" *-- "0..*" IrrigationSchedule : schedules >
Plot "1" *-- "0..*" ClimateAlert : receives >
User "1" --> "0..*" SupportTicket: creates >
@enduml
```

## 4.8. Database Design.

### 4.8.1. Database Diagrams.

![Imagen de la base de datos](report/assets/DiagramaDataBaseAgrotrack.png)


<br>
<br>


# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

Esta sección presentará las herramientas que se han utilizado durante
este proyecto para desarrollar nuestras plataformas digitales con una
gestión estructurada de los cambios, versiones y configuraciones dentro
del desarrollo de software.

### 5.1.1 Software Development Environment Configuration.

En el presente proyecto, para la etapa de diseño UX/UI se utilizó la
plataforma Figma, la cual permitió elaborar prototipos, definir la
estructura visual y organizar la experiencia de usuario de la solución
propuesta.

Para el desarrollo de la landing page se trabajó con WebStorm como
entorno de desarrollo, facilitando la edición y organización del código
del proyecto. Asimismo, se emplearon tecnologías base del desarrollo web
como HTML para la estructura del contenido, CSS para el diseño y estilos
visuales, y JavaScript para agregar interactividad en la página.

Finalmente, para el control de versiones y el trabajo colaborativo entre
los integrantes del equipo, se utilizaron Git y GitHub, herramientas que
permitieron registrar cambios y mantener un desarrollo ordenado del
proyecto.

**FIGMA:** Es una plataforma orientada al diseño de interfaces y
experiencia de usuario, utilizada para crear wireframes, mockups,
prototipos interactivos y propuestas visuales de alta fidelidad. Su
principal ventaja es el trabajo colaborativo en tiempo real, ya que
permite que varios integrantes del equipo participen de manera
simultánea desde distintas ubicaciones. Además, facilita la
planificación de la estructura visual y la navegación de la aplicación
antes de iniciar la etapa de desarrollo.

**Figura 1**\
*Logo de Figma*

![logo-figma](report/assets/logo-figma.webp)

*Nota.* Obtenido de:
https://www.iebschool.com/hub/wp-content/uploads/2024/01/s-1024x529-1-768x397.png

**HTML:** Es el lenguaje de marcado utilizado para definir la estructura
base de una página web. Permite organizar el contenido mediante
elementos como títulos, párrafos, imágenes, enlaces, formularios y
secciones, facilitando una correcta distribución de la información
dentro del sitio web.

**Figura 2**\
*Logo de HTML*

![logo-html](report/assets/logo-html.png)

*Nota.* Obtenido de:
<https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/250px-HTML5_logo_and_wordmark.svg.png>

**CSS:** Es un lenguaje de estilos empleado para personalizar la
apariencia visual de una página web. Permite modificar colores,
tipografías, tamaños, márgenes, posiciones y diseños responsivos,
logrando una presentación más atractiva y adaptable a distintos
dispositivos.

**Figura 3**\
*Logo de CSS*

![logo-css](report/assets/logo-css.png)

*Nota.* Obtenido de:
<https://lineadecodigo.com/wp-content/uploads/2014/04/css.png>

**JavaScript:** Es un lenguaje de programación orientado al desarrollo
web que permite incorporar dinamismo e interactividad en las páginas.
Gracias a JavaScript, es posible validar formularios, manipular
elementos del DOM, responder a eventos del usuario y mejorar la
experiencia general de navegación.

**Figura 4**\
*Logo de JavaScript*

![logo-javascript](report/assets/logo-javascript.png)

*Nota.* Obtenido de:
<https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRuHnJDLOcdm_0b6N6kNj-1OvO9KhKYgqIy0w&s>

**GIT:** Es un sistema de control de versiones ampliamente utilizado en
proyectos de software para registrar y administrar los cambios
realizados en el código fuente. Permite que varios desarrolladores
trabajen de manera colaborativa, manteniendo un historial detallado de
cada modificación. Al ser una herramienta distribuida, cada integrante
cuenta con una copia completa del repositorio en su equipo local.
Además, facilita la creación de ramas independientes para desarrollar
nuevas funcionalidades o corregir errores sin comprometer la versión
principal. Una vez finalizado el trabajo, los cambios pueden integrarse
de forma ordenada al proyecto principal.

**Figura 5**\
Logo de Git

![logo-git](report/assets/logo-git.png)

*Nota.* Obtenido de:
<https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSdd25hyNQOMs4Xx1Cv_A_oaT0zagfSWlXMBA&s>

**GITHUB:** Es una plataforma en la nube orientada al alojamiento de
repositorios Git, utilizada para almacenar, compartir y gestionar
proyectos de desarrollo de software. Proporciona herramientas para el
trabajo colaborativo como pull requests, revisión de código, control de
incidencias e integración continua. Asimismo, permite coordinar el
trabajo entre los miembros del equipo, mantener distintas versiones del
proyecto y conservar un historial completo de los avances realizados.

**Figura 6**\
*Logo de GitHub*

![logo-github](report/assets/logo-github.jpg)

*Nota.* Obtenido de:
<https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuYIprEvJ5lj-58xOPTE1xD_DBgdbrNhicyg&s>

### 5.1.2. Source Code Management

Con el propósito de mantener un control adecuado del código fuente y
facilitar el trabajo colaborativo entre los integrantes del equipo, se
utilizará la plataforma **GitHub**. Esta herramienta permitirá
administrar los cambios realizados en el proyecto, revisar los commits
efectuados por cada integrante y mantener un historial ordenado del
desarrollo.

Asimismo, dentro de la organización se han creado repositorios
independientes, cada uno destinado a un producto específico:

- Repositorio correspondiente al informe del proyecto:
  https://github.com/AgroTrack-Project/report
- Repositorio correspondiente a la landing page:
  https://github.com/AgroTrack-Project/Landing-Page

Para organizar el proceso de desarrollo y asegurar una integración
eficiente de los avances, se aplicará la metodología **GitFlow**, la
cual estructura el trabajo mediante ramas con responsabilidades
definidas.

**Ramas principales**

- **main**
  - Contiene la versión estable del proyecto.
  - Solo recibe cambios aprobados para producción.
  - Cada versión liberada seguirá el estándar **Semantic Versioning**.
- **develop**
  - Rama principal de desarrollo.
  - Integra nuevas funcionalidades y correcciones antes de pasar a
    producción.
  - Sirve como base para la creación de nuevas ramas de trabajo.

**Ramas de apoyo**

- **feature/**\*

  - Se crean desde `develop` para implementar nuevas funcionalidades o
    mejoras.
  - Convención de nombres:

  `feature/nombre-descriptivo`

  - Ejemplos:

  `feature/login-user`

  `feature/improve-navbar`

  - Una vez completadas, se integran nuevamente en `develop` mediante
    *pull request*.

- **release/**

  - Se crean cuando el proyecto está listo para preparar una nueva
    versión.
  - Permiten realizar ajustes finales, correcciones menores o cambios de
    documentación.
  - Convención de nombres:

  `release/version`

  - Ejemplo:

  `release/1.0.0`

- **hotfix/**\*

  - Se crean desde `main` para solucionar errores críticos detectados en
    producción.
  - Luego de la corrección, se integran tanto en `main` como en
    `develop`.

------------------------------------------------------------------------

**Conventional Commits**

Con el fin de mantener claridad y consistencia en el historial del
repositorio, los mensajes de commit seguirán la especificación
**Conventional Commits**.

Estructura general:

`<tipo>(<ámbito>): <descripción breve>`

Tipos utilizados:

- `feat`: nueva funcionalidad.
- `fix`: corrección de errores.
- `docs`: cambios en documentación.
- `style`: cambios visuales o de formato.
- `refactor`: mejora interna del código sin alterar funcionalidad.
- `test`: pruebas nuevas o modificadas.
- `chore`: tareas de mantenimiento general.

Ejemplos:

`feat(landing-page): add hero section`

`fix(navbar): correct responsive menu`

`docs(readme): update project structure`

\*\* Integrantes del equipo en GitHub \*\*

  User Name   Nombre Completo
  ----------- ---------------------------------------
  Delzekl     Martínez Gaona, Pablo Afranio
  DuDu-tech   Quispe Perez, Eder Edu
  elprrr      Alfaro Mallma, Alberto Joaquin
  Edu-VLL     Velasquez Laquihuanaco, Eduardo David
  Miler2003   Rodriguez Rojas, Miler Alexander

# 5.1.3. Source Code Style Guide & Coding Conventions

El equipo de AgroTrack adopta las siguientes convenciones de código para
garantizar consistencia, legibilidad y mantenibilidad en los
repositorios del proyecto. Todos los identificadores, comentarios y
documentación se redactan **en inglés**, sin excepción.

Para este primer avance, los lenguajes utilizados son HTML, CSS y
JavaScript, correspondientes al desarrollo de la Landing Page.

------------------------------------------------------------------------

**HTML**

Se adopta la **W3Schools HTML Style Guide and Coding Conventions** como
referencia principal, complementada con la **Google HTML/CSS Style
Guide**.

**Nomenclatura y estructura** - Los nombres de archivos HTML van en
`kebab-case`: `index.html`. - Los atributos se escriben siempre en
minúsculas: `class`, `id`, `href`, `src`, `type`, `aria-label`. - Se
usan comillas dobles para todos los valores de atributos:
`class="site-header"`. - La indentación es de **4 espacios**; no se usan
tabulaciones. - Se declara siempre el `DOCTYPE` y el atributo `lang` en
la etiqueta `<html>`: `<html lang="en">`. - Se usan elementos semánticos
de HTML5 en lugar de `<div>` genéricos cuando corresponde: `<header>`,
`<nav>`, `<main>`, `<section>`, `<footer>`. - El atributo `alt` es
obligatorio en todas las etiquetas `<img>`. - Se evitan estilos en línea
(`style="..."`); todo estilo va en la hoja CSS externa
`css/style.css`. - Los atributos de accesibilidad (`aria-label`,
`aria-expanded`, `aria-controls`) se incluyen en todos los elementos
interactivos. - Los textos traducibles llevan el atributo `data-i18n`
con su clave correspondiente para el sistema i18n. - Los event listeners
se declaran en el archivo `js/script.js`; no se usan atributos `onclick`
en línea salvo en los botones que invocan funciones globales
(`toggleLanguage`, `toggleMobileMenu`). **Ejemplo --- estructura base
del proyecto:**

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AgroTrack</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header class="site-header">
    <nav class="navbar">
        <a href="#" class="brand" aria-label="AgroTrack home">
            <img src="assets/agrotrack-logo.png" alt="AgroTrack logo">
        </a>
        <button
                class="hamburger-button"
                type="button"
                aria-label="Open navigation menu"
                aria-expanded="false"
                aria-controls="navCollapse"
                onclick="toggleMobileMenu()">
            <span></span>
            <span></span>
            <span></span>
        </button>
        <div class="nav-collapse" id="navCollapse">
            <div class="nav-menu">
                <a href="#features" data-i18n="nav.features">Features</a>
                <a href="#plans" data-i18n="nav.plans">Plans</a>
            </div>
            <div class="nav-actions">
                <button class="button-language header-language-button"
                        type="button"
                        onclick="toggleLanguage()"
                        aria-label="Toggle language">
                    <span class="language-icon" aria-hidden="true">🌐</span>
                    <span>EN | ES</span>
                </button>
                <a href="#" class="auth-button sign-in-button" data-i18n="nav.signIn">Sign in</a>
                <a href="#" class="auth-button sign-up-button" data-i18n="nav.signUp">Sign up</a>
            </div>
        </div>
    </nav>
</header>
<main>
    <section class="hero-section">
        <!-- section content -->
    </section>
</main>
<footer class="footer">
    <!-- footer content -->
</footer>
<script src="js/script.js"></script>
</body>
</html>
```

**Ejemplo --- sección con i18n y semántica correcta:**

``` html
<!-- Hero section -->
<section class="hero-section">
    <div class="hero-content">
        <div class="hero-text">
            <h1 class="hero-title">
                <span data-i18n="hero.titleLine1">Grow better with</span>
                <span class="hero-title-accent" data-i18n="hero.titleLine2">real data</span>
            </h1>
            <p class="hero-description" data-i18n="hero.description">
                AgroTrack helps you register your plots, monitor soil conditions,
                and receive clear irrigation recommendations.
            </p>
            <div class="hero-buttons">
                <a href="#plans" class="hero-primary-button">
                    <span data-i18n="hero.primaryCta">Get started now</span>
                    <span aria-hidden="true">→</span>
                </a>
                <a href="#demo" class="hero-secondary-button" data-i18n="hero.secondaryCta">
                    Request demo
                </a>
            </div>
        </div>
        <div class="hero-image-wrapper">
            <img src="assets/cultivo-agotrack.png" alt="Crop field" class="hero-image">
        </div>
    </div>
</section>
```

------------------------------------------------------------------------

**CSS**

Se adopta la **Google HTML/CSS Style Guide** como referencia principal.

**Nomenclatura** - Los selectores de clase usan `kebab-case`:
`.site-header`, `.hero-section`, `.plan-card`, `.feature-card`. - Los
identificadores (`id`) se reservan para anclas de navegación y elementos
únicos del DOM: `#features`, `#plans`, `#audience`, `#demo`,
`#navCollapse`, `#fullName`, `#email`. - No se usan estilos de `id` para
reglas CSS generales; se prefieren clases. - Los modificadores de estado
o variante se nombran con doble guion BEM: `.plan-card--active`,
`.hamburger-button.active`, `.nav-collapse.open`. - Las variables CSS
siguen el patrón `--descriptive-name` y se declaran en `:root`.
**Formato** - Cada declaración en su propia línea, con punto y coma al
final. - Un espacio entre el selector y la llave de apertura `{`. -
Indentación de **4 espacios**. - Las propiedades se ordenan siguiendo el
criterio: posicionamiento → modelo de caja → tipografía → visual →
miscelánea. - El uso de `!important` se evita; si es necesario, se
documenta con un comentario explicativo. - Los colores, tamaños y
espaciados reutilizables se definen como variables en `:root`.
**Variables globales (design tokens del proyecto):**

``` css
:root {
    --primary-green: #2D7A3A;
    --dark-green:    #2C3E2D;
    --soft-green:    #8FC594;
    --light-bg:      #F5F0E8;
    --white:         #FFFFFF;
    --soft-gray:     #ECE8E1;
    --text-muted:    #5F615C;
    --border-color:  #D9D9D9;
}
```

**Ejemplo --- navbar y header:**

``` css
.site-header {
    background-color: var(--soft-green);
    border-bottom: 2px solid rgba(44, 62, 45, 0.08);
    position: sticky;
    top: 0;
    z-index: 1000;
    overflow: visible;
}
 
.navbar {
    max-width: 1280px;
    margin: 0 auto;
    padding: 18px 42px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
    flex-wrap: wrap;
    position: relative;
}
```

**Ejemplo --- botones con estados:**

``` css
.auth-button {
    min-width: 120px;
    min-height: 44px;
    padding: 10px 20px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 700;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    transition: transform 0.2s ease, opacity 0.2s ease;
}
 
.auth-button:hover {
    transform: translateY(-1px);
    opacity: 0.92;
}
 
.sign-in-button {
    background-color: #DDE6D8;
    color: #1F2E1F;
}
 
.sign-up-button {
    background-color: var(--primary-green);
    color: var(--white);
}
```

**Ejemplo --- hamburger menu con animación de estado activo:**

``` css
.hamburger-button span {
    display: block;
    width: 22px;
    height: 2.5px;
    background-color: #1F2E1F;
    border-radius: 2px;
    transition: 0.25s ease;
}
 
.hamburger-button.active span:nth-child(1) {
    transform: translateY(8px) rotate(45deg);
}
 
.hamburger-button.active span:nth-child(2) {
    opacity: 0;
}
 
.hamburger-button.active span:nth-child(3) {
    transform: translateY(-8px) rotate(-45deg);
}
```

**Responsive design --- mobile-first con tres breakpoints:**

``` css
/* Tablet: ≤ 1024px */
@media (max-width: 1024px) {
    .navbar {
        padding: 16px 24px;
        justify-content: center;
    }
    .hero-section {
        padding: 60px 24px;
    }
}
 
/* Mobile: ≤ 768px */
@media (max-width: 768px) {
    .hamburger-button {
        display: flex;
    }
    .nav-collapse {
        display: none;
        position: absolute;
        top: calc(100% + 10px);
        right: 20px;
        width: min(320px, calc(100vw - 40px));
        background: #F5F0E8;
        border-radius: 18px;
        box-shadow: 0 16px 30px rgba(0, 0, 0, 0.12);
        padding: 16px;
        z-index: 1200;
        flex-direction: column;
    }
    .nav-collapse.open {
        display: flex;
    }
    .hero-content {
        flex-direction: column;
        text-align: center;
    }
}
 
/* Small mobile: ≤ 480px */
@media (max-width: 480px) {
    .hero-buttons {
        flex-direction: column;
        align-items: stretch;
    }
    .hero-primary-button,
    .hero-secondary-button {
        width: 100%;
    }
    .plan-card {
        min-width: 100%;
    }
}
```

------------------------------------------------------------------------

**JavaScript**

Se adopta la **Google JavaScript Style Guide** como referencia
principal.

**Nomenclatura** - Variables y funciones: `camelCase` →
`currentLanguage`, `toggleLanguage()`, `toggleMobileMenu()`. -
Constantes de datos: `camelCase` cuando es un objeto de configuración →
`translation`. - Archivos: `kebab-case` → `script.js`. **Convenciones
generales** - Se usa `let` para variables que cambian de valor (como
`currentLanguage`) y `const` para datos que no se reasignan (como el
objeto `translation`). - Se usan funciones declaradas con `function`
para las funciones globales invocadas desde el HTML (`toggleLanguage`,
`toggleMobileMenu`). - Las funciones se documentan con JSDoc indicando
tipo de parámetros y comportamiento. - Los comentarios de bloque
(`/** */`) se usan para describir el propósito de funciones y objetos
complejos. - Los comentarios en línea (`//`) explican el *por qué* de
una decisión, no el *qué* hace el código. - Los textos de la interfaz
nunca se escriben directamente en JS; se gestionan exclusivamente a
través del objeto `translation` usando claves `data-i18n`. **Ejemplo ---
sistema de internacionalización (i18n):**

``` javascript
/**
 * Current active language. Defaults to English.
 * @type {string}
 */
let currentLanguage = "en";
 
/**
 * Translation object containing all UI strings for each supported language.
 * Supported locales: en -> English, es_419 -> Spanish (Latin America).
 * To add new text, add the key in both locales and use data-i18n="key" in HTML.
 * @type {Object}
 */
const translation = {
    en: {
        // Navbar
        "nav.features": "Features",
        "nav.plans":    "Plans",
        "nav.forWho":   "For who",
        "nav.demo":     "Demo",
        "nav.signIn":   "Sign in",
        "nav.signUp":   "Sign up",
 
        // Hero section
        "hero.titleLine1":   "Grow better with",
        "hero.titleLine2":   "real data",
        "hero.description":  "AgroTrack helps you register your plots, monitor soil conditions, and receive clear irrigation recommendations.",
        "hero.primaryCta":   "Get started now",
        "hero.secondaryCta": "Request demo",
 
        // ... (resto de claves)
    },
    es_419: {
        // Navbar
        "nav.features": "Características",
        "nav.plans":    "Planes",
        "nav.forWho":   "Para quién",
        "nav.demo":     "Demo",
        "nav.signIn":   "Ingresar",
        "nav.signUp":   "Registrarse",
 
        // Hero section
        "hero.titleLine1":   "Cultiva mejor con",
        "hero.titleLine2":   "datos reales",
        "hero.description":  "AgroTrack te ayuda a registrar tus parcelas, monitorear el suelo y recibir recomendaciones claras de riego.",
        "hero.primaryCta":   "Comenzar ahora",
        "hero.secondaryCta": "Solicitar demo",
 
        // ... (resto de claves)
    }
};
 
/**
 * Toggles the page language between English and Spanish.
 * Updates all elements with data-i18n attribute and the HTML lang attribute
 * for screen readers (accessibility).
 */
function toggleLanguage() {
    // Switch between English and Spanish
    currentLanguage = currentLanguage === "en" ? "es_419" : "en";
 
    // Update HTML lang attribute for screen readers (a11y)
    document.documentElement.lang = currentLanguage === "en" ? "en" : "es";
 
    // Find all translatable elements and update their text
    const elements = document.querySelectorAll("[data-i18n]");
    elements.forEach(function (element) {
        const key = element.getAttribute("data-i18n");
        element.textContent = translation[currentLanguage][key];
    });
}
```

**Ejemplo --- menú hamburguesa con accesibilidad:**

``` javascript
/**
 * Toggles the mobile navigation menu open/closed.
 * Updates aria-expanded for screen reader compatibility.
 */
function toggleMobileMenu() {
    const navCollapse      = document.getElementById("navCollapse");
    const hamburgerButton  = document.querySelector(".hamburger-button");
 
    navCollapse.classList.toggle("open");
    hamburgerButton.classList.toggle("active");
 
    const isExpanded = navCollapse.classList.contains("open");
    hamburgerButton.setAttribute("aria-expanded", isExpanded ? "true" : "false");
}
 
/**
 * Resets the mobile menu state when the viewport is resized above 900px.
 * Prevents the menu from remaining open when switching to desktop view.
 */
window.addEventListener("resize", function () {
    const navCollapse     = document.getElementById("navCollapse");
    const hamburgerButton = document.querySelector(".hamburger-button");
 
    if (window.innerWidth > 900 && navCollapse && hamburgerButton) {
        navCollapse.classList.remove("open");
        hamburgerButton.classList.remove("active");
        hamburgerButton.setAttribute("aria-expanded", "false");
    }
});
```

# 5.1.4. Software Deployment Configuration

Esta sección describe la configuración y los pasos necesarios para
desplegar la Landing Page de AgroTrack a partir del repositorio de
código fuente.

**Repositorio:** <https://github.com/agrotrack-project/Landing-Page>\
**URL publicada:** <https://agrotrack-project.github.io/Landing-Page/>\
**Rama de producción:** `develop`

------------------------------------------------------------------------

**Landing Page**

**Stack:** HTML5 + CSS3 + JavaScript vanilla\
**Plataforma de despliegue:** GitHub Pages

**Estructura del repositorio**

    Landing-Page/
    ├── assets/
    │   ├── agrotrack-logo.png
    │   ├── cultivo-agotrack.png
    │   ├── logo-facebook.png
    │   ├── logo-instagram.png
    │   ├── logo-tiktok.png
    │   ├── testimonial1.jpg
    │   ├── testimonial2.jpg
    │   └── testimonial3.jpeg
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    └── index.html

**Pasos de despliegue**

1.  Confirmar que la rama `develop` contiene la versión estable de la
    Landing Page y que `index.html` se encuentra en la raíz del
    repositorio.
2.  En el repositorio de GitHub, ir a **Settings → Pages**.
3.  En la sección **Build and deployment**, configurar:
    - **Source:** Deploy from a branch
    - **Branch:** `develop`
    - **Folder:** `/ (root)`
4.  Hacer clic en **Save**. GitHub Pages generará automáticamente la URL
    pública.
5.  Esperar entre 1 y 2 minutos y verificar que la página carga
    correctamente en:
    `https://agrotrack-project.github.io/Landing-Page/`
6.  Comprobar que el diseño responde correctamente en desktop (≥
    1025px), tablet (769--1024px) y móvil (≤ 768px).
7.  Verificar que el toggle de idioma (EN \| ES) funciona correctamente
    en todos los breakpoints. \### Actualizaciones posteriores

Cada `git push` a la rama `develop` desencadena un redespliegue
automático en GitHub Pages. No se requiere ninguna acción manual
adicional.

``` bash
# Flujo estándar para publicar cambios
git add .
git commit -m "feat: update hero section copy"
git push origin develop
```

GitHub Pages tomará los nuevos archivos y publicará la versión
actualizada en aproximadamente 1 minuto.

 **Verificación post-despliegue**
 
Tras cada despliegue se recomienda verificar los siguientes puntos:
 
| Verificación | Detalle |
|---|---|
| Carga de assets | Logo, imágenes de cultivo y fotos de testimonios visibles |
| Navegación | Links del navbar redirigen a las secciones correctas (`#features`, `#plans`, `#audience`, `#demo`) |
| Toggle de idioma | Cambia correctamente entre EN y ES en todos los textos con `data-i18n` |
| Menú hamburguesa | Se abre y cierra correctamente en móvil; desaparece en desktop |
| Formulario de demo | Los campos `fullName` y `email` tienen validación `required` activa |
| Responsive | Sin scroll horizontal en ningún breakpoint |

  -----------------------------------------------------------------------

### 5.2.1 Sprint 1

El primer sprint se centrará en la implementación de las secciones de
Página de inicio, Servicios y Aplicaciones de AgroTrack. El objetivo es
crear una interfaz clara y funcional que presente la plataforma y sus
principales características a los agricultores y empresas agrícolas.

#### 5.2.1.1 Sprint Planning 1

Ahora, mostraremos nuestro sprint planning. En esta sección, vamos a explicar la
reunión inicial del sprint realizado, detallando lo que se planeó, acordó y revisó en la reunión.

| Sprint #                     | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint Planning Background   | En el sprint decidimos reunirnos para verificar el progreso de cada integrante y del proyecto desde el punto de vista grupal. Luego de ello buscamos mejoras y nuevas acciones.                                                                                                                                                                                                                                                          |
| Date                         | 2025-04-18                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Time                         | 21:05 PM                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Location                     | Google Meet Group Call                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Prepared By                  | Velasquez Laquihuanaco, Eduardo David                                                                                                                                                                                                                                                                                                                                                                                                    |
| Attendees                    | Martínez Gaona, Pablo Afranio <br> Quispe Perez, Eder Edu <br> Rodriguez Rojas, Miler Alexander <br> Alfaro Mallma, Alberto Joaquin                                                                                                                                                                                                                                                                                                      |
| Sprint Review Summary        | Revisamos nuestras metas del negocio, discutimos las user stories y dimos feedback. También revisamos riesgos futuros y el avance individual y grupal.                                                                                                                                                                                                                                                                                   |
| Sprint Retrospective Summary | **Start:** Debemos comunicarnos más entre nosotros. <br> **Continue:** Hacer preguntas al Product Owner. <br> **Stop:** Dejar tareas para último momento. <br> **Continue:** Hacer preguntas al product owner hacer reuniones interdiarias para priorizar el avance                                                                                                                                                                      |
| Sprint Goal & User Stories   |                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Spring n Goal                | Our focus is on implementing the core functionalities of the landing page and user registration module. We believe this provides a clear access point and an organized onboarding experience for farmers and agricultural businesses. This will be validated when users are able to successfully enter the platform, complete the registration process, and navigate smoothly to their main dashboard to manage agricultural activities. |                                                                                                                                                                                                                                                                  |
| Sprint n Velocity            | 4                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Sum of Story Points          | 7                                                                                                                                                                                                                                                                                                                                                                                                                                        |       
  ----------------------------------------------------------------------------------

<br>

#### 5.2.1.2 Aspect Leaders and Collaborators.

| Team Member (Last Name, First Name)   | GitHub Username | Landing Page Leader (L) / Collaborator (C) | Documentation Leader (L) / Collaborator (C) | Epics Leader (L) / Collaborator (C) |
|---------------------------------------|-----------------|----------------------------------------|---|-------------------------------------|
| Alfaro Mallma, Alberto Joaquin        | elprrr          | C                                      | C | C                                   |
| Martínez Gaona, Pablo Afranio         | Delzekl         | C                                      | C | C                                   |
| Quispe Perez, Eder Edu                | DuDu-tech       | C                                      | C | C                                   |
| Rodriguez Rojas, Miler Alexander      | Miler2003       | C                                      | C | C                                   |
| Velasquez Laquihuanaco, Eduardo David | Edu-VLL         | L                                      | L | L                                   |



#### 5.2.1.3. Sprint Backlog 1

Durante este primer sprint, el objetivo principal del equipo es
desarrollar la Landing Page de AgroTrack. Para lograrlo, se definieron
tareas asociadas a cada historia de usuario relacionada con la Landing
Page, asignándolas a los integrantes del equipo. Además, para una mejor
organización y seguimiento del backlog, se utilizó la herramienta
"**Trello**".

**Figura**

![Sprint Backlog 1](report/assets/sprint-backlog.png)

*Sprint 1 de AgroTrack*

*Nota* Elaboración propia. Obtenido de
https://trello.com/invite/b/69ec6b9c1f448409979be07f/ATTI57cb684f86da5dce34b16c20796587777599AEFD/agrotrack-sprint-backlog-1

 
#### 5.2.1.4  Development Evidence for Sprint Review

| Repository                                  | Branch  | Commit Id                                                           | Commit Message                                                                                                                                                                                                                                                                          | Body | Commited on (Date) |
|---------------------------------------------|---------|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|--------------------|
| Edu-VLL/AgroTack-Project-Landing-page       | develop | <br>23e7ffe<br/> <br>3c5e87e<br/> <br>2149b10<br/> <br>d00435b<br/> | <br> feat: Add plans seccion on Landing Page<br/>  <br> feat: Add button logic EN/ES and translate <br/> <br> feat: Add words in EN/ES for translate<br/> <br>Add html structure of demo form<br/>                                                                                      | - | 24/04/2025 |
| DuDu-tech/AgroTack-Project-Landing-page     | develop | <br>da737c7<br/>                                                    | <br> feat: add problem section on landing page <br/>                                                                                                                                                                                                                                    | - | 24/04/2025 |
| elprrr/AgroTack-Project-Landing-page        | develop | <br>6711fe9<br/> <br>2144fe2<br/>                                   | <br> feat(functions-section): add features grid section with soil, irrigation, weather and crop history cards <br/> <br> feat(segments-section): add target audience section with farmer and agricultural business owner profile cards <br/>                                                                                                                                                                                                                                   | - | 24/04/2025 |
| Miler2003/AgroTack-Project-Landing-page     | develop | <br>55db4bf<br/> <br>f28b50b<br/> <br>f26a98a<br/>                  | <br> feat: add footer section with navigation, social media, contact and footer links also added copyright and terms and conditions. <br/> <br> feat: add footer translation of english language strings and spanish language strings. <br/> <br> feat: add footer section styles <br/> | - | 24/04/2025 |
| Delzekl/AgroTack-Project-Landing-page       | develop | <br>039e4af<br/>                                                    | <br> feat: implement landing page hero section <br/>                                                                                                                                                                                                                                    | - | 24/04/2025 |

#### 5.2.1.5. Execution Evidence for Sprint Review

Fotos de la landing implementada y video que ilustre y explique la
visualización y navegación.

![landing page](report/assets/landing-page-en-web.png)

link de la landing: https://agrotrack-project.github.io/Landing-Page/

link del video:
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQCHKXSXfiGjTKYe4gDB3oUZAWgYlplm50CGrMfFiBHi4aI?e=fnoiA6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante este Sprint, el equipo de desarrollo se centró en definir la
visión inicial del backend de AgroTrack, estableciendo las bases
necesarias para el funcionamiento interno de la plataforma. Esta etapa
permitió organizar la estructura principal del sistema y proyectar cómo
se gestionará la información relacionada con las actividades agrícolas.

El backend de AgroTrack estará orientado a facilitar la administración
de procesos clave dentro del entorno agrícola, permitiendo un manejo más
ordenado de datos, recursos y operaciones diarias. Asimismo, servirá
como soporte para futuras funcionalidades que contribuirán a mejorar la
eficiencia y el control dentro de la plataforma.

Este avance representa un paso importante para el crecimiento del
proyecto, ya que permitirá consolidar una base sólida sobre la cual se
desarrollarán las siguientes etapas del sistema.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para llevar a cabo el deployment correspondiente a este sprint, se
realizaron diversas actividades orientadas a publicar y poner en
funcionamiento la landing page del proyecto. A continuación, se presenta
un resumen del proceso ejecutado.

La landing page fue desplegada como un sitio web público mediante
**GitHub Pages**, con el fin de que pueda ser accesible para cualquier
usuario. Como primer paso, se creó una cuenta en GitHub y se configuró
un repositorio público con el nombre asignado al proyecto.

Posteriormente, se cargaron los archivos desarrollados de la página web
dentro del repositorio. Luego, desde la sección de configuración, se
habilitó la opción de **GitHub Pages** para publicar el contenido en
línea.

Finalmente, se verificó el correcto funcionamiento del sitio web y su
disponibilidad en internet. En caso de requerir modificaciones o
mejoras, solo es necesario actualizar los archivos del repositorio para
que los cambios se reflejen nuevamente en la página publicada.

**Figura**\
*Evidencia de deployment 1*

![Repo de la landing pade](report/assets/git-repo-laning-page.jpeg)

*Nota.* Elaboración propia.

**Figura**\
*Evidencia de deployment 2*

![Landing page en funcionamiento](report/assets/landing-page-en-web.png)

*Nota.* Elaboración propia.

#### 5.2.1.8 Team Collaboration Insights during Sprint

![contribucion del equipo](report/assets/team-contribution.png)

*Nota.* Elaboración propia.

### 5.2.2 Sprint 2

El segundo sprint se centrará en el desarrollo del Frontend Web Application de AgroTrack, distribuyendo las funcionalidades entre los miembros del equipo. El objetivo es construir las vistas principales de la plataforma, permitiendo a los agricultores acceder al sistema, registrarse y gestionar sus parcelas y cultivos desde un panel funcional e intuitivo.

#### 5.2.2.1. Sprint Planning 2

Se presenta a continuación el resumen del Sprint Planning Meeting para el Sprint 2.

| Campo | Detalle |
|-------|---------|
| **Sprint #** | Sprint 2 |
| **Sprint Planning Background** | |
| **Date** | 2025-05-19 |
| **Time** | 19:00 PM |
| **Location** | Virtual – Discord (canal General) |
| **Prepared By** | Velasquez Laquihuanaco, Eduardo David |
| **Attendees (to planning meeting)** | Alfaro Mallma, Alberto Joaquin / Martínez Gaona, Pablo Afranio / Quispe Perez, Eder Edu / Rodriguez Rojas, Miler Alexander / Velasquez Laquihuanaco, Eduardo David |
| **Sprint 1 – Review Summary** | Durante el Sprint 1 se desarrolló e implementó la primera versión del Landing Page de AgroTrack, cubriendo las User Stories correspondientes a la Épica 01. La Landing Page fue desplegada exitosamente mediante GitHub Pages. |
| **Sprint 1 – Retrospective Summary** | El equipo identificó como oportunidad de mejora la corrección de enlaces internos del Landing Page. En términos generales, la dinámica de trabajo colaborativo fue adecuada para el alcance del Sprint. |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Our focus is on implementing the Frontend Web Application. We believe it delivers a clear entry point and structured onboarding experience to farmers and agricultural staff. This will be confirmed when users are able to successfully access the platform, complete the registration process, and navigate to their plots dashboard without friction. |
| **Sprint 2 Velocity** | 7 |
| **Sum of Story Points** | 7 |


#### 5.2.2.2. Aspect Leaders and Collaborators

En el Sprint 2, los principales aspectos considerados corresponden a los bounded contexts y componentes técnicos trabajados: Gestión de Parcelas, Gestión de Cultivos, Monitoreo del Suelo, Alertas Climáticas e Interfaz de Perfil de Usuario.

| Team Member (Last Name, First Name) | GitHub Username | Gestión de Parcelas | Gestión de Cultivos | Monitoreo del Suelo | Alertas Climáticas | Perfil de Usuario |
|---|---|---|---|---|---|---|
| Alfaro Mallma, Alberto Joaquin | albertoalfaro | L | C | C | C | C |
| Martínez Gaona, Pablo Afranio | pabloafranio | C | C | L | C | C |
| Quispe Perez, Eder Edu | ederedu0912 | C | L | C | C | C |
| Rodriguez Rojas, Miler Alexander | milerrodr | C | C | C | L | C |
| Velasquez Laquihuanaco, Eduardo David | Edu-VLL | C | C | C | C | L |

#### 5.2.2.3. Sprint Backlog 2

El objetivo principal del Sprint 2 fue implementar el Frontend Web Application de AgroTrack, 
cubriendo la gestión de perfil de usuario, parcelas, cultivos, monitoreo del suelo, 
recomendaciones de riego y alertas climáticas. A continuación se presenta el tablero 
del sprint y la descomposición de User Stories en Work-Items/Tasks.

**Figura**

![Sprint Backlog 2](report/assets/sprint-backlog-2.png)

*Sprint 2 de AgroTrack*

*Nota.* Elaboración propia. Obtenido de https://trello.com/invite/b/6a082c484e76c24a6bf159db/ATTIeacb888e3799fbf438b8caf8a0d78ced55CA92BA/agrotrack-sprint-backlog-2

| User Story Id | User Story | Work-Item / Task Id | Work-Item / Task Title | Work-Item / Task Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---|---|---|---|
| US13 | Editar datos del perfil personal | T-001 | Maquetar vista de perfil de usuario | Construir el componente ProfilePage con formulario para editar nombre, correo y datos personales del usuario. Aplicar validaciones reactivas. | 3 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-002 | Conectar formulario de perfil con MockAPI | Enviar los cambios del perfil mediante PUT al endpoint correspondiente y mostrar mensaje de confirmación. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| US15 | Registrar una nueva parcela | T-003 | Maquetar formulario de registro de parcela | Construir el componente PlotForm con campos nombre, ubicación, tamaño y tipo de suelo, con validaciones reactivas. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| | | T-004 | Conectar formulario con endpoint POST /plots | Enviar los datos al endpoint, mostrar spinner durante la petición y notificar al usuario con mensaje de éxito o error. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| US16 | Ver listado de mis parcelas | T-005 | Construir vista PlotsListPage con grilla de tarjetas | Maquetar grilla responsive de tarjetas mostrando nombre, ubicación, tamaño y estado de cada parcela. Incluir botón para crear nueva parcela. | 4 | Alfaro Mallma, Alberto Joaquin | Done |
| | | T-006 | Implementar estado vacío (empty state) | Cuando GET /plots responde vacío, mostrar mensaje con CTA para registrar la primera parcela. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| US17 | Editar información de una parcela | T-007 | Reutilizar PlotForm en modo edición | Adaptar PlotForm para precargar datos existentes via GET /plots/:id y guardar cambios con PUT /plots/:id. | 3 | Martínez Gaona, Pablo Afranio | Done |
| US18 | Eliminar una parcela registrada | T-008 | Implementar modal de confirmación de eliminación | Mostrar modal de advertencia antes de ejecutar DELETE /plots/:id. Refrescar listado tras eliminación exitosa. | 2 | Rodriguez Rojas, Miler Alexander | Done |
| US19 | Ver detalle de una parcela específica | T-009 | Construir vista PlotDetailPage | Maquetar vista de detalle con secciones de información general, cultivos activos y estado del suelo. Consumir endpoints correspondientes. | 4 | Quispe Perez, Eder Edu | Done |
| US20 | Registrar un cultivo en una parcela | T-010 | Maquetar formulario CropForm | Construir formulario con campos tipo de cultivo, fecha de siembra y notas opcionales, vinculado al plotId de la parcela actual. | 3 | Quispe Perez, Eder Edu | Done |
| | | T-011 | Conectar formulario con POST /crops | Enviar el cultivo al endpoint, actualizar lista de cultivos activos en la vista de detalle y mostrar confirmación. | 2 | Quispe Perez, Eder Edu | Done |
| US21 | Ver los cultivos activos de una parcela | T-012 | Construir sección de cultivos activos en PlotDetailPage | Mostrar lista de cultivos activos con tipo, fecha de siembra y estado. Incluir empty state si no hay cultivos. | 3 | Quispe Perez, Eder Edu | Done |
| US22 | Editar información de un cultivo | T-013 | Implementar edición de cultivo | Adaptar CropForm para modo edición, precargando datos via GET y guardando cambios con PUT. | 2 | Quispe Perez, Eder Edu | Done |
| US23 | Marcar un cultivo como cosechado o finalizado | T-014 | Implementar botón de marcar cultivo como finalizado | Agregar opción para cambiar estado del cultivo a "Finalizado" mediante PATCH y moverlo al historial. | 3 | Quispe Perez, Eder Edu | Done |
| US24 | Ver historial de cultivos anteriores por parcela | T-015 | Construir sección de historial de cultivos | Mostrar cultivos finalizados con tipo, fecha de siembra y fecha de cosecha en la vista de detalle de la parcela. | 3 | Quispe Perez, Eder Edu | Done |
| US25 | Ingresar manualmente datos de humedad del suelo | T-016 | Maquetar formulario SoilEntryForm con validación 0–100 | Construir formulario con input numérico para humedad con validación inline que bloquee el guardado si el valor está fuera de rango. | 3 | Martínez Gaona, Pablo Afranio | Done |
| US26 | Ingresar manualmente datos de temperatura del suelo | T-017 | Agregar campo de temperatura al SoilEntryForm | Añadir input numérico para temperatura con validación de formato numérico al formulario de datos del suelo. | 2 | Martínez Gaona, Pablo Afranio | Done |
| US27 | Ver el estado actual del suelo de una parcela | T-018 | Mostrar indicador visual del estado del suelo | Mostrar badge con estado (Bajo, Normal, Alto) usando los colores de la paleta institucional tras guardar el registro. | 2 | Martínez Gaona, Pablo Afranio | Done |
| US28 | Ver historial de registros del suelo por parcela | T-019 | Construir sección de historial del suelo | Mostrar registros de suelo ordenados del más reciente al más antiguo con fecha, humedad y temperatura. | 3 | Martínez Gaona, Pablo Afranio | Done |
| US29 | Recibir recomendación de riego basada en datos del suelo | T-020 | Implementar lógica de recomendación de riego | Mostrar recomendación de riego basada en el último nivel de humedad registrado usando los umbrales definidos. | 3 | Rodriguez Rojas, Miler Alexander | Done |
| US30 | Ver el cronograma de riego sugerido | T-021 | Construir vista de cronograma de riego | Maquetar sección con fechas y horarios sugeridos de riego basados en los datos del suelo registrados. | 3 | Rodriguez Rojas, Miler Alexander | Done |
| US31 | Confirmar o rechazar una recomendación de riego | T-022 | Implementar botones de confirmar/rechazar recomendación | Agregar botones de confirmación y rechazo en la vista de recomendación y registrar la respuesta en el historial. | 2 | Rodriguez Rojas, Miler Alexander | Done |
| US32 | Ver historial de riegos aplicados en una parcela | T-023 | Construir sección de historial de riegos | Mostrar registros de riego con fecha, hora e indicador de si la recomendación fue seguida o no. | 2 | Rodriguez Rojas, Miler Alexander | Done |
| US33 | Recibir alerta ante riesgo de helada | T-024 | Implementar lógica de alerta por helada | Conectar con OpenWeatherMap y generar alerta cuando temp_min <= 5°C o feels_like <= 5°C. | 4 | Velasquez Laquihuanaco, Eduardo David | In-Process |
| US34 | Recibir alerta ante riesgo de sequía | T-025 | Implementar lógica de alerta por sequía | Detectar sequía cuando 80%+ de registros del forecast de 5 días tienen pop < 0.1. | 4 | Velasquez Laquihuanaco, Eduardo David | In-Process |
| US35 | Recibir alerta ante lluvias intensas previstas | T-026 | Implementar lógica de alerta por lluvia intensa | Generar alerta cuando algún registro del forecast tiene pop > 0.7. Mostrar notificación en dashboard. | 3 | Velasquez Laquihuanaco, Eduardo David | Done |
| US36 | Ver historial de alertas climáticas recibidas | T-027 | Construir vista de historial de alertas | Mostrar alertas ordenadas por fecha con tipo y descripción. Incluir empty state si no hay alertas. | 3 | Velasquez Laquihuanaco, Eduardo David | Done |
| US37 | Configurar qué tipo de alertas quiero recibir | T-028 | Implementar configuración de alertas | Agregar toggles para activar/desactivar cada tipo de alerta desde la vista de configuración. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| US38 | Ver panel de control con resumen de todas mis parcelas | T-029 | Construir dashboard para empresario agrícola | Maquetar panel con resumen de cada parcela mostrando estado de humedad, cultivo activo y última alerta. | 4 | Alfaro Mallma, Alberto Joaquin | Done |
| US39 | Ver rendimiento por parcela | T-030 | Construir sección de rendimiento por parcela | Mostrar métricas de producción por parcela ordenadas de mayor a menor rendimiento. | 3 | Martínez Gaona, Pablo Afranio | Done |
| US40 | Ver porcentaje de pérdidas estimadas por parcela | T-031 | Construir sección de pérdidas estimadas | Mostrar porcentaje de pérdidas por parcela junto con las causas registradas. | 3 | Martínez Gaona, Pablo Afranio | Done |
| US41 | Ver consumo de agua registrado por temporada | T-032 | Construir sección de consumo de agua | Mostrar consumo total de agua por parcela agrupado por temporada. | 3 | Rodriguez Rojas, Miler Alexander | Done |
| US42 | Exportar reporte de producción en formato PDF o Excel | T-033 | Implementar exportación de reporte | Agregar botones para exportar reporte de producción en PDF y Excel desde la sección de reportes. | 4 | Rodriguez Rojas, Miler Alexander | Done |
| TS03 | Endpoint para crear una parcela | T-034 | Configurar endpoint POST /plots en MockAPI | Verificar y configurar el endpoint de creación de parcelas en MockAPI con los campos requeridos. | 1 | Alfaro Mallma, Alberto Joaquin | Done |
| TS04 | Endpoint para obtener parcelas de un usuario | T-035 | Configurar endpoint GET /plots en MockAPI | Verificar endpoint de listado de parcelas filtrando por userId. | 1 | Alfaro Mallma, Alberto Joaquin | Done |
| TS05 | Endpoint para actualizar una parcela | T-036 | Configurar endpoint PUT /plots/:id en MockAPI | Verificar endpoint de actualización de parcela por ID. | 1 | Martínez Gaona, Pablo Afranio | Done |
| TS06 | Endpoint para eliminar una parcela | T-037 | Configurar endpoint DELETE /plots/:id en MockAPI | Verificar endpoint de eliminación de parcela por ID. | 1 | Rodriguez Rojas, Miler Alexander | Done |
| TS07 | Endpoint para crear un cultivo | T-038 | Configurar endpoint POST /crops en MockAPI | Verificar endpoint de creación de cultivo vinculado a una parcela. | 1 | Quispe Perez, Eder Edu | Done |
| TS08 | Endpoint para obtener cultivos de una parcela | T-039 | Configurar endpoint GET /crops en MockAPI | Verificar endpoint de listado de cultivos filtrando por plotId. | 1 | Quispe Perez, Eder Edu | Done |
| TS09 | Endpoint para actualizar el estado de un cultivo | T-040 | Configurar endpoint PATCH /crops/:id en MockAPI | Verificar endpoint para actualizar estado de cultivo a finalizado. | 1 | Quispe Perez, Eder Edu | Done |
| TS10 | Endpoint para registrar datos del suelo | T-041 | Configurar endpoint POST /soil-records en MockAPI | Verificar endpoint de registro de humedad y temperatura del suelo con validaciones de rango. | 1 | Martínez Gaona, Pablo Afranio | Done |
| TS11 | Endpoint para obtener historial de datos del suelo | T-042 | Configurar endpoint GET /soil-records en MockAPI | Verificar endpoint de historial de suelo ordenado por fecha descendente. | 1 | Martínez Gaona, Pablo Afranio | Done |
| TS12 | Endpoint para obtener alertas climáticas de una parcela | T-043 | Configurar endpoint GET /climate-alerts en MockAPI | Verificar endpoint de alertas climáticas activas filtrando por plotId. | 1 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS13 | Endpoint para crear una alerta climática | T-044 | Configurar endpoint POST /climate-alerts en MockAPI | Verificar endpoint de creación de alertas climáticas vinculadas a una parcela. | 1 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS14 | Endpoint para obtener recomendación de riego | T-045 | Configurar endpoint GET /irrigation-recommendations en MockAPI | Verificar endpoint de recomendación de riego basado en último registro del suelo. | 1 | Rodriguez Rojas, Miler Alexander | Done |
| TS15 | Endpoint para registrar respuesta a una recomendación | T-046 | Configurar endpoint POST /irrigation-recommendations/:id/response en MockAPI | Verificar endpoint para registrar si el agricultor aceptó o rechazó la recomendación. | 1 | Rodriguez Rojas, Miler Alexander | Done |


#### 5.2.2.4. Development Evidence for Sprint Review

Durante el S los bounded contexts de farming, soil monitoring, climate alerts e identity. El desarrollo se realizó en ramas feature independientes por cada integrante, las cuales fueron integradas a develop mediante pull requests revisados por el Team Leader. A continuación se presentan los commits realizados por repositorio durante el Sprint 2.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 37323a1 | feat: Add language files | Added i18n language files for en and es | 2026-05-12 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 6750147 | feat: add shared components and views | Added shared components and views for base layout | 2026-05-12 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | f22f516 | feat: add project structure | Set up base Angular project structure with DDD folders | 2026-05-12 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | e6fb4ff | feat: configure layout with navbar, sidebar and base routing | Configured app layout with navbar, sidebar and base routing | 2026-05-12 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | db2e432 | feat: update shared infrastructure base classes | Updated base classes for shared infrastructure layer | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | dff478c0 | feat: update shared layout components and views | Updated layout components and views for shared context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | e9b1038 | feat: add content on i18n for en and es | Added translation content for English and Spanish | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 9f8a35d | feat: add identity domain entities and models | Added domain entities and models for identity bounded context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | f54ac1c | feat: add identity store | Added Angular Signals store for identity bounded context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 4119432 | feat: add identity infrastructure | Added infrastructure layer for identity bounded context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 759d750 | feat: add presentation for profile and configuration | Added profile and configuration views for identity context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 745d089 | feat: update app routes | Updated app routing to include identity and profile routes | 2026-05-14 |
| AgroTrack-Project/web-Application | develop | a934340 | Merge pull request #1 from AgroTrack-Project/feature/EduardoVelasquez | Merged identity and shared infrastructure into develop | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 45ad493 | feat(environments): update environment paths for farming endpoints | Updated environment variables for farming API endpoints | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 819064d | feat(farming): add plot and crop status enums | Added status enums for plot and crop domain entities | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 4b26908 | feat(farming): add plot entity with domain methods | Added plot entity class with domain methods | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 6d603ca | feat(farming): add crop entity with domain methods | Added crop entity class with domain methods | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 735b050 | feat(farming): add plot and crop resource interfaces | Added resource interfaces for plot and crop | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 8629dcb | feat(farming): add plot assembler for resource mapping | Added assembler class for plot resource mapping | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 439472d | feat(farming): add crop assembler for resource mapping | Added assembler class for crop resource mapping | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 61dafb4 | feat(farming): add plot API endpoint service | Added API service for plot CRUD operations | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 05f78ce | feat(farming): add crop API endpoint service | Added API service for crop CRUD operations | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | d0ce7e7 | feat(farming): add farming API facade | Added facade service for farming bounded context | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 439e014 | feat(farming): add farming store with Angular signals | Added Angular Signals store for farming state management | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | b3f996b | feat(farming): add plots view structure and logic | Added plots list view with structure and business logic | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 70f3a8f | feat(farming): add plots view styles with summary cards | Added styles and summary cards for plots list view | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | c9899b3 | feat(farming): add plot detail view with crop tabs and form | Added plot detail view with crop management tabs | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | daf9932 | feat(farming): add plot detail view styles | Added styles for plot detail view | 2026-05-14 |
| AgroTrack-Project/web-Application | develop | 20d66d1 | Merge pull request #2 from AgroTrack-Project/feature/EderQuispe | Merged farming bounded context into develop | 2026-05-14 |
| AgroTrack-Project/web-Application | feature/EderQuispe | a8f66e7 | Implement soil monitoring and plot form screens | Implemented soil monitoring screens and plot form views | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 2d8be85 | Add soil monitoring and plot form screens | Added additional soil monitoring and plot form screens | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | ddb40a7 | Add irrigation | Added irrigation recommendation views and logic | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | aa2b335 | fix(farming): move plot ID to first position in form and detail view | Fixed plot ID position in form and detail view | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | f4edd10 | feat(farming): add harvest and edit actions to crop cards | Added harvest and edit action buttons to crop cards | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | a50b4bb | feat(farming): add harvest history section in history tab | Added harvest history section in farming history tab | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 5431ea9 | feat(farming): extend i18n to all farming module content | Extended i18n translations to all farming module content | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 7272a36 | fix(farming): fix harvest button width and add i18n label | Fixed harvest button width and added i18n label | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EderQuispe | 4c1bbd5 | fix(farming): replace harvest icon with text label Cosechar | Replaced harvest icon with text label for better UX | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/Pablo-Martinez | 98df9a9d | Finish soil monitoring BC | Completed soil monitoring bounded context implementation | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | b3e819e | Merge pull request #4 from AgroTrack-Project/feature/Pablo-Martinez | Merged farming and soil monitoring BCs into develop | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | c46fcf7 | feat: add view change | Added view change functionality for identity context | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/EduardoVelasquez | 840c738 | feat: add content on i18n for translate | Added i18n translation content for identity views | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | 4236ed3 | Merge pull request #3 from AgroTrack-Project/feature/EduardoVelasquez | Merged identity updates into develop | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | a265e4e | feat: add weather card component for displaying weather data | Added weather card component for climate data display | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 945383f | feat: add unit tests for alerts page component | Added unit tests for alerts page component | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 4a9b8cc | feat: create alerts page component with weather card integration | Created alerts page with weather card integration | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | ef10148 | feat: add alerts page route to application routing | Added alerts page route to app routing configuration | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 8c951ce | feat: add climate entity class to represent climate data | Added climate entity class for climate data representation | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 3fca1d6 | feat: add climate api endpoint class for fetching weather data by city | Added API endpoint class for fetching weather data | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | f9a2d63 | feat: add climate assembler class for transforming climate api responses into entities | Added assembler for climate API response transformation | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | cdfb56d | feat: add climate response interface for structured climate data | Added response interface for structured climate data | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 64b3dbd | feat: add climate risk analyzer class for calculating weather-related risks | Added climate risk analyzer for weather risk calculation | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 7346b40 | feat: add css styles for weather alerts display | Added CSS styles for weather alerts display | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 353943c | feat: add weather alerts display component | Added weather alerts display component | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 272fbe8 | feat(home): redesign dashboard with plots summary | Redesigned home dashboard with plots summary section | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 14cb892 | feat: add unit tests for weather card component | Added unit tests for weather card component | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 1b0b503 | feat: add alert generator for climate risk notifications | Added alert generator for climate risk notifications | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | c73e476 | feat: update environment import for alert preference API endpoint | Updated environment import for alert preference endpoint | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 20c9c90 | feat: implement AlertsStore for managing climate alerts and weather data | Implemented AlertsStore with Angular Signals | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 21f2fb3 | feat: add alerts api service for fetching weather data by city | Added API service for fetching weather data by city | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 52b7fda | feat: add alert notification entity for managing alert notifications | Added alert notification entity class | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 36b28b3 | feat: add styles for alerts page | Added CSS styles for alerts page | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/miler-rodriguez | 80d3cd3 | feat: add weather card component to alerts page | Added weather card component integration to alerts page | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | 5282603 | Merge pull request #5 from AgroTrack-Project/feature/miler-rodriguez | Merged climate alerts bounded context into develop | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/JoaquinAlfaro | e36b401 | feat: update logout method to redirect to landing page | Updated logout to redirect to landing page | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/JoaquinAlfaro | 74af4bc | feat: implement entry animation for app layout and clean up imports | Implemented entry animation and cleaned up imports | 2026-05-15 |
| AgroTrack-Project/web-Application | feature/JoaquinAlfaro | 263796b | feat: add support ticket functionality with CRUD operations | Added support ticket functionality with CRUD operations | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | c803787 | Merge pull request #6 from AgroTrack-Project/feature/EderQuispe | Merged remaining farming and soil monitoring updates into develop | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | 7af97b6 | feat: add content on alerts | Added content and translations for alerts section | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | b0aece6 | feat: add content on shared | Added content for shared bounded context | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | 2768532 | feat: add content on weather-card | Added content for weather card component | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | ef344e6 | feat: add content on presentation | Added presentation layer content | 2026-05-15 |
| AgroTrack-Project/web-Application | develop | 6365150 | feat: add some content on alerts | Added additional content for alerts section | 2026-05-15 |

#### 5.2.2.5.Execution Evidence for Sprint Review. 

Durante el Sprint 2 se implementó y desplegó la primera versión funcional del 
Frontend Web Application de AgroTrack. La aplicación cubre los bounded contexts 
de farming (gestión de parcelas y cultivos), soil monitoring (registro y seguimiento 
del estado del suelo), climate alerts (alertas climáticas basadas en datos de 
OpenWeatherMap) e identity (perfil de usuario y configuración de cuenta). A 
continuación se presentan las principales vistas implementadas durante este sprint, 
junto con el video de navegación correspondiente.

**Home Page**

![home](report/assets/home.png)

**Plots Page**

![plots](report/assets/plots.png)

**Alert Page**

![alerts](report/assets/alerts.png)

**Configuration Page**

![config](report/assets/config.png)

**Profile Page**

![profile](report/assets/profile.png)

**Configuration Profile Page**

![config-profile](report/assets/config-profile.png)


**Screenshot del video**

![video de presentación](report/assets/evidencia_sprint_review.png)

URL del video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120011_upc_edu_pe/IQAICJzo_YiLQ7CqTCNRwBTEAXCtfrOV6VxiAqzsegC73xo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=fk0ICb


#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2, el equipo no desplegó un RESTful API propio dado que el alcance
estuvo centrado en la implementación del Frontend Web Application. Para soportar el
funcionamiento de la aplicación, se configuró MockAPI como servidor provisional,
permitiendo que el frontend consuma datos estructurados mediante endpoints REST
simulados. A continuación se documentan todos los endpoints configurados en MockAPI
que el frontend consume durante este sprint.

**Figura**

![MockAPI Endpoints](report/assets/mockapi-endpoints.png)

*Panel de MockAPI con los recursos configurados para AgroTrack*

URL base: `https://6a02c43e0d92f63dd25406d7.mockapi.io/api/v1`

---

**Users**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/users` | GET | `GET /users` | Sin parámetros | Retorna la lista de todos los usuarios registrados | `{ "id": "1", "name": "Luis Quispe", "email": "luis@agrotrack.com", "planId": "2" }` |
| `/users/:id` | GET | `GET /users/{id}` | `id` (path, requerido): ID del usuario | Retorna el detalle de un usuario específico | `{ "id": "1", "name": "Luis Quispe", "planId": "2", "createdAt": "2026-01-10" }` |
| `/users` | POST | `POST /users` | Body JSON: `name`, `email`, `planId` | Registra un nuevo usuario y retorna el objeto creado | `{ "id": "5", "name": "Ana Torres", "email": "ana@mail.com", "planId": "1" }` |
| `/users/:id` | PUT | `PUT /users/{id}` | `id` (path, requerido): ID del usuario. Body JSON: campos a actualizar | Actualiza los datos de un usuario existente | `{ "id": "1", "name": "Luis Quispe", "planId": "3" }` |

**Plans**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/plans` | GET | `GET /plans` | Sin parámetros | Retorna los planes de suscripción disponibles | `{ "id": "2", "name": "Pro", "plotLimit": 10, "price": 85 }` |
| `/plans/:id` | GET | `GET /plans/{id}` | `id` (path, requerido): ID del plan | Retorna el detalle de un plan específico | `{ "id": "1", "name": "Basic", "plotLimit": 3, "price": 39 }` |

**Alert Preferences**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/alert_preferences` | GET | `GET /alert_preferences` | Sin parámetros | Retorna las preferencias de alertas configuradas | `{ "id": "1", "userId": "1", "frost": true, "drought": false, "heavyRain": true }` |
| `/alert_preferences/:id` | PUT | `PUT /alert_preferences/{id}` | `id` (path, requerido): ID de preferencia. Body JSON: campos a actualizar | Actualiza las preferencias de alertas de un usuario | `{ "id": "1", "userId": "1", "frost": false, "drought": true }` |

**Support Tickets**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/support_tickets` | GET | `GET /support_tickets` | Sin parámetros | Retorna todos los tickets de soporte registrados | `{ "id": "1", "userId": "1", "title": "Error en parcelas", "status": "open" }` |
| `/support_tickets` | POST | `POST /support_tickets` | Body JSON: `userId`, `title`, `description` | Crea un nuevo ticket de soporte | `{ "id": "7", "userId": "2", "title": "Problema con riego", "status": "open" }` |
| `/support_tickets/:id` | PUT | `PUT /support_tickets/{id}` | `id` (path, requerido). Body JSON: campos a actualizar | Actualiza un ticket de soporte existente | `{ "id": "1", "status": "closed" }` |
| `/support_tickets/:id` | DELETE | `DELETE /support_tickets/{id}` | `id` (path, requerido): ID del ticket | Elimina un ticket de soporte | `{ "id": "1", "deleted": true }` |

**Plots**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/plots` | GET | `GET /plots` | Sin parámetros | Retorna todas las parcelas registradas | `{ "id": "1", "userId": "1", "name": "Parcela Norte", "location": "Arequipa", "size": 5.0 }` |
| `/plots/:id` | GET | `GET /plots/{id}` | `id` (path, requerido): ID de la parcela | Retorna el detalle de una parcela específica | `{ "id": "1", "name": "Parcela Norte", "soilType": "arcilloso" }` |
| `/plots` | POST | `POST /plots` | Body JSON: `userId`, `name`, `location`, `size`, `soilType` | Registra una nueva parcela | `{ "id": "10", "name": "Parcela Sur", "location": "Lima", "size": 3.0 }` |
| `/plots/:id` | PUT | `PUT /plots/{id}` | `id` (path, requerido). Body JSON: campos a actualizar | Actualiza los datos de una parcela | `{ "id": "1", "name": "Parcela Norte Actualizada" }` |
| `/plots/:id` | DELETE | `DELETE /plots/{id}` | `id` (path, requerido): ID de la parcela | Elimina una parcela registrada | `{ "id": "1", "deleted": true }` |

**Crops**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/crops` | GET | `GET /crops` | Sin parámetros | Retorna todos los cultivos registrados | `{ "id": "1", "plotId": "1", "type": "Papa", "sowingDate": "2026-03-01", "status": "active" }` |
| `/crops/:id` | GET | `GET /crops/{id}` | `id` (path, requerido): ID del cultivo | Retorna el detalle de un cultivo específico | `{ "id": "1", "plotId": "1", "type": "Maíz", "status": "active" }` |
| `/crops` | POST | `POST /crops` | Body JSON: `plotId`, `type`, `sowingDate` | Registra un nuevo cultivo en una parcela | `{ "id": "9", "plotId": "2", "type": "Quinua", "sowingDate": "2026-04-10" }` |
| `/crops/:id` | PUT | `PUT /crops/{id}` | `id` (path, requerido). Body JSON: campos a actualizar | Actualiza los datos de un cultivo | `{ "id": "1", "status": "harvested", "harvestDate": "2026-05-20" }` |
| `/crops/:id` | DELETE | `DELETE /crops/{id}` | `id` (path, requerido): ID del cultivo | Elimina un cultivo registrado | `{ "id": "1", "deleted": true }` |

**Soil Records**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/soil_records` | GET | `GET /soil_records` | Sin parámetros | Retorna todos los registros de suelo | `{ "id": "1", "plotId": "1", "humidity": 65, "temperature": 18.5, "recordedAt": "2026-05-10" }` |
| `/soil_records` | POST | `POST /soil_records` | Body JSON: `plotId`, `humidity`, `temperature` | Registra nuevos datos del suelo de una parcela | `{ "id": "8", "plotId": "1", "humidity": 72, "temperature": 20.0 }` |
| `/soil_records/:id` | DELETE | `DELETE /soil_records/{id}` | `id` (path, requerido): ID del registro | Elimina un registro de suelo | `{ "id": "1", "deleted": true }` |

**Irrigation Recommendations**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/irrigation_recommendations` | GET | `GET /irrigation_recommendations` | Sin parámetros | Retorna todas las recomendaciones de riego generadas | `{ "id": "1", "plotId": "1", "recommendation": "Regar hoy", "urgency": "high", "accepted": null }` |
| `/irrigation_recommendations` | POST | `POST /irrigation_recommendations` | Body JSON: `plotId`, `recommendation`, `urgency` | Crea una nueva recomendación de riego | `{ "id": "6", "plotId": "2", "recommendation": "No regar", "urgency": "low" }` |
| `/irrigation_recommendations/:id` | PUT | `PUT /irrigation_recommendations/{id}` | `id` (path, requerido). Body JSON: `accepted` (boolean) | Registra si el agricultor aceptó o rechazó la recomendación | `{ "id": "1", "accepted": true }` |

**Irrigation Schedules**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/irrigation_schedules` | GET | `GET /irrigation_schedules` | Sin parámetros | Retorna el cronograma de riegos sugeridos | `{ "id": "1", "plotId": "1", "scheduledDate": "2026-05-20", "scheduledTime": "07:00" }` |
| `/irrigation_schedules` | POST | `POST /irrigation_schedules` | Body JSON: `plotId`, `scheduledDate`, `scheduledTime` | Registra un nuevo horario de riego sugerido | `{ "id": "5", "plotId": "3", "scheduledDate": "2026-05-22", "scheduledTime": "06:30" }` |

**Climate Alerts**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/climate_alerts` | GET | `GET /climate_alerts` | Sin parámetros | Retorna todas las alertas climáticas registradas | `{ "id": "1", "plotId": "1", "type": "FROST", "description": "Riesgo de helada", "date": "2026-05-15" }` |
| `/climate_alerts` | POST | `POST /climate_alerts` | Body JSON: `plotId`, `type`, `description` | Crea una nueva alerta climática para una parcela | `{ "id": "5", "plotId": "2", "type": "HEAVY_RAIN", "description": "Lluvias intensas previstas" }` |

**Yield Summaries**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/yield_summaries` | GET | `GET /yield_summaries` | Sin parámetros | Retorna los resúmenes de rendimiento por parcela | `{ "id": "1", "plotId": "1", "season": "2026-1", "yieldKg": 1200, "lossPercent": 8 }` |
| `/yield_summaries` | POST | `POST /yield_summaries` | Body JSON: `plotId`, `season`, `yieldKg` | Registra un nuevo resumen de rendimiento | `{ "id": "5", "plotId": "3", "season": "2026-1", "yieldKg": 900 }` |

**Loss Summaries**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/loss_summaries` | GET | `GET /loss_summaries` | Sin parámetros | Retorna los resúmenes de pérdidas por parcela | `{ "id": "1", "plotId": "1", "season": "2026-1", "lossPercent": 12, "cause": "Helada" }` |
| `/loss_summaries` | POST | `POST /loss_summaries` | Body JSON: `plotId`, `season`, `lossPercent`, `cause` | Registra un nuevo resumen de pérdidas | `{ "id": "5", "plotId": "2", "lossPercent": 5, "cause": "Sequía" }` |

**Water Consumptions**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/water_consumptions` | GET | `GET /water_consumptions` | Sin parámetros | Retorna el consumo de agua registrado por temporada | `{ "id": "1", "plotId": "1", "season": "2026-1", "liters": 45000 }` |
| `/water_consumptions` | POST | `POST /water_consumptions` | Body JSON: `plotId`, `season`, `liters` | Registra el consumo de agua de una temporada | `{ "id": "5", "plotId": "3", "season": "2026-1", "liters": 32000 }` |

---

URL del repositorio Web Application: https://github.com/AgroTrack-Project/web-Application

Commits relacionados con la configuración de endpoints en este Sprint: `45ad493`, `cc941b4`, `31ff5e4`


#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizaron las actividades necesarias para desplegar la primera versión funcional del Frontend Web Application de AgroTrack. A continuación se describeel proceso ejecutado y se presenta la evidencia correspondiente.

Como primer paso, se consolidó el código de todas las ramas feature de los integrantesdel equipo hacia la rama develop mediante pull requests revisados por el Team Leader. Una vez estabilizado el código, se configuró el entorno de despliegue en Cloudflare Workers y se publicó la aplicación de forma pública.

Se verificó el correcto funcionamiento de las vistas implementadas desde cualquier
dispositivo, comprobando que los módulos de gestión de parcelas, cultivos, monitoreo del suelo, alertas climáticas y perfil de usuario cargaran correctamente en producción.

**Repositorio Frontend Web Application:**
https://github.com/AgroTrack-Project/web-Application

**URL de la Web Application desplegada:**
https://agro-track.vitaltrek.workers.dev/home

---

<br>

**Figura**
*Evidencia de deployment 1*

![Web Application - Vista 1](report/assets/web-app-1.png)

*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 2*

![Web Application - Vista 2](report/assets/web-app-2.png)

*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 3*

![Web Application - Vista 3](report/assets/web-app-3.png)

*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 4*

![Web Application - Vista 4](report/assets/web-app-4.png)

*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 5*

![Web Application - Vista 5](report/assets/web-app-5.png)

*Nota.* Elaboración propia.


#### 5.2.2.8 Team Collaboration Insights during Sprint

Durante el Sprint 2, el equipo desarrolló las actividades de implementación del
Frontend Web Application de AgroTrack de forma colaborativa mediante el repositorio
GitHub de la organización AgroTrack-Project. Cada integrante trabajó en su rama
feature correspondiente y realizó pull requests hacia la rama develop, los cuales
fueron revisados y aprobados por el Team Leader antes de ser integrados.

A continuación se presentan los analíticos de colaboración del repositorio
web-Application durante el periodo del sprint, evidenciando la participación
de cada miembro del equipo.

![contribucion del equipo](report/assets/team-contribution-2.png)

*Nota.* Elaboración propia.

### 5.2.3. Sprint 3

El tercer sprint se centrará en el desarrollo del RESTful API (Web Services) de AgroTrack, distribuyendo la implementación de los bounded contexts entre los miembros del equipo. El objetivo es construir y desplegar la primera versión del backend bajo una arquitectura orientada a dominio (DDD), permitiendo que el Frontend Web Application consuma datos reales a través de endpoints REST documentados con OpenAPI.

#### 5.2.3.1. Sprint Planning 3

Se presenta a continuación el resumen del Sprint Planning Meeting para el Sprint 3.

| Campo | Detalle |
|-------|---------|
| **Sprint #** | Sprint 3 |
| **Sprint Planning Background** | |
| **Date** | 20/06/26 |
| **Time** | 7:00 PM |
| **Location** | Virtual – Discord (canal General) |
| **Prepared By** | Velasquez Laquihuanaco, Eduardo David |
| **Attendees (to planning meeting)** | Alfaro Mallma, Alberto Joaquin / Martínez Gaona, Pablo Afranio / Quispe Perez, Eder Edu / Rodriguez Rojas, Miler Alexander / Velasquez Laquihuanaco, Eduardo David |
| **Sprint 2 – Review Summary** | Durante el Sprint 2 se desarrolló e implementó la primera versión funcional del Frontend Web Application de AgroTrack, cubriendo los bounded contexts de identity (perfil y configuración), farming (parcelas y cultivos), soil monitoring (datos del suelo), climate alerts (alertas climáticas) y dashboard (panel de control). La aplicación fue desplegada exitosamente mediante Cloudflare Workers y consumió datos a través de MockAPI como servidor provisional. |
| **Sprint 2 – Retrospective Summary** | El equipo identificó como oportunidad de mejora la definición anticipada de los contratos de la API antes de iniciar la implementación del frontend, a fin de evitar inconsistencias entre los datos simulados (MockAPI) y los reales. En términos generales, la dinámica de trabajo fue adecuada para el alcance del Sprint. |
| **Sprint Goal & User Stories** | |
| **Sprint 3 Goal** | Nuestro enfoque está en implementar la API RESTful para AgroTrack. Creemos que ofrece una capa de backend fiable y persistente que permite al frontend interactuar con datos reales en todos los contextos limitados. Esto se confirmará cuando todos los endpoints de contexto limitado asignados estén operativos, documentados con OpenAPI a través de Swagger y consumidos con éxito por la aplicación web frontend. |
| **Sprint 3 Velocity** | 7 |
| **Sum of Story Points** | 7 |


#### 5.2.3.2. Aspect Leaders and Collaborators.

En el Sprint 3, los principales aspectos considerados corresponden a los bounded contexts implementados en el RESTful API (Web Services) de AgroTrack. Cada bounded context representa un dominio funcional independiente del backend, desarrollado por un integrante líder bajo la arquitectura Domain-Driven Design (DDD). Los aspectos del Sprint son: **Identity** (gestión de usuarios, planes y preferencias de alertas), **Farming** (gestión de parcelas y cultivos), **Soil Monitoring** (monitoreo de datos del suelo), **Alerts** (alertas climáticas) y **Support & Dashboard** (tickets de soporte y panel de control).

| Team Member (Last Name, First Name) | GitHub Username | Identity BC | Farming BC | Soil Monitoring BC | Alerts BC | Support & Dashboard BC |
|---|---|---|---|---|---|---|
| Alfaro Mallma, Alberto Joaquin | elprrr | C | C | C | C | L |
| Martínez Gaona, Pablo Afranio | de123kl | C | C | L | C | C |
| Quispe Perez, Eder Edu | DuDu-tech | C | L | C | C | C |
| Rodriguez Rojas, Miler Alexander | milerrodr | C | C | C | L | C |
| Velasquez Laquihuanaco, Eduardo David | Edu-VLL | L | C | C | C | C |



#### 5.2.3.3. Sprint Backlog 3.

El objetivo principal del Sprint 3 fue implementar el RESTful API (Web Services) de AgroTrack, distribuyendo el desarrollo de los bounded contexts entre los integrantes del equipo bajo una arquitectura Domain-Driven Design (DDD). A continuación se presenta el tablero del sprint y la descomposición de Technical Stories en Work-Items/Tasks.

**Figura**

![Sprint Backlog 3](./report/assets/trelloSprin3.png) 

*Sprint 3 de AgroTrack*

*Nota.* Elaboración propia. Obtenido de Trello 

**Link del trello:** https://trello.com/invite/b/6a386dfb1297005b1b046b88/ATTIf29aeadd54f0dac60d77b9b1cc2cf2ce5B4F6107/agrotrack-sprint-3

| User Story Id | User Story | Work-Item / Task Id | Work-Item / Task Title | Work-Item / Task Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---|---|---|---|
| TS01 | Endpoint para registrar un usuario | T-001 | Implementar capa de dominio del BC Identity | Crear los agregados User, Plan y AlertPreference con sus value objects (UserType, PlanType), comandos (CreateUserCommand, UpdateUserCommand, UpdateAlertPreferenceCommand) y queries (GetUserByIdQuery, ListPlansQuery, ListAlertPreferencesQuery). | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-002 | Implementar capa de aplicación del BC Identity | Implementar UserCommandServiceImpl (con auto-creación de AlertPreference al registrar usuario), AlertPreferenceCommandServiceImpl, PlanQueryServiceImpl y AlertPreferenceQueryServiceImpl con la lógica de negocio correspondiente. | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-003 | Implementar capa de infraestructura del BC Identity | Crear entidades de persistencia (UserPersistenceEntity, PlanPersistenceEntity, AlertPreferencePersistenceEntity), repositorios JPA, assemblers de conversión y adaptadores de repositorio. | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-004 | Implementar endpoint POST /users | Crear UsersController con endpoint POST /users que retorna 201 al crear el usuario y genera automáticamente su AlertPreference. Incluir validaciones de campos obligatorios y manejo de correo duplicado (409). | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS02 | Endpoint para obtener un usuario por ID | T-005 | Implementar endpoint GET /users/{id} | Agregar endpoint GET /users/{id} en UsersController que retorna 200 con los datos del usuario o 404 si el ID no existe. | 1 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS03 | Endpoint para actualizar un usuario | T-006 | Implementar endpoint PUT /users/{id} | Agregar endpoint PUT /users/{id} en UsersController que actualiza nombre, email, password, planType y companyName, renovando el campo updated_at. Retorna 200 o 404. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS04 | Endpoint para listar planes de suscripción | T-007 | Implementar PlansController con endpoint GET /plans | Crear PlansController con endpoint GET /plans que retorna el array de los 3 planes disponibles (BASIC, PRO, ENTERPRISE) con sus características. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-008 | Implementar IdentityDataSeeder para poblar planes | Crear seeder ApplicationRunner que inicializa los planes BASIC, PRO y ENTERPRISE con sus características al arrancar la aplicación, si no existen aún. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS05 | Endpoint para obtener preferencias de alertas | T-009 | Implementar AlertPreferencesController con endpoint GET /alert_preferences | Crear endpoint GET /alert_preferences con parámetro opcional ?user_id para filtrar por usuario o retornar todas las preferencias registradas. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS06 | Endpoint para actualizar preferencias de alertas | T-010 | Implementar endpoint PUT /alert_preferences/{id} | Agregar endpoint PUT /alert_preferences/{id} que actualiza los toggles frostEnabled, droughtEnabled y heavyRainEnabled. Retorna 200 o 404. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS07 | Endpoint para registrar una lectura de suelo | T-011 | Implementar capa de dominio del BC Soil Monitoring | Crear los agregados SoilRecord e IrrigationRecommendation con sus value objects (Humidity, Temperature, PlotId, SoilRecordId, IrrigationUrgency, IrrigationRecommendationStatus), comandos y queries correspondientes. | 4 | Martínez Gaona, Pablo Afranio | Done |
| | | T-012 | Implementar capa de aplicación del BC Soil Monitoring | Implementar SoilRecordCommandServiceImpl, SoilRecordQueryServiceImpl, IrrigationRecommendationCommandServiceImpl e IrrigationRecommendationQueryServiceImpl con la lógica de negocio y validaciones. | 4 | Martínez Gaona, Pablo Afranio | Done |
| | | T-013 | Implementar capa de infraestructura del BC Soil Monitoring | Crear entidades de persistencia (SoilRecordPersistenceEntity, IrrigationRecommendationPersistenceEntity), repositorios JPA, assemblers de conversión y StubPlotReferenceAdapter. | 4 | Martínez Gaona, Pablo Afranio | Done |
| | | T-014 | Implementar endpoint POST /soil_records | Crear SoilRecordsController con endpoint POST /soil_records que valida humedad (0–100) y temperatura, y retorna 201 con la lectura creada o 400 si los datos son inválidos. | 2 | Martínez Gaona, Pablo Afranio | Done |
| TS08 | Endpoint para listar lecturas de suelo | T-015 | Implementar endpoint GET /soil_records | Agregar endpoint GET /soil_records con filtro opcional por plot_id que retorna 200 con la lista de lecturas ordenadas por fecha descendente. | 2 | Martínez Gaona, Pablo Afranio | Done |
| TS09 | Endpoint para eliminar una lectura de suelo | T-016 | Implementar endpoint DELETE /soil_records/{id} | Agregar endpoint DELETE /soil_records/{id} que elimina la lectura de suelo indicada. Retorna 200 o 404 si el ID no existe. | 1 | Martínez Gaona, Pablo Afranio | Done |
| TS10 | Endpoint para registrar una recomendación de riego | T-017 | Implementar endpoint POST /irrigation_recommendations | Crear IrrigationRecommendationsController con endpoint POST /irrigation_recommendations que valida plot_id, soil_record_id existente, urgency (LOW/MEDIUM/HIGH) y status (PENDING/CONFIRMED/REJECTED). Retorna 201 o 400. | 3 | Martínez Gaona, Pablo Afranio | Done |
| TS11 | Endpoint para listar recomendaciones de riego | T-018 | Implementar endpoint GET /irrigation_recommendations | Agregar endpoint GET /irrigation_recommendations con filtro opcional por plot_id que retorna 200 con la lista de recomendaciones. | 2 | Martínez Gaona, Pablo Afranio | Done |
| TS12 | Endpoint para actualizar una recomendación de riego | T-019 | Implementar endpoint PUT /irrigation_recommendations/{id} | Agregar endpoint PUT /irrigation_recommendations/{id} que actualiza el estado (CONFIRMED/REJECTED) y el campo responded_at. Retorna 200 o 404. | 2 | Martínez Gaona, Pablo Afranio | Done |
| TS13 | Endpoint para eliminar una recomendación de riego | T-020 | Implementar endpoint DELETE /irrigation_recommendations/{id} | Agregar endpoint DELETE /irrigation_recommendations/{id} que elimina la recomendación. Retorna 200 o 404 si el ID no existe. | 1 | Martínez Gaona, Pablo Afranio | Done |
| TS14 | Endpoint para listar parcelas | T-021 | Implementar capa de dominio del BC Farming – Plots | Crear el agregado Plot con su value object PlotStatus y comandos (CreatePlotCommand, UpdatePlotCommand, DeactivatePlotCommand) y queries (GetPlotByIdQuery, ListPlotsQuery). | 3 | Quispe Perez, Eder Edu | Done |
| | | T-022 | Implementar capa de aplicación del BC Farming – Plots | Implementar PlotCommandServiceImpl con lógica de creación, actualización y desactivación de parcelas, y PlotQueryServiceImpl para listado con filtro opcional por userId. | 3 | Quispe Perez, Eder Edu | Done |
| | | T-023 | Implementar capa de infraestructura del BC Farming – Plots | Crear PlotPersistenceEntity, PlotPersistenceRepository JPA, PlotRepositoryImpl y PlotPersistenceAssembler para la persistencia de parcelas. | 3 | Quispe Perez, Eder Edu | Done |
| | | T-024 | Implementar endpoint GET /plots | Crear PlotsController con endpoint GET /plots que retorna la lista de parcelas con filtro opcional por userId. Retorna 200. | 2 | Quispe Perez, Eder Edu | Done |
| TS15 | Endpoint para registrar una parcela | T-025 | Implementar endpoint POST /plots | Agregar endpoint POST /plots en PlotsController que crea una parcela nueva con estado ACTIVE. Retorna 201 o 400 si faltan campos obligatorios. | 2 | Quispe Perez, Eder Edu | Done |
| TS16 | Endpoint para actualizar una parcela | T-026 | Implementar endpoint PUT /plots/{id} | Agregar endpoint PUT /plots/{id} que actualiza nombre, ubicación y tamaño de la parcela. Retorna 200 o 404 si el ID no existe. | 2 | Quispe Perez, Eder Edu | Done |
| TS17 | Endpoint para desactivar una parcela | T-027 | Implementar endpoint DELETE /plots/{id} | Agregar endpoint DELETE /plots/{id} que cambia el estado de la parcela a DELETED (soft delete). Retorna 204 o 404 si el ID no existe. | 1 | Quispe Perez, Eder Edu | Done |
| TS18 | Endpoint para listar cultivos | T-028 | Implementar capa de dominio del BC Farming – Crops | Crear el agregado Crop con su value object CropStatus y comandos (CreateCropCommand, UpdateCropCommand, DeleteCropCommand) y queries (GetCropByIdQuery, ListCropsQuery). | 3 | Quispe Perez, Eder Edu | Done |
| | | T-029 | Implementar capas de aplicación e infraestructura del BC Farming – Crops | Implementar CropCommandServiceImpl, CropQueryServiceImpl, CropPersistenceEntity, CropPersistenceRepository JPA, CropRepositoryImpl y CropPersistenceAssembler. | 4 | Quispe Perez, Eder Edu | Done |
| | | T-030 | Implementar endpoint GET /crops | Crear CropsController con endpoint GET /crops que retorna la lista de cultivos con filtro opcional por plotId. Retorna 200. | 2 | Quispe Perez, Eder Edu | Done |
| TS19 | Endpoint para registrar un cultivo | T-031 | Implementar endpoint POST /crops | Agregar endpoint POST /crops en CropsController que registra un cultivo en una parcela con estado ACTIVE. Retorna 201 o 400 si faltan campos. | 2 | Quispe Perez, Eder Edu | Done |
| TS20 | Endpoint para actualizar un cultivo | T-032 | Implementar endpoint PUT /crops/{id} | Agregar endpoint PUT /crops/{id} que actualiza el tipo, estado o fechas del cultivo registrado. Retorna 200 o 404 si el ID no existe. | 2 | Quispe Perez, Eder Edu | Done |
| TS21 | Endpoint para eliminar un cultivo | T-033 | Implementar endpoint DELETE /crops/{id} | Agregar endpoint DELETE /crops/{id} que elimina el cultivo de la base de datos. Retorna 204 o 404 si el ID no existe. | 1 | Quispe Perez, Eder Edu | Done |
| TS22 | Endpoint para obtener alertas climáticas por ciudad | T-034 | Implementar endpoint GET /alerts | Crear AlertsController con endpoint GET /alerts?city={city} que consulta OpenWeather y retorna alertas climáticas generadas. Retorna 200, 400 si falta city, o 404 si la ciudad no existe. | 3 | Rodriguez Rojas, Miler Alexander | Done |
| TS23 | Endpoint para listar resúmenes de rendimiento | T-035 | Implementar endpoint GET /yield_summaries | Crear YieldSummariesController con endpoint GET /yield_summaries con filtro opcional por user_id. Retorna 200 y array de resúmenes o vacío si no hay registros. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| TS24 | Endpoint para obtener resumen de rendimiento por ID | T-036 | Implementar endpoint GET /yield_summaries/{id} | Agregar endpoint GET /yield_summaries/{id} que retorna el resumen con plot_id, yield_per_hectare, season y calculated_at. Retorna 200 o 404 si no existe. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS25 | Endpoint para listar resúmenes de pérdidas | T-037 | Implementar endpoint GET /loss_summaries | Crear LossSummariesController con endpoint GET /loss_summaries con filtro opcional por user_id. Retorna 200 y array de resúmenes de pérdidas o vacío si no hay registros. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| TS26 | Endpoint para obtener resumen de pérdidas por ID | T-038 | Implementar endpoint GET /loss_summaries/{id} | Agregar endpoint GET /loss_summaries/{id} que retorna el resumen con loss_percentage, cause, season y calculated_at. Retorna 200 o 404 si no existe. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS27 | Endpoint para listar consumos de agua | T-039 | Implementar endpoint GET /water_consumptions | Crear WaterConsumptionsController con endpoint GET /water_consumptions con filtro opcional por user_id. Retorna 200 y array de consumos o vacío si no hay registros. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| TS28 | Endpoint para obtener consumo de agua por ID | T-040 | Implementar endpoint GET /water_consumptions/{id} | Agregar endpoint GET /water_consumptions/{id} que retorna el consumo con plot_id, total_liters, season y calculated_at. Retorna 200 o 404 si no existe. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS29 | Endpoint para listar tickets de soporte | T-041 | Implementar endpoint GET /support_tickets | Crear SupportTicketsController con endpoint GET /support_tickets con filtro opcional por user_id. Retorna 200 y array de tickets con subject, message, status, created_at y responded_at. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS30 | Endpoint para obtener ticket de soporte por ID | T-042 | Implementar endpoint GET /support_tickets/{id} | Agregar endpoint GET /support_tickets/{id} que retorna el ticket completo. Retorna 200 o 404 si no existe. | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS31 | Endpoint para crear un ticket de soporte | T-043 | Implementar endpoint POST /support_tickets | Agregar endpoint POST /support_tickets con body { user_id, subject, message } que crea el ticket con status OPEN. Retorna 201 o 400 si faltan campos requeridos. | 3 | Alfaro Mallma, Alberto Joaquin | Done |


---

#### 5.2.3.4. Development Evidence for Sprint Review.

En el Sprint 3, el equipo de Andes Smart implementó los Web Services del sistema AgroTrack como una RESTful API desarrollada con Spring Boot y Java 26, aplicando una arquitectura Domain-Driven Design (DDD) en cuatro capas: domain, application, infrastructure e interfaces. Se implementaron cinco Bounded Contexts: Identity, Soil Monitoring, Farming, Alerts, Support y Dashboard. El trabajo se organizó mediante GitFlow, con feature branches individuales por integrante y Pull Requests hacia la rama `develop`. A continuación se presentan los commits más relevantes del repositorio de Web Services.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on |
|---|---|---|---|---|---|
| AgroTrack-Project/web-services | develop | 40067 | `feat: add initial Spring Boot project structure for Agrotrack backend` | Estructura base del proyecto Spring Boot con paquetes DDD, dependencias Maven y configuración inicial | 2026-05-20 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | be94e | `chore(config): set context-path, naming strategy, integration profiles and H2 for tests` | Configuración del context-path /api/v1, estrategia de naming snake_case pluralizado, perfiles dev/test y H2 para pruebas | 2026-05-21 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 9adca | `feat(support): implement domain layer with value objects, commands, queries, aggregate and domain events` | Aggregate SupportTicket con value objects TicketStatus, commands CreateTicket y CloseTicket, domain events y queries | 2026-05-22 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 16b5f | `feat(support): implement application layer with command/query services and ports` | Servicios de aplicación SupportCommandService y SupportQueryService con puertos de repositorio | 2026-05-23 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 1f8a4 | `feat(support): implement infrastructure layer with persistence entities, repositories, assemblers and data seeder` | Entidades JPA, repositorios Spring Data, assemblers de persistencia y DataSeeder con datos de muestra | 2026-05-24 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 30594 | `feat(support): implement REST interface layer with resources, assemblers and controller` | SupportTicketsController con endpoints GET /support_tickets, GET /{id} y POST, recursos REST y assemblers | 2026-05-24 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 994f0 | `feat(dashboard): implement domain layer with value objects, aggregates and queries for yield, loss and water summaries` | Domain model del BC Dashboard con aggregates YieldSummary, LossSummary y WaterConsumption y sus queries | 2026-05-26 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 67178 | `feat(dashboard): implement application layer with query services, ports and MockAPI farming integration` | Query services del dashboard con integración al BC Farming mediante PlotOwnershipQueryPort | 2026-05-27 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | e613a | `feat(dashboard): implement infrastructure layer with persistence entities, repositories, assemblers and data seeder` | Capa de persistencia JPA para los tres recursos del dashboard con DataSeeder para datos de demostración | 2026-05-28 |
| AgroTrack-Project/web-services | feature/JoaquinAlfaro | 46585 | `feat(dashboard): implement REST interface layer with resources, assemblers and controllers` | Tres controladores REST para YieldSummaries, LossSummaries y WaterConsumptions con endpoints GET | 2026-05-29 |
| AgroTrack-Project/web-services | develop | 8f78f | `Merge pull request #1 from AgroTrack-Project/feature/JoaquinAlfaro` | Integración del BC Support & Dashboard a la rama develop mediante Pull Request #1 | 2026-06-01 |
| AgroTrack-Project/web-services | feature/eduardo-velasquez | 14c72 | `feat: add identity bounded context REST API` | Implementación completa del BC Identity con Users, Plans y AlertPreferences en las cuatro capas DDD | 2026-06-02 |
| AgroTrack-Project/web-services | develop | 51a2f | `Merge pull request #2 from AgroTrack-Project/feature/eduardo-velasquez` | Integración del BC Identity a la rama develop mediante Pull Request #2 | 2026-06-04 |
| AgroTrack-Project/web-services | feature/Pablo-Martinez | 2d6f2 | `Implement soil monitoring BC` | Implementación del BC Soil Monitoring con SoilRecords e IrrigationRecommendations en las cuatro capas DDD | 2026-06-05 |
| AgroTrack-Project/web-services | develop | 8b1b2 | `Merge pull request #3 from AgroTrack-Project/feature/Pablo-Martinez` | Integración inicial del BC Soil Monitoring a la rama develop mediante Pull Request #3 | 2026-06-06 |
| AgroTrack-Project/web-services | feature/Pablo-Martinez | 5cfa9 | `refactor: move soil monitoring enums to value objects` | Refactorización de SoilStatus e IrrigationStatus hacia el paquete value objects del dominio | 2026-06-07 |
| AgroTrack-Project/web-services | develop | 77b71 | `Merge pull request #4 from AgroTrack-Project/feature/Pablo-Martinez` | Integración de la refactorización del BC Soil Monitoring a la rama develop mediante Pull Request #4 | 2026-06-08 |
| AgroTrack-Project/web-services | feature/eder-quispe | f0b51 | `feat(farming): add PlotStatus and CropStatus value objects` | Value objects PlotStatus (ACTIVE, INACTIVE, DELETED) y CropStatus (GROWING, HARVESTED) para el dominio de Farming | 2026-06-09 |
| AgroTrack-Project/web-services | feature/eder-quispe | 05756 | `feat(farming): add Plot aggregate with create, update and deactivate behavior` | Aggregate Plot con comportamientos de creación, actualización y desactivación, junto con sus comandos de dominio | 2026-06-09 |
| AgroTrack-Project/web-services | feature/eder-quispe | a1a65 | `feat(farming): add Crop aggregate with create, update and markAsHarvested behavior` | Aggregate Crop con comportamientos de creación, actualización y marcado como cosechado | 2026-06-09 |
| AgroTrack-Project/web-services | feature/eder-quispe | 68234 | `feat(farming): add Plot and Crop repository ports` | Puertos de repositorio PlotRepository y CropRepository para desacoplar dominio de infraestructura | 2026-06-10 |
| AgroTrack-Project/web-services | feature/eder-quispe | cff93 | `feat(farming): add Plot and Crop JPA persistence entities and repositories` | Entidades JPA PlotEntity y CropEntity con sus repositorios Spring Data JPA | 2026-06-10 |
| AgroTrack-Project/web-services | feature/eder-quispe | fceb5 | `feat(farming): add Plot and Crop persistence assemblers and repository adapters` | Assemblers de persistencia y adapters de repositorio que implementan los puertos del dominio | 2026-06-11 |
| AgroTrack-Project/web-services | feature/eder-quispe | 55445 | `feat(farming): add Plot and Crop command and query services` | Servicios de aplicación PlotCommandService, PlotQueryService, CropCommandService y CropQueryService | 2026-06-11 |
| AgroTrack-Project/web-services | feature/eder-quispe | 89eec | `feat(farming): add Plot and Crop REST controllers` | PlotsController y CropsController con endpoints CRUD completos y transformación mediante assemblers REST | 2026-06-12 |
| AgroTrack-Project/web-services | feature/eder-quispe | aaf99 | `fix(farming): migrate Plot and Crop IDs from Long to UUID string` | Migración de IDs numéricos Long a UUID string en aggregates para compatibilidad con frontend Angular | 2026-06-13 |
| AgroTrack-Project/web-services | feature/eder-quispe | 5b995 | `fix(farming): update Plot and Crop persistence layer to use UUID string IDs` | Actualización de entidades JPA para almacenar UUID como VARCHAR en la base de datos MySQL | 2026-06-14 |
| AgroTrack-Project/web-services | feature/eder-quispe | 79f31 | `fix(farming): replace soft delete with hard delete on DELETE /plots/{id}` | Cambio de eliminación lógica a eliminación física en el endpoint DELETE /plots/{id} requerido por el frontend | 2026-06-15 |
| AgroTrack-Project/web-services | feature/eder-quispe | 3b9f5 | `refactor(farming): remove getById and harvest endpoints not used by frontend` | Eliminación de endpoints GET /plots/{id}, GET /crops/{id} y PATCH /crops/{id}/harvest no consumidos por el frontend | 2026-06-16 |
| AgroTrack-Project/web-services | feature/Pablo-Martinez | df18e | `refactor: remove unused get-by-id endpoints in soil-monitoring BC` | Eliminación de endpoints GET /{id} en soil monitoring no utilizados por el frontend para mantener la API limpia | 2026-06-16 |
| AgroTrack-Project/web-services | develop | 56471 | `Merge pull request #5 from AgroTrack-Project/feature/Pablo-Martinez` | Integración de la refactorización final del BC Soil Monitoring a la rama develop mediante Pull Request #5 | 2026-06-16 |
| AgroTrack-Project/web-services | develop | 46bb2 | `Merge pull request #6 from AgroTrack-Project/feature/eder-quispe` | Integración completa del BC Farming a la rama develop mediante Pull Request #6 | 2026-06-17 |
| AgroTrack-Project/web-services | develop | 4d8b6 | `feat: Add BC Alerts` | Implementación del BC Alerts con integración a OpenWeather API para consulta de condiciones climáticas por ciudad y generación de alertas | 2026-06-20 |



#### 5.2.3.5. Execution Evidence for Sprint Review. 

Durante el Sprint 3, el equipo de Andes Smart completó la implementación de los Web Services del sistema AgroTrack. Se desarrollaron cinco Bounded Contexts (Identity, Soil Monitoring, Farming, Alerts y Support & Dashboard) como una RESTful API desplegada en Render, documentada mediante OpenAPI/Swagger y consumida exitosamente por la Web Application. A continuación se presentan las capturas de las principales vistas del funcionamiento del sistema.

**Swagger UI - Documentación de endpoints desplegados**

![swagger 1](report/assets/swagger1.png) 
![swagger 2](report/assets/swagger2.png) 
![swagger 3](report/assets/swagger3.png) 
![swagger 4](report/assets/swagger4.png)  

**Video de demostración**

A continuación se presenta el video de demostración del Sprint 3, donde se muestra el funcionamiento de los Web Services d
ocumentados en Swagger y los endpoints implementados por el equipo.

![swagger 2](report/assets/swagger2.png) 

**Link del video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202323350_upc_edu_pe/IQANSlaoHDAvRrqH_iFNWhu7AaJ-uZhcqpvZBazMZA5JOiE?e=HwAWli&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


<br>
#### 5.2.3.4 Development Evidence for Sprint Review.

En este Sprint, el equipo avanzó en la implementación de los principales productos de la solución: Web Application, Web Services y la documentación del Report, cubriendo las funcionalidades priorizadas en el Sprint Backlog. A continuación se detallan los commits realizados por cada integrante en los repositorios correspondientes, evidenciando la colaboración del equipo durante el ciclo de desarrollo.

**Web Application**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-application | | | | | |
| AgroTrack-Project/web-application | | | | | |
| AgroTrack-Project/web-application | | | | | |

**Web Services**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-services | | | | | |
| AgroTrack-Project/web-services | | | | | |
| AgroTrack-Project/web-services | | | | | |

**Report**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/report | | | | | |
| AgroTrack-Project/report | | | | | |
| AgroTrack-Project/report | | | | | |

**Commits por integrante:**

| Integrante | GitHub Username |
|---|---|
| Alberto Joaquin Alfaro Mallma | elprrr |
| Eder Edu Quispe Perez | DuDu-0912 |
| Miler Alexander Rodriguez Rojas | Miler2003 |
| Eduardo David Velasquez Laquihuanaco | Edu-VLL | |

#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

Durante el Sprint 3, el equipo documentó los Web Services de AgroTrack mediante **OpenAPI  / Swagger UI**. La documentación se generó automáticamente a partir de las anotaciones de los controladores REST.

A continuación se presenta la tabla con todos los endpoints documentados, junto con la sintaxis de llamada, parámetros, descripción de operación y códigos de respuesta:

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Response |
|:---|:---:|:---|:---|:---|:---:|
| Users | GET | `GET /api/v1/users/{id}` | `id` (path, UUID): identificador del usuario | Obtiene un usuario por su ID único | 200, 404 |
| Users | POST | `POST /api/v1/users` | Body: `name`, `email`, `password`, `user_type`, `plan_type`, `company_name`(opcional) | Registra un nuevo usuario en el sistema | 201, 409 |
| Users | PUT | `PUT /api/v1/users/{id}` | `id` (path, UUID); Body: campos actualizables del usuario | Actualiza los datos de un usuario existente | 200, 404 |
| Plans | GET | `GET /api/v1/plans` | — | Retorna el catálogo completo de planes disponibles (BASIC, PRO, ENTERPRISE) | 200 |
| Alert Preferences | GET | `GET /api/v1/alert_preferences` | `user_id` (query, opcional): filtra por usuario | Lista las preferencias de alertas climáticas; sin parámetro retorna todas | 200 |
| Alert Preferences | PUT | `PUT /api/v1/alert_preferences/{id}` | `id` (path, UUID); Body: `frost_enabled`, `drought_enabled`, `heavy_rain_enabled` | Actualiza las preferencias de alertas de un usuario | 200, 404 |
| Plots | GET | `GET /api/v1/plots` | `userId` (query, opcional): filtra parcelas por propietario | Lista todas las parcelas; con `userId` retorna solo las del usuario indicado | 200 |
| Plots | POST | `POST /api/v1/plots` | Body: `name`, `location`, `size_hectares`, `status`, `user_id` | Crea una nueva parcela asociada a un usuario | 201, 400 |
| Plots | PUT | `PUT /api/v1/plots/{id}` | `id` (path, UUID); Body: campos actualizables de la parcela | Actualiza los datos de una parcela existente | 200, 404 |
| Plots | DELETE | `DELETE /api/v1/plots/{id}` | `id` (path, UUID) | Elimina permanentemente una parcela y sus datos asociados | 204 |
| Crops | GET | `GET /api/v1/crops` | `plotId` (query, opcional): filtra cultivos por parcela | Lista todos los cultivos; con `plotId` retorna solo los de esa parcela | 200 |
| Crops | POST | `POST /api/v1/crops` | Body: `type`, `sowing_date`, `harvest_date`, `status`, `plot_id` | Registra un nuevo cultivo en una parcela | 201, 400 |
| Crops | PUT | `PUT /api/v1/crops/{id}` | `id` (path, UUID); Body: campos actualizables del cultivo | Actualiza los datos de un cultivo existente | 200, 404 |
| Crops | DELETE | `DELETE /api/v1/crops/{id}` | `id` (path, UUID) | Elimina permanentemente un cultivo | 204 |
| Soil Records | GET | `GET /api/v1/soil_records` | `plot_id` (query, opcional): filtra registros por parcela | Lista registros del sensor de suelo; con `plot_id` filtra por parcela | 200 |
| Soil Records | POST | `POST /api/v1/soil_records` | Body: `plot_id`, `humidity`, `temperature`, `recorded_at` | Registra una nueva lectura de humedad y temperatura del suelo | 201, 400 |
| Soil Records | DELETE | `DELETE /api/v1/soil_records/{id}` | `id` (path, UUID) | Elimina un registro de suelo; retorna mensaje de confirmación | 200 |
| Irrigation Recommendations | GET | `GET /api/v1/irrigation_recommendations` | `plot_id` (query, opcional): filtra por parcela | Lista recomendaciones de riego; con `plot_id` filtra por parcela | 200 |
| Irrigation Recommendations | POST | `POST /api/v1/irrigation_recommendations` | Body: `plot_id`, `soil_record_id`, `message`, `urgency`, `status` | Crea una nueva recomendación de riego generada por el sistema | 201, 400 |
| Irrigation Recommendations | PUT | `PUT /api/v1/irrigation_recommendations/{id}` | `id` (path, UUID); Body: `status`, `responded_at` | Actualiza el estado de una recomendación (aceptada/rechazada) | 200, 404 |
| Irrigation Recommendations | DELETE | `DELETE /api/v1/irrigation_recommendations/{id}` | `id` (path, UUID) | Elimina una recomendación de riego; retorna mensaje de confirmación | 200 |
| Support Tickets | GET | `GET /api/v1/support_tickets` | `user_id` (query, opcional): filtra tickets por usuario | Lista tickets de soporte; con `user_id` retorna solo los del usuario | 200 |
| Support Tickets | GET | `GET /api/v1/support_tickets/{id}` | `id` (path, UUID) | Obtiene el detalle de un ticket de soporte específico | 200, 404 |
| Support Tickets | POST | `POST /api/v1/support_tickets` | Body: `user_id`, `subject`, `message` | Crea un nuevo ticket de soporte enviado por el usuario | 201, 400 |
| Support Tickets | PUT | `PUT /api/v1/support_tickets/{id}` | `id` (path, UUID); Body: `status` | Cierra o actualiza el estado de un ticket de soporte | 200 |
| Alerts | GET | `GET /api/v1/alerts` | `city` (query, **requerido**): nombre de la ciudad | Consulta alertas climáticas activas para la ciudad indicada vía OpenWeather API | 200, 400, 404 |
| Yield Summaries | GET | `GET /api/v1/yield_summaries` | `user_id` (query, opcional): filtra por usuario | Lista resúmenes de rendimiento por hectárea; con `user_id` filtra por propietario | 200 |
| Yield Summaries | GET | `GET /api/v1/yield_summaries/{id}` | `id` (path, UUID) | Obtiene el detalle de un resumen de rendimiento específico | 200, 404 |
| Loss Summaries | GET | `GET /api/v1/loss_summaries` | `user_id` (query, opcional): filtra por usuario | Lista resúmenes de pérdidas agrícolas; con `user_id` filtra por propietario | 200 |
| Loss Summaries | GET | `GET /api/v1/loss_summaries/{id}` | `id` (path, UUID) | Obtiene el detalle de un resumen de pérdidas específico | 200, 404 |
| Water Consumptions | GET | `GET /api/v1/water_consumptions` | `user_id` (query, opcional): filtra por usuario | Lista registros de consumo de agua por temporada; con `user_id` filtra por propietario | 200 |
| Water Consumptions | GET | `GET /api/v1/water_consumptions/{id}` | `id` (path, UUID) | Obtiene el detalle de un registro de consumo de agua específico | 200, 404 |

### Documentación en Swagger UI

Se incluyen a continuación capturas de la documentación interactiva accesible en Swagger:


**Captura 1: Ejecución interactiva de un endpoint de prueba**

![Swagger UI - Endpoint POST](./report/assets/postUsers.png) 


**Captura 2: Detalle de un endpoint con ejemplo de GET /users/{id}**

![Swagger UI - Endpoint GET](./report/assets/getUsers.png) 

 

### Referencias de Implementación

**Repositorio de Web Services:** https://github.com/AgroTrack-Project/web-services

**URL de la Documentación Swagger:** https://agotrack.onrender.com/api/v1/swagger-ui/index.html#/

---

<br> 

#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Durante el Sprint 3, el equipo realizó el despliegue del **Web Service de AgroTrack** en entorno de producción. Se utilizaron dos plataformas en la nube: **Aiven** para alojar la base de datos MySQL y **Render** para el backend.  
 

---

<br>

**Fase 1: Configuración de la base de datos en Aiven (MySQL)**

Acceso a la plataforma Aiven (aiven.io), proveedor de infraestructura de datos en la nube seleccionado por el equipo para gestionar la base de datos MySQL del backend.

![BACKEND-1: Página principal de Aiven](report/assets/BACKEND-1.png)

<br>

Dashboard de servicios de Aiven. Se verificó que el servicio MySQL `mysql-58d1d5c` se encontraba activo (status: Running) en DigitalOcean, región California, bajo el plan Free-1-1gb (1 CPU / 1 GB RAM / 1 GB storage).

![BACKEND-2: Servicio MySQL activo en el dashboard de Aiven](report/assets/BACKEND-2.png)

<br>

Vista de la sección Services de Aiven con la opción de crear un nuevo servicio disponible.

![BACKEND-3: Sección Services de Aiven con botón Create service](report/assets/BACKEND-3.png)

<br>


Selección del tipo de servicio a crear. Se eligió **MySQL** como motor de base de datos relacional para el backend de AgroTrack.

![BACKEND-4: Selección del tipo de servicio MySQL en Aiven](report/assets/BACKEND-4.png)

<br>


Configuración del plan de servicio. Se seleccionó el tier **Free** ($0/mes), región **North America**, plan **Free-1-1gb** (1 VM, 1 CPU, 1 GB RAM, 1 GB storage).

![BACKEND-5: Configuración del plan Free en Aiven](report/assets/BACKEND-5.png)

<br>


Servicio MySQL desplegado y activo. Se obtuvo la información de conexión: host `mysql-58d1d5c-joaquinaso5612-e97f.a.aivencloud.com`, puerto `27774`, usuario `avnadmin`, SSL mode: `REQUIRED`. Estas credenciales se configuraron como variables de entorno en el backend.

![BACKEND-6: Información de conexión del servicio MySQL en Aiven](report/assets/BACKEND-6.png)

---

<br>


<br>


**Fase 2: Despliegue del API REST en Render**

Acceso a la plataforma Render (render.com), seleccionada como plataforma de hosting para el backend Spring Boot por su integración con GitHub y soporte para contenedores Docker.

![BACKEND-7: Página principal de Render](report/assets/BACKEND-7.png)

<br>


Dashboard de Render mostrando el servicio **AGOTRACK** desplegado correctamente (status: Deployed, runtime: Docker, región: Ohio).

![BACKEND-8: Servicio AGOTRACK desplegado en el dashboard de Render](report/assets/BACKEND-8.png)

<br>


Vista general de proyectos en Render. El proyecto "My project" muestra el estado "All services are up and running", confirmando que todos los servicios están operativos.

![BACKEND-9: Vista general de proyectos en Render con servicios activos](report/assets/BACKEND-9.png)

<br>


Creación de un nuevo Web Service desde el menú "+ New" de Render, seleccionando la opción **Web Service**.

![BACKEND-10: Menú de creación de nuevo Web Service en Render](report/assets/BACKEND-10.png)

<br>


Selección del repositorio de código fuente mediante el Git Provider de Render. Se vinculó el repositorio **BACKEND-AGROTRACK** de la organización en GitHub.

![BACKEND-11: Selección del repositorio BACKEND-AGROTRACK en Render](report/assets/BACKEND-11.png)

<br>


Configuración del Web Service: nombre del servicio, lenguaje/runtime, branch de despliegue (`main`) y región de hosting (**Ohio, US East**).

![BACKEND-12: Configuración del Web Service en Render](report/assets/BACKEND-12.png)

<br>


Selección del plan de instancia. Se eligió el plan **Free** (512 MB RAM, 0.1 CPU, $0/mes) para el entorno de demostración del proyecto.

![BACKEND-13: Selección del plan Free en Render](report/assets/BACKEND-13.png)

<br>


Configuración de las variables de entorno del servicio. Se registraron las variables `DB_URL`, `DB_USERNAME`, `DB_PASSWORD` (con las credenciales de Aiven) y `OPENWEATHER_API_KEY` (para el bounded context Alerts). Finalmente se ejecutó el despliegue con el botón **Deploy Web Service**.

![BACKEND-14: Configuración de variables de entorno y despliegue en Render](report/assets/BACKEND-14.png)

<br>


Servicio desplegado y en estado **Live** en Render. El backend quedó disponible públicamente y con auto-deploy habilitado desde el branch `main`.

![BACKEND-15: Servicio backend Live en Render](report/assets/BACKEND-15.png)

<br>
 

#### 5.2.3.8. Team Collaboration Insights during Sprint.

Durante el Sprint 3, el equipo concentró sus actividades de implementación en el desarrollo de los Web Services de AgroTrack. El trabajo se distribuyó entre los diferentes Bounded Contexts del sistema, permitiendo que cada integrante implementara los endpoints, reglas de negocio, servicios de aplicación y componentes de persistencia correspondientes a su responsabilidad.

A continuación se presentan los analíticos de colaboración del repositorio web-services durante el periodo del sprint, evidenciando la participación de cada miembro del equipo.

![contribucion del equipo](report/assets/Sprint_3_Insight.png)


<br>


### 5.2.4. Sprint 4

El cuarto sprint se centrará en completar el módulo de IAM (Identity and Access Management) del RESTful API de AgroTrack, implementando el registro y autenticación real de cuentas (sign-up / sign-in), la emisión y validación de tokens JWT, y la protección de los endpoints de perfil de usuario. El objetivo es cerrar el ciclo de seguridad del backend antes de avanzar hacia la integración completa con el Frontend Web Application.

#### 5.2.4.1. Sprint Planning 4

Se presenta a continuación el resumen del Sprint Planning Meeting para el Sprint 4.

| Campo | Detalle |
|-------|---------|
| **Sprint #** | Sprint 4 |
| **Sprint Planning Background** | |
| **Date** | 2026-07-02 |
| **Time** | 10:00 PM |
| **Location** | Virtual – Discord (canal General) |
| **Prepared By** | Velasquez Laquihuanaco, Eduardo David |
| **Attendees (to planning meeting)** | Alfaro Mallma, Alberto Joaquin / Quispe Perez, Eder Edu / Rodriguez Rojas, Miler Alexander / Velasquez Laquihuanaco, Eduardo David |
| **Sprint 3 – Review Summary** | Durante el Sprint 3 se implementó y desplegó la primera versión del RESTful API (Web Services) de AgroTrack, cubriendo los bounded contexts de Identity, Soil Monitoring, Farming, Alerts y Support & Dashboard bajo una arquitectura Domain-Driven Design con Spring Boot. El backend fue desplegado en Render con base de datos MySQL en Aiven, y documentado mediante OpenAPI/Swagger. |
| **Sprint 3 – Retrospective Summary** | El equipo identificó que el bounded context Identity implementado en el Sprint 3 cubría únicamente el CRUD de usuarios, planes y preferencias de alerta, pero no contaba con un mecanismo real de autenticación (login) ni con protección de endpoints mediante tokens. Se acordó dedicar el Sprint 4 a construir el módulo de IAM (registro, inicio de sesión y seguridad JWT) como base necesaria antes de conectar el Frontend Web Application al backend real. |
| **Sprint Goal & User Stories** | |
| **Sprint 4 Goal** | Our focus is on completing the IAM (Identity and Access Management) module of AgroTrack's RESTful API, including account sign-up, sign-in and JWT-based protection of profile endpoints. We believe it delivers secure and reliable authentication to farmers and agricultural managers accessing the platform. This will be confirmed when users can register and log in through /authentication/sign-up and /authentication/sign-in, receive a valid JWT token, and every request to /users/** is rejected unless that token is present and valid. |
| **Sprint 4 Velocity** | 13 |
| **Sum of Story Points** | 13 |

<br>

#### 5.2.4.2. Aspect Leaders and Collaborators

En el Sprint 4, el equipo mantiene la misma distribución de liderazgo por Bounded Context definida en el Sprint 3, este sprint se concentra principalmente en el IAM.

| Team Member (Last Name, First Name) | GitHub Username | Identity BC | Farming BC | Soil Monitoring BC | Alerts BC | Support & Dashboard BC |
|---|---|---|---|---|---|---|
| Alfaro Mallma, Alberto Joaquin | elprrr | C | C | C | C | L | 
| Quispe Perez, Eder Edu | Eder_09 | C | L | L | C | C |
| Rodriguez Rojas, Miler Alexander | Miler2003 | C | C | C | L | C |
| Velasquez Laquihuanaco, Eduardo David | Edu-VLL | L | C | C | C | C | 



<br>


#### 5.2.4.3. Sprint Backlog 4

El objetivo principal del Sprint 4 fue completar el módulo de IAM (Identity and Access Management) del RESTful API de AgroTrack, implementando el registro y autenticación de cuentas, la emisión de tokens JWT y la protección de los endpoints de perfil de usuario, distribuyendo el desarrollo entre los integrantes del equipo. A continuación se presenta el tablero del sprint y la descomposición de Technical Stories en Work-Items/Tasks.


![Sprint Backlog 4](report/assets/trelloSprint4.png)

*Sprint 4 de AgroTrack*

*Nota.* Elaboración propia.

**Link del trello:** https://trello.com/b/GAgdFmxb/agrotrack-sprint-4

| User Story Id | User Story | Work-Item / Task Id | Work-Item / Task Title | Work-Item / Task Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---|---|---|---|
| TS32 | Endpoint para registrar credenciales de una cuenta (sign-up) | T-044 | Implementar capa de dominio del BC IAM | Crear el agregado IamUser con sus value objects (Email, HashedPassword, Role) y el comando SignUpCommand para el registro de credenciales. | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-045 | Implementar capa de aplicación del BC IAM | Implementar SignUpCommandServiceImpl, incluyendo el hasheo de la contraseña con BCrypt y la asignación automática del rol según el plan (FARMER para BASIC/PRO, AGRICULTURAL_MANAGER para ENTERPRISE). | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-046 | Implementar capa de infraestructura del BC IAM | Crear IamUserPersistenceEntity, RolePersistenceEntity, repositorios JPA y un RoleSeeder que registre ROLE_FARMER, ROLE_AGRICULTURAL_MANAGER y ROLE_ADMIN al arrancar la aplicación. | 4 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-047 | Implementar endpoint POST /authentication/sign-up | Crear AuthenticationController con el endpoint POST /authentication/sign-up, retornando el token JWT generado y manejando el conflicto 409 por email duplicado. | 3 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS33 | Endpoint para iniciar sesión (sign-in) | T-048 | Implementar SignInCommand y servicio de autenticación | Implementar SignInCommandServiceImpl, validando credenciales con BCrypt y generando el token JWT correspondiente. | 3 | Velasquez Laquihuanaco, Eduardo David | Done |
| | | T-049 | Implementar endpoint POST /authentication/sign-in | Agregar el endpoint POST /authentication/sign-in en AuthenticationController, manejando el error 400 por password incorrecto y 404 por email no registrado. | 2 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS34 | Endpoint para listar los roles disponibles | T-050 | Implementar RolesController con endpoint GET /roles | Crear el endpoint GET /roles que retorna los roles IAM sembrados en el sistema (ROLE_FARMER, ROLE_AGRICULTURAL_MANAGER, ROLE_ADMIN). | 1 | Velasquez Laquihuanaco, Eduardo David | Done |
| TS35 | Endpoint para completar el perfil de negocio de una cuenta registrada | T-051 | Vincular el agregado User del BC Identity con la credencial IAM | Actualizar el agregado User para referenciar el iam_user_id y derivar el user_type a partir del plan recibido. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| | | T-052 | Implementar endpoint POST /users para completar el perfil de negocio | Crear el endpoint POST /users que recibe el iam_user_id junto con nombre, plan y empresa, y crea automáticamente la AlertPreference asociada al nuevo perfil. | 3 | Alfaro Mallma, Alberto Joaquin | Done |
| | | T-053 | Manejar validaciones del endpoint POST /users | Implementar el manejo de errores 404 (iam_user_id inexistente) y 409 (perfil ya existente para esa credencial). | 2 | Alfaro Mallma, Alberto Joaquin | Done |
| TS36 | Endpoint para obtener el perfil propio a partir de la sesión activa | T-054 | Implementar endpoint GET /users/by-iam-user/{iamUserId} | Crear el endpoint protegido que retorna el perfil completo del usuario a partir de su iamUserId. | 2 | Rodriguez Rojas, Miler Alexander | Done |
| | | T-055 | Implementar validación de propiedad del perfil consultado | Validar que el iamUserId de la URL coincida con el del dueño del token, retornando 403 en caso contrario. | 2 | Rodriguez Rojas, Miler Alexander | Done |
| TS37 | Protección de los endpoints de perfil con autenticación JWT | T-056 | Configurar Spring Security y el filtro de autenticación JWT | Implementar JwtAuthenticationFilter y la configuración de Spring Security para exigir un token JWT válido en todos los endpoints bajo /users/**. | 4 | Quispe Perez, Eder Edu | Done |
| | | T-057 | Manejar errores de autenticación en endpoints protegidos | Configurar el manejo de errores 401 para solicitudes sin token o con token inválido/expirado. | 2 | Quispe Perez, Eder Edu | Done |



<br>


#### 5.2.4.4. Development Evidence for Sprint Review

En este Sprint, el equipo avanzó en la implementación de los principales productos de la solución: Landing Page, Web Application y Web Services, cubriendo las funcionalidades priorizadas en el Sprint Backlog. A continuación se detallan los commits realizados por cada integrante en los repositorios correspondientes, evidenciando la colaboración del equipo durante el ciclo de desarrollo.

**Landing Page**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/Landing-Page (DuDu-0912) | develop | a4c9970 | Merge branch 'develop' | Integrates the latest changes from develop into the main working branch to keep the Landing Page in sync with recent updates. | 10/07/2026 |
| AgroTrack-Project/Landing-Page (DuDu-0912) | develop | 3b9c7db | Merge branch 'develop' | Merges pending feature updates from develop to consolidate progress before the next review. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | develop | b33f4a1 | merge branch 'feature/changes' into develop | Brings recent UI adjustments from the feature branch into develop for integration testing. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | feature/changes | 5f05ae4 | feat: update README to clarify landing page link and remove license section | Rewrites the README to point clearly to the deployed Landing Page URL and removes an outdated license reference no longer applicable to the project. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | feature/changes | 0c94e42 | merge branch 'feature/changes' into develop | Consolidates documentation fixes from the feature branch into develop. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (elprrr) | develop | 4402245 | Merge branch 'develop' of https://github.com/AgroTrack-Project/Landing-Page into develop | Syncs local changes with the remote develop branch to avoid divergence before pushing new features. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (elprrr) | develop | 661e613 | feat: Update authentication buttons and navigation with animation support | Adds smooth transition animations to the login/register buttons and navigation menu to improve visual feedback on user interaction. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | f12e53e | Merge branch 'main' of https://github.com/AgroTrack-Project/Landing-Page | Pulls the latest changes published on main to keep the local branch up to date before deploying. | 22/06/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | 017b9f2 | feat: update url | Updates the external panel URL referenced in the navigation links to point to the correct production endpoint. | 22/06/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | 6d82380 | Update panel URL for navigation | Fixes the navigation link so users are redirected to the correct dashboard panel after login. | 22/06/2026 |

**Web Application**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-application (elprrr) | main | e36b401 | feat: update logout method to redirect to landing page | Modifies the logout flow so that, after clearing the session, the user is redirected to the public Landing Page instead of the login screen. | 16/05/2026 |
| AgroTrack-Project/web-application (elprrr) | main | 74af4bc | feat: implement entry animation for app layout and clean up imports | Adds a fade-in animation on the main app layout when it loads, and removes unused imports left over from previous refactors. | 16/05/2026 |
| AgroTrack-Project/web-application (elprrr) | main | 263796b | feat: add support ticket functionality with CRUD operations | Implements the full CRUD flow for support tickets, allowing users to create, view, update and close tickets from the application. | 16/05/2026 |
| AgroTrack-Project/web-application (DuDu-tech / Eder-09) | main | 3f18c9c | chore: remove .claude folder and add to gitignore | Removes local AI-assistant configuration files from version control and updates .gitignore to prevent them from being tracked in the future. | 16/05/2026 |
| AgroTrack-Project/web-application (DuDu-tech / Eder-09) | main | 0f45ce0 | Merge branch 'develop' | Merges the latest updates from develop into main to prepare for the upcoming release. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | 4bda6b2 | merge branch 'feature/changes' into develop | Integrates documentation and structural changes made in the feature branch into the shared develop branch. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | e42e728 | docs: update README for clarity and structure improvements | Reorganizes the README sections and improves wording for better readability by new contributors. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | 812c543 | docs: update README for clarity and structure improvements | Further refines the README structure, adding missing setup steps and correcting formatting inconsistencies. | 10/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | 2423fa8 | docs: add translations for login, register, alerts and profile | Adds Spanish and English translation strings for the login, register, alerts and profile views to support internationalization. | 09/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | 5f6e58e | chore: fix dev api base url and add missing auth endpoint path | Corrects the development environment's API base URL and adds a missing path for the authentication endpoint that was causing failed requests. | 09/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | bbf6c9c | fix: remove default 0 from numeric plot and soil-record inputs | Removes the default value of 0 pre-filled in numeric plot and soil-record form fields, preventing users from submitting unintended zero values. | 09/07/2026 |

**Web Services**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-services (elprrr) | main | 4658527 | feat(dashboard): implement REST interface layer with resources, assemblers and controllers | Adds the REST interface layer for the dashboard bounded context, including resources, assemblers and controllers to expose dashboard data through the API. | 19/06/2026 |
| AgroTrack-Project/web-services (elprrr) | main | e613a62 | feat(dashboard): implement infrastructure layer with persistence entities, repositories, assemblers and data seeder | Implements the infrastructure layer for the dashboard context, including persistence entities, repositories, assemblers and a data seeder for local testing. | 19/06/2026 |
| AgroTrack-Project/web-services (elprrr) | develop | ea29a76 | Merge branch 'develop' of https://github.com/AgroTrack-Project/web-services into develop | Synchronizes local develop branch with the remote repository to incorporate teammates' latest commits. | 19/06/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | 2f105e8 | merge branch 'origin/feature/changes' into feature/changes | Pulls remote updates into the local feature branch to keep it aligned before continuing work. | 09/07/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | e23b1d7 | docs(farming): document REST transform assemblers | Adds brief class-level Javadoc to each resource-to-command/query mapper and notes that path-variable ids take precedence over any id present in the request body. | 09/07/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | ed6dbac | docs(farming): document REST controllers and request/response resources | Adds Javadoc documentation to the farming REST controllers and their associated request/response resource classes to clarify their responsibilities. | 09/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 837e91d | docs: update README with project description, installation instructions, and deployment details | Expands the README with a clearer project description, step-by-step installation instructions and deployment details for the backend service. | 10/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 7eb3514 | docs: add description into readme.md | Adds a short project description section at the top of the README for better first-time context. | 10/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 9b6197c | docs: add newline at the end of README.md for consistency | Adds a trailing newline at the end of the README file to follow standard formatting conventions. | 10/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 134bb9a | feat: add JWT authentication module with sign-up and sign-in | Implements the JWT-based authentication module, including sign-up and sign-in endpoints, token generation and validation logic. | 09/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 7491fd5 | feat: link business profiles to IAM accounts via iam_useR_id | Adds a relationship between business profiles and IAM accounts using the iam_user_id field, enabling profile lookup by authenticated identity. | 09/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 9412ced | fix: allow profile updates without resending the current password | Fixes the profile update endpoint so users can update their information without being required to re-enter their current password. | 09/07/2026 |



<br>


#### 5.2.4.5. Execution Evidence for Sprint Review

Durante el Sprint 4, el equipo de Andes Smart completó la implementación del Bounded Context de Identity (IAM) del sistema AgroTrack. Se desarrollaron los endpoints de autenticación (sign-up y sign-in) y de gestión de perfil de negocio, protegidos mediante JWT, como parte de la RESTful API desplegada en Render, documentada mediante OpenAPI/Swagger y consumida exitosamente por la Web Application. A continuación se presentan las capturas de las principales vistas del funcionamiento del sistema.
 
**Swagger UI - Documentación de endpoints desplegados**
 
![swagger 1](report/assets/swagger1-sprint4.png) 
![swagger 2](report/assets/swagger2-sprint4.png) 
![swagger 3](report/assets/swagger3-sprint4.png) 
![swagger 4](report/assets/swagger4-sprint4.png)  
![swagger 5](report/assets/swagger5-sprint4.png)  
![swagger 6](report/assets/swagger6-sprint4.png)  

**Video de demostración**
 
A continuación se presenta el video de demostración del Sprint 4, donde se muestra el funcionamiento de los Web Services de autenticación e identidad documentados en Swagger y los endpoints implementados por el equipo.
 
![swagger 2](report/assets/swagger1-sprint4.png) 
 
**Link del video:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQBe2DaJnk2nRITEOF8NEWw1AUNSwXuPQMT2jwS22LQeqag?e=6vj60X&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
 


<br>


#### 5.2.4.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 4, el equipo documentó los Web Services de autenticación e identidad (IAM) de AgroTrack mediante **OpenAPI / Swagger UI**. La documentación se generó automáticamente a partir de las anotaciones de los controladores REST.
 
A continuación se presenta la tabla con todos los endpoints documentados, junto con la sintaxis de llamada, parámetros, descripción de operación y códigos de respuesta:
 
| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Response |
|:---|:---:|:---|:---|:---|:---:|
| Authentication | POST | `POST /api/v1/authentication/sign-up` | Body: `email`, `password`, `plan` | Registra una nueva credencial de acceso y retorna el id, email, roles derivados del plan y un token JWT | 201, 400, 409 |
| Authentication | POST | `POST /api/v1/authentication/sign-in` | Body: `email`, `password` | Autentica a un usuario existente y retorna el id, email, roles y token JWT | 200, 400, 404 |
| Roles | GET | `GET /api/v1/roles` | — | Retorna el catálogo completo de roles IAM sembrados en el sistema (ROLE_FARMER, ROLE_AGRICULTURAL_MANAGER, ROLE_ADMIN) | 200 |
| Users | POST | `POST /api/v1/users` | Header: `Authorization`; Body: `iam_user_id`, `name`, `plan`, `company` | Completa el perfil de negocio de una cuenta ya autenticada y crea automáticamente una AlertPreference | 201, 401, 404, 409 |
| Users | GET | `GET /api/v1/users/by-iam-user/{iamUserId}` | `iamUserId` (path, UUID); Header: `Authorization` | Obtiene el perfil de negocio completo del usuario autenticado a partir de su iamUserId | 200, 401, 403 |
| Users | ALL | `/api/v1/users/**` | Header: `Authorization` (JWT requerido) | Middleware de protección que exige un token JWT válido para acceder a cualquier endpoint de perfil de usuario | 401 |
 
### Documentación en Swagger UI
 
Se incluyen a continuación capturas de la documentación interactiva accesible en Swagger:
 
 
**Captura 1: Ejecución interactiva del endpoint POST /authentication/sign-up**
 
![Swagger UI - Endpoint POST sign-up](report/assets/endpoint-sign.png) 
 
 
**Captura 2: Detalle del endpoint GET /users/by-iam-user/{iamUserId}**
 
![Swagger UI - Endpoint GET users by iam user](report/assets/endpoint-user.png) 
 
 
 
### Referencias de Implementación
 
**Repositorio de Web Services:** https://github.com/AgroTrack-Project/web-services
 
**URL de la Documentación Swagger:** https://agotrack.onrender.com/api/v1/swagger-ui/index.html#/
 
--- 


<br>


#### 5.2.4.7. Software Deployment Evidence for Sprint Review.

En el transcurso del Sprint 4, el equipo verificó, actualizó y validó el despliegue productivo de los tres productos que conforman la solución: el **Web Service de AgroTrack**, el **Landing Page** y la **Web Application**. Se confirmó la estabilidad de la infraestructura configurada en sprints previos y se aplicaron los ajustes necesarios derivados de las nuevas funcionalidades implementadas en este sprint. Se mantuvo el uso de **Aiven** para la base de datos MySQL, **Render** para el backend, **GitHub Pages** para el Landing Page y **Cloudflare Workers** para la Web Application.

---

<br>

**Fase 1: Verificación y ajuste de la base de datos en Aiven (MySQL)**

Ingreso al panel de administración de Aiven (aiven.io) para validar la continuidad operativa del servicio de base de datos utilizado por el backend durante este sprint.

![BACKEND-1: Panel principal de Aiven en Sprint 4](report/assets/BACKEND-1.png)

<br>

Verificación del estado del servicio `mysql-58d1d5c` en el dashboard de Aiven, confirmando que continuaba con estado **Running** en la infraestructura de DigitalOcean, región California, bajo el plan **Free-1-1gb**, sin incidencias reportadas durante el periodo del sprint.

![BACKEND-2: Estado activo y estable del servicio MySQL](report/assets/BACKEND-2.png)

<br>

Revisión del apartado Services de Aiven para descartar la necesidad de aprovisionar servicios adicionales, dado que el esquema existente soportaba adecuadamente las nuevas entidades incorporadas al modelo de datos.

![BACKEND-3: Revisión de la sección Services sin necesidad de nuevos servicios](report/assets/BACKEND-3.png)

<br>

Confirmación del motor de base de datos en uso, **MySQL**, como sustento relacional para las nuevas tablas y relaciones incorporadas al esquema durante el Sprint 4.

![BACKEND-4: Confirmación del motor MySQL vigente](report/assets/BACKEND-4.png)

<br>

Revisión del plan de servicio contratado, manteniéndose el tier **Free** ($0/mes), región **North America**, plan **Free-1-1gb**, validando que la capacidad de almacenamiento (1 GB) seguía siendo suficiente para el volumen de datos generado hasta la fecha.

![BACKEND-5: Verificación del plan Free vigente en Aiven](report/assets/BACKEND-5.png)

<br>

Actualización de las credenciales de conexión utilizadas por el backend: host `mysql-58d1d5c-joaquinaso5612-e97f.a.aivencloud.com`, puerto `27774`, usuario `avnadmin`, modo SSL `REQUIRED`, reconfirmando su vigencia como variables de entorno en el servicio desplegado en Render.

![BACKEND-6: Revalidación de credenciales de conexión MySQL](report/assets/BACKEND-6.png)

---

<br>

**Fase 2: Actualización del despliegue del API REST en Render**

Ingreso a la plataforma Render (render.com) para gestionar la nueva versión del backend correspondiente a los avances del Sprint 4.

![BACKEND-7: Acceso al panel de Render en Sprint 4](report/assets/BACKEND-7.png)

<br>

Revisión del historial de despliegues del servicio **AGOTRACK**, confirmando que el runtime **Docker** en la región **Ohio** continuaba operativo tras la incorporación de los nuevos endpoints (status: Deployed).

![BACKEND-8: Historial de despliegues del servicio AGOTRACK](report/assets/BACKEND-8.png)

<br>

Verificación del estado general del proyecto en Render, donde el panel "My project" reportaba "All services are up and running", validando la disponibilidad continua de todos los servicios asociados.

![BACKEND-9: Estado general de servicios operativos en Render](report/assets/BACKEND-9.png)

<br>

Revisión de la configuración de disparadores de despliegue automático (auto-deploy) desde el branch `main`, confirmando que los últimos merges de features del Sprint 4 dispararon correctamente un nuevo build.

![BACKEND-10: Verificación del disparador de auto-deploy tras nuevos merges](report/assets/BACKEND-10.png)

<br>

Inspección del repositorio vinculado **BACKEND-AGROTRACK**, confirmando que el commit más reciente correspondiente a las funcionalidades del Sprint 4 fue tomado correctamente por Render para el nuevo build.

![BACKEND-11: Verificación del último commit tomado por Render](report/assets/BACKEND-11.png)

<br>

Revisión de la configuración del Web Service: runtime, branch de despliegue (`main`) y región de hosting (**Ohio, US East**), sin cambios respecto a la configuración base, dado que la infraestructura existente soportaba los nuevos requerimientos.

![BACKEND-12: Configuración vigente del Web Service](report/assets/BACKEND-12.png)

<br>

Verificación del plan de instancia activo, manteniéndose el plan **Free** (512 MB RAM, 0.1 CPU, $0/mes), suficiente para las necesidades del entorno de demostración en esta etapa del proyecto.

![BACKEND-13: Confirmación del plan Free activo en Render](report/assets/BACKEND-13.png)

<br>

Actualización de las variables de entorno del servicio para incorporar nuevos parámetros requeridos por las funcionalidades del Sprint 4, manteniendo `DB_URL`, `DB_USERNAME`, `DB_PASSWORD` y `OPENWEATHER_API_KEY`, y ejecutando un nuevo despliegue mediante **Manual Deploy**.

![BACKEND-14: Actualización de variables de entorno y nuevo despliegue](report/assets/BACKEND-14.png)

<br>

Confirmación del nuevo build en estado **Live**, validando que el backend actualizado quedó disponible públicamente con las funcionalidades incorporadas en el Sprint 4 y el auto-deploy habilitado desde `main`.

![BACKEND-15: Backend actualizado en estado Live tras el Sprint 4](report/assets/BACKEND-15.png)

---

<br>

**Fase 3: Actualización del despliegue del Landing Page en GitHub Pages**

Se verificó el repositorio **Landing-Page** dentro de la organización **AgroTrack-Project**, confirmando que la rama `develop` recibió pushes recientes con los últimos ajustes visuales y de contenido correspondientes al Sprint 4, y que la rama `main` mantenía integrados los cambios de las carpetas `assets`, `css` y `js`, junto con 44 commits acumulados, 4 tags y 2 releases publicados (siendo `release/v3.0.0` la versión vigente).

![LANDING-1: Repositorio Landing-Page con la última versión integrada en main](report/assets/LANDING-1.png)

<br>

Ingreso a la sección **Actions** del repositorio para revisar la ejecución del workflow **pages-build-deployment**, encargado de automatizar la publicación del sitio estático. Se confirmó que las 6 ejecuciones registradas finalizaron de manera exitosa sobre el branch `main`, incluyendo las dos corridas más recientes generadas a raíz de los últimos cambios incorporados al Landing Page durante este sprint.

![LANDING-2: Historial de ejecuciones exitosas del workflow pages-build-deployment](report/assets/LANDING-2.png)

<br>

Verificación del sitio publicado en producción mediante **GitHub Pages**, confirmando la correcta visualización de la sección hero ("Grow better with real data"), la propuesta de valor del producto, los botones de llamada a la acción (Get started now / Request demo) y la sección "The problem we solve", validando que el contenido, los estilos y las imágenes se cargaran correctamente en el entorno desplegado.

![LANDING-3: Landing Page de AgroTrack desplegado y funcionando en producción](report/assets/LANDING-3.png)

---

<br>

**Fase 4: Verificación del despliegue de la Web Application en Cloudflare Workers**

Como parte del Sprint 4, se verificó y actualizó el despliegue de la Web Application de AgroTrack, previamente publicada en el Sprint 2 sobre la plataforma **Cloudflare Workers**. Se confirmó que las ramas feature de los integrantes del equipo con las nuevas funcionalidades del sprint fueron integradas a la rama `develop` mediante pull requests revisados por el Team Leader, y posteriormente fusionadas hacia `main` para disparar una nueva publicación del entorno de producción.

Se comprobó el correcto funcionamiento de las vistas actualizadas desde distintos dispositivos, validando que los módulos de gestión de parcelas, cultivos, monitoreo del suelo, alertas climáticas y perfil de usuario continuaran operando correctamente en producción tras la incorporación de los cambios del Sprint 4.

<br>

**Figura**
*Evidencia de deployment 1*
![Web Application - Vista 1](report/assets/web-app-1.png)
*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 2*
![Web Application - Vista 2](report/assets/web-app-2.png)
*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 3*
![Web Application - Vista 3](report/assets/web-app-3.png)
*Nota.* Elaboración propia.

**Figura**
*Evidencia de deployment 4*
![Web Application - Vista 4](report/assets/web-app-4.png)
*Nota.* Elaboración propia.

 
<br>


### 5.2.4.8. Team Collaboration Insights during Sprint.

En esta sección el equipo explica cómo se han desarrollado las actividades de implementación y se presenta los analíticos de colaboración y commits en GitHub, realizados por los miembros del equipo durante el Sprint 4.

**Distribución de Trabajo:**

Durante el Sprint 4, el equipo consolidó el desarrollo del proyecto atendiendo tres frentes en paralelo: completar la cuarta versión de la Landing Page, continuar la evolución de la Web Application hacia la versión v3.0.0 e iniciar el desarrollo de la versión v2.0.0 del Backend de AgroTrack Platform. A diferencia del Sprint anterior, donde cada integrante desarrolló un único Bounded Context de manera independiente, en este Sprint se adoptó una estrategia de colaboración cruzada, en la que todos los integrantes participaron activamente en el desarrollo de cada uno de los Bounded Contexts del Backend, compartiendo conocimientos y resolviendo problemas técnicos de manera conjunta.

El equipo mantuvo un enfoque de trabajo colaborativo mediante reuniones de seguimiento, revisiones de código y la integración continua en GitHub, lo que permitió coordinar eficientemente las tareas desarrolladas por cada integrante y garantizar la correcta integración de todos los componentes implementados durante el Sprint.

**Métricas de Colaboración:**

<div align="center">    
  <p>
    <b>Contributors de la Landing Page v4.0.0</b>
  </p>
  <img src="report/assets/contributors-sprint-4-landing-page.png" alt="Contributors landing page v4.0.0" width="600">
  <p><i><b>Fuente</b>: GitHub Insights del repositorio agrotrack/landing-page.</i></p>
</div>

<div align="center">
  <p>
    <b>Contributors de la Web Application v3.0.0</b>
  </p>
  <img src="report/assets/contributors-sprint-4-web-application.png" alt="Contributors web application v3.0.0" width="600">
  <p><i><b>Fuente</b>: GitHub Insights del repositorio agrotrack/web-application.</i></p>
</div>

<div align="center">
  <p>
    <b>Contributors del Backend (AgroTrack Platform v2.0.0)</b>
  </p>
  <img src="report/assets/contributors-sprint-4-web-platform.png" alt="Contributors agrotrack platform v2.0.0" width="600">
  <p><i><b>Fuente</b>: GitHub Insights del repositorio agrotrack/web-services.</i></p>
</div>

Los analíticos muestran la participación activa de todos los integrantes durante el Sprint, evidenciando un incremento en las contribuciones como resultado del desarrollo simultáneo de la Landing Page, la Web Application y el Backend.

**Reflexiones del Equipo:**

- **Velasquez Laquihuanaco, Eduardo David:** "En el Sprint 4 implementé la capa **Application** del Bounded Context de IAM, desarrollando los módulos `acl`, `commandservices` y `queryservices`, responsables de la lógica de aplicación, la ejecución de comandos y la atención de consultas. Trabajar en esta capa me permitió comprender la importancia de separar las operaciones de escritura y lectura, manteniendo una arquitectura limpia y escalable."

- **Alfaro Mallma, Alberto Joaquin:** "En el Sprint 4 participé en el desarrollo de la capa **Domain** del Bounded Context de IAM, implementando los paquetes `model` y `repositories`. Esta parte fue fundamental para definir las entidades principales del dominio y los contratos de persistencia, fortaleciendo la base sobre la que funciona el contexto."

- **Quispe Perez, Eder Edu:** "En el Sprint 4 desarrollé la capa **Infrastructure** del Bounded Context de IAM, implementando los módulos `authorization/sfs`, `hashing/bcrypt`, `persistence/jpa` y `tokens/jwt`. Esta experiencia me permitió integrar la autenticación, autorización, persistencia de datos y generación de tokens, comprendiendo cómo los servicios externos soportan el funcionamiento del sistema."

- **Rodriguez Rojas, Miler Alexander:** "En el Sprint 4 implementé la capa **Interfaces** del Bounded Context de IAM, desarrollando los módulos `acl` y `rest`, encargados de exponer las funcionalidades del sistema y facilitar la comunicación con otros contextos y con el cliente. Esta parte me permitió entender la importancia de desacoplar la lógica de negocio de los mecanismos de acceso."
**Lección Aprendida:**

El equipo identifica las siguientes lecciones de este Sprint 4:

1. **La colaboración cruzada en el desarrollo del Backend aceleró la implementación de los Bounded Contexts:** Trabajar todos sobre los mismos módulos permitió compartir conocimientos, resolver bloqueos técnicos más rápido y mantener consistencia entre Frontend y Backend.

2. **Atender tres productos en paralelo (Landing Page, Web Application y Backend) exige una coordinación de prioridades más estricta:** Fue necesario planificar con cuidado el tiempo de cada integrante para no descuidar ninguno de los tres frentes de trabajo del Sprint.

3. **Separar Monitoring y Alerts en dos Bounded Contexts distintos permitió un diseño más claro de responsabilidades:** Monitoring se enfoca en capturar y almacenar el estado de las parcelas, mientras que Alerts consume esa información para generar notificaciones según el plan del usuario, evitando mezclar ambas responsabilidades en un solo módulo.

4. **Integrar el módulo de Support al Bounded Context de Dashboard permitió centralizar la experiencia post-venta del usuario:** Al tener analíticas y soporte en un mismo espacio, se facilita que agricultores y empresarios agrícolas encuentren ayuda contextual junto a la información que ya están consultando.

5. **La revisión conjunta de código entre integrantes que trabajaron en los mismos Bounded Contexts mejoró la calidad de la integración:** Al tener varias personas familiarizadas con un mismo módulo, fue más sencillo detectar inconsistencias antes de fusionar los cambios en `develop`.

6. **La integración progresiva y constante en `develop` permitió sostener el desarrollo simultáneo de tres productos sin generar conflictos mayores al cierre del Sprint:** Mantener commits frecuentes facilitó que el trabajo de frontend, backend y landing page se integrara de forma ordenada.

---

<br>


### 5.3.2. Registro de Entrevistas

**Entrevista N° 1**

| **Nombres y apellidos**      | **Edad** | **Distrito** |
|------------------------------|----------|--------------|
| Matias Carrillo Acho         | 20 años  | Lima         |

| **Segmento**          | **URL**            | **Inicio** | **Duración** |
|-----------------------|--------------------|------------|--------------|
| Empresario Agricola   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQAAri3xk_xURropEvsluVzmAXj4s7kSXhMjvGD23jlLV3I?e=ua1W4A&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00      | 6:45 min     |

![Entrevista-1](report/assets/entrevista-1-s3.png)

**Resumen:** En el video se presenta una prueba de usabilidad de la plataforma AgroTrack realizada con Matías Carrillo, empresario del sector agrícola. Durante la sesión, el usuario interactúa con la landing page y el dashboard de la aplicación, evaluando la facilidad de uso, claridad de la información, visualización de parcelas, métricas de rendimiento, consumo de agua y exportación de reportes. Finalmente, brinda retroalimentación positiva sobre la utilidad de la plataforma y propone mejoras como agregar más gráficos y métricas para una mejor visualización de la información agrícola.

**Entrevista N° 2**

| **Nombres y apellidos**   | **Edad**   | **Distrito**   |
|---------------------------|------------|----------------|
| Valeri Rojas                 | 22 años    | Los Olivos          |

| **Segmento** | **URL** | **Inicio** | **Duración** |
|--------------|---|---|--------------|
| Empresaria Agricola  | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQAsdhz3gAqtRqfZKulI0qiAAb1ilpwoVd6NDvYrs-_WKio?e=xPs1e0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00 | 7:26 min  |

![Entrevista-2](report/assets/Segmento-Valeri.png)

**Resumen:** Valeri Rojas, de 22 años de Los Olivos, quien trabaja en la empresa agrícola Agroverde del Norte, fue entrevistada sobre la plataforma AgroTrack. Durante la prueba de usabilidad, navegó por la landing page y el panel de control, identificando rápidamente que la plataforma permite monitorear gestiones de riego basadas en datos. Valeri aprecio que el panel de control presenta un resumen organizado del estado de todas las parcelas sin necesidad de entrar a cada una, que los indicadores facilitan la comparación de rendimiento entre parcelas, y que la información sobre pérdidas estimadas y consumo de agua proporciona una buena base para identificar problemas y tomar decisiones de mejora. Tambien elogió la simplicidad del proceso de exportación de reportes en PDF y la navegación intuitiva de la plataforma. Sin embargo, sugirió agregar proyecciones de rendimiento futuro y análisis de costos por parcela para campañas futuras. En conclusión, recomendaría AgroTrack a otros empresarios del sector agrícola porque centraliza la información importante sobre las parcelas y facilita el monitoreo de indicadores clave que ayudan a la toma de decisiones.

**Entrevista N° 3**

| **Nombres y apellidos**   | **Edad**   | **Distrito**   |
|---------------------------|------------|----------------|
| Lucia Alarcon             | 23 años    | Comas         |

| **Segmento** | **URL** | **Inicio** | **Duración** |
|--------------|---|---|--------------|
| Agricultora   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQBE_PFpJHzZSY8DPfCCjxgUAYq_Li89X4uKG9cjUehaKr0?e=8mXpdF&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00 | 8:35 min      |

![Entrevista-3](report/assets/Segmento-Lucia.png)

**Resumen:** Lucía Larcón, de 23 años del Distrito de Commerce, agricultora entrevistada sobre AgroTrack, comprendió desde el inicio que la plataforma sirve para monitorear cultivos y el estado del suelo, además de recibir avisos sobre cambios climáticos, destacando que la información estaba clara y las funciones se mostraban de forma sencilla. Durante la prueba navegó por el panel principal, registró y editó parcelas, ingresó datos de humedad y temperatura del suelo, gestionó cultivos hasta cosecharlos, y revisó las recomendaciones de riego, señalando que todo el proceso fue bastante sencillo y los campos eran claros. Valoró positivamente las recomendaciones de riego por considerarlas lógicas para evitar desperdiciar agua, y las alertas climáticas por permitirle planificar actividades y proteger sus cultivos con anticipación. Mencionó que las opciones de configuración de alertas no eran difíciles de encontrar, aunque al inicio le tomó unos segundos ubicarlas y sugirió que podrían estar más visibles. Como mejoras propuso opciones más grandes y accesibles desde el celular para registrar datos rápidamente, gráficos más visuales sobre la evolución de la humedad del suelo, y destacó que actualmente lleva sus anotaciones en un cuaderno o de memoria, por lo que tener toda la información organizada en una sola plataforma le ayudaría a tomar decisiones más rápidas.

**Entrevista N° 4**

| **Nombres y apellidos**   | **Edad**   | **Distrito**   |
|---------------------------|------------|----------------|
| Christopher Mejia         | 28 años    | Los Olivos     |

| **Segmento** | **URL** | **Inicio** | **Duración** |
|--------------|---|---|--------------|
| Empresario Agricola   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQB0QuCKjIVyTJUrsuQBrtjnAQwPmiZGOUkIMTinESxiDiU?e=42L1Vu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00 | 9:58 min      |

![Entrevista-4](report/assets/Segmento-Cristopher.png)

**Resumen:** Christopher Mejía, de 28 años, dueño de Inca Agroindustries & SACS, exploró AgroTrack identificando rápidamente que es una plataforma amigable y directa con los datos mostrados, útil para la gestión agrícola del día a día. Durante la prueba navegó por el dashboard donde revisó el rendimiento de parcelas, resumen de pérdidas y consumo de agua, intentó exportar reportes en PDF y Excel aunque no logró completar la descarga, utilizó el módulo de soporte para reportar el problema mediante un ticket, y exploró las funcionalidades de parcelas, cultivos, estado del suelo, recomendaciones de riego e historial de cosechas. Valoró positivamente que el panel de control está bien ordenado y claro, que la información de rendimiento por parcela ayuda a identificar dónde se produce más y dónde se pierde, y que las alertas climáticas en tiempo real son muy útiles para su operación. Sin embargo, señaló que no encontró métricas financieras suficientes para tomar decisiones de inversión, y como principal mejora solicitó incorporar un indicador de cuánto dinero producen sus parcelas por hectárea en efectivo. A pesar de los problemas con la exportación de reportes, consideró que la navegación general es sencilla y afirmó que recomendaría AgroTrack a otros empresarios del sector siempre que se mantengan las alertas en tiempo real.

**Entrevista N° 5**

| **Nombres y apellidos**   | **Edad**   | **Distrito**   |
|---------------------------|------------|----------------|
| Jorge Ramírez             | 37 años    | Cañete         |

| **Segmento** | **URL** | **Inicio** | **Duración** |
|--------------|---|---|--------------|
| Agricultor   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a267_upc_edu_pe/IQCn1iiiJRjvTKpLXB4BILBdATYBcfP8wG8cSEe3SHraYPo?e=voT80Y&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00 | 14:38 min |

![Entrevista-5](report/assets/Segmento-Jorge.png)

**Resumen:** Jorge Ramírez, de 37 años, agricultor con varias hectáreas de parcelas propias, exploró AgroTrack desde la Landing Page identificando rápidamente que se trata de una plataforma para monitorear cultivos y el estado del suelo, destacando que la web transmite la sensación de mostrar datos en tiempo real. Durante la prueba registró una parcela nueva (ubicación, tamaño y cultivo), navegó la sección de estado del suelo, y revisó el módulo de alertas climáticas y la recomendación de riego asociada a su cultivo. Valoró positivamente que la información se mostrara de forma clara desde la Landing Page sin necesitar ayuda externa, que el registro de parcela y de datos del suelo fue sencillo de completar, y que las alertas climáticas le resultan útiles para tomar decisiones a tiempo sobre sus cultivos. Sin embargo, señaló que la recomendación de riego ("bajo") le pareció poco descriptiva y necesitaría más detalle o contexto para confiar en ella, que no encontró un acceso directo a la sección de cultivos sin pasar primero por "editar" en la parcela, y que tuvo dudas sobre cómo recibiría las alertas en la práctica (sugirió notificaciones por celular o WhatsApp en lugar de depender de acceso constante a una computadora). Como mejora adicional, propuso resaltar visualmente la información más importante con colores y agregar pequeñas descripciones o tooltips para usuarios nuevos. A pesar de estas observaciones, consideró que la navegación general es intuitiva, que usaría AgroTrack en su día a día para reemplazar su seguimiento actual de cultivos, y que la plataforma tiene utilidad real para agricultores como él.

**Entrevista N° 6**

| **Nombres y apellidos**   | **Edad**   | **Distrito**   |
|---------------------------|------------|----------------|
| Johan Contreras           | 25 años    | San Miguel     |

| **Segmento** | **URL** | **Inicio** | **Duración** |
|--------------|---|---|--------------|
| Empresario Agricola   | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQC_3fMojx7QRpXxX_AI_lCEAVlwmCBCt3_sEttPiNL0n2Q?e=iuZLHA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D | 00:00 | 7:55 min   |

![Entrevista-6](report/assets/Segmento-Johan.png)

**Resumen:** Se entrevistó a Johan Contreras, empresario agrícola de 25 años del distrito de San Miguel, a quien se le presentó la plataforma AgroTrack y sus principales funcionalidades. En términos generales, Johan tuvo una experiencia positiva: identificó rápidamente el valor de la plataforma desde el landing page, valoró que el dashboard concentrara toda la información en un solo lugar y destacó especialmente la vista de rendimiento por parcela como una mejora respecto a sus métodos actuales con papel y Excel. Sin embargo, señaló que los datos de pérdidas y consumo de agua aún le parecen insuficientes para tomar decisiones concretas, ya que necesitaría mayor detalle por fecha y por parcela específica; además, sugirió incorporar métricas de costos operativos como mano de obra e insumos, y alertas automáticas ante caídas de rendimiento. La navegación le resultó sencilla e intuitiva, aunque tuvo una pequeña dificultad inicial para encontrar el historial, y la exportación de reportes funcionó bien, aunque propuso añadir la opción de filtrar por rango de fechas. Finalmente, Johan indicó que sí recomendaría AgroTrack a otros empresarios del sector, reconociendo que la plataforma tiene una base sólida y bien orientada al campo, aunque aún le falta madurar en algunas funcionalidades

### 5.3.3. Evaluaciones según heurísticas.

#### UX Heuristics & Principles Evaluation

#### Usability – Inclusive Design – Information Architecture

**CARRERA:** Ingeniería de Software

**CURSO:** Desarrollo de Aplicaciones Open Source

**SECCIÓN:** 11959

**PROFESORES:** Hugo Mori

**AUDITOR:** AURORA

**CLIENTE(S):** 

- Carrillo Acho, Matias
- Rojas, Valeri
- Alarcon, Lucia
- Mejia, Christopher
- Ramirez, Jorge
---

**SITE APP A EVALUAR:** 
AgroTrack

**TAREAS A EVALUAR:**

- Registrar y administrar parcelas agrícolas.
- Consultar alertas climáticas según ubicación del cultivo.
- Revisar información del perfil y plan del usuario.
- Navegar entre las diferentes secciones de la plataforma.

---

**ESCALA DE SEVERIDAD:**
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel | Descripción                                                                                                                                                                                     |
| :---: |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                    |
| **2** | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| **3** | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.                                 |
| **4** | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                               |

---

**TABLA RESUMEN:**

|   #   | Problema                                                                                                                                                    | Escala de severidad | Heurística/Principio violada(o)                                       |
|:-----:|:------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------:|:----------------------------------------------------------------------|
| **1** | Falta de información contextual al momento de crear o editar una parcela agrícola. El usuario no recibe suficiente orientación sobre los datos requeridos.  |          3          | Usability: Visibilidad del estado del sistema / Ayuda y documentación |
| **2** | Las alertas climáticas muestran información de riesgo, pero no incluyen recomendaciones claras de acciones que debería realizar el agricultor.              |          3          | Usability: Correspondencia entre el sistema y el mundo real           |
| **3** | La navegación lateral contiene varias opciones similares y puede generar dificultad para usuarios nuevos al identificar dónde administrar sus cultivos.     |          2          | Information Architecture: Organización y claridad de navegación       |
| **4** | Los botones de edición y eliminación de parcelas utilizan únicamente iconos sin etiquetas descriptivas, lo que puede generar confusión en algunos usuarios. |          2          | Inclusive Design: Reconocimiento antes que recuerdo                   |
| **5** | No existe suficiente diferenciación visual entre estados de las parcelas (activas, con riesgo climático o pendientes de configuración).                     |          3          | Usability: Visibilidad del estado del sistema                         |
| **6** | La información mostrada en el perfil del usuario no explica claramente las diferencias entre los planes disponibles ni los beneficios de cada uno.          |          2          | Usability: Ayuda y documentación                                      |
| **7** | La plataforma no presenta mensajes personalizados o recomendaciones según el tipo de cultivo registrado y ubicación del usuario.                            |          2          | Inclusive Design: Flexibilidad y eficiencia de uso                    |

---

**DESCRIPCIÓN DE PROBLEMAS:**

---

**PROBLEMA #1:**

- **Severidad:** 3
- **Heurística violada:** Usability: Visibilidad del estado del sistema / Ayuda y documentación.

- **Problema:** Al momento de administrar parcelas agrícolas, el usuario puede no comprender completamente qué información debe ingresar o cuál es la finalidad de cada campo solicitado.

![Problema 1](report/assets/problema-1.png)

- **Recomendación:** Agregar textos de ayuda, ejemplos de datos esperados y mensajes informativos dentro de los formularios de creación y edición de parcelas.


---

**PROBLEMA #2:**

- **Severidad:** 3

- **Heurística violada:** Usability: Correspondencia entre el sistema y el mundo real.

- **Problema:** Las alertas climáticas permiten identificar riesgos como lluvias intensas, pero no proporcionan recomendaciones prácticas para que el agricultor pueda tomar decisiones.

![Problema 2](report/assets/problema-2.png)

- **Recomendación:** Incorporar sugerencias agrícolas asociadas a cada alerta, como protección del cultivo, revisión del sistema de riego o prevención ante eventos climáticos.


---

**PROBLEMA #3:**

- **Severidad:** 2

- **Heurística violada:** Information Architecture: Organización y claridad de navegación.

- **Problema:** La estructura del menú lateral puede resultar poco intuitiva para usuarios nuevos debido a la cantidad de opciones disponibles.

![Problema 3](report/assets/problema-3.png)

- **Recomendación:** Agrupar opciones relacionadas y utilizar nombres más descriptivos para cada sección.

---

**PROBLEMA #4:**

- **Severidad:** 2

- **Heurística violada:** Inclusive Design: Reconocimiento antes que recuerdo.

- **Problema:** Los botones de editar y eliminar parcelas están representados únicamente mediante iconos, lo que puede dificultar su comprensión para ciertos usuarios.

![Problema 4](report/assets/problema-4.png)

- **Recomendación:** Agregar etiquetas de texto o tooltips descriptivos al pasar el cursor sobre cada acción.

---

**PROBLEMA #5:**

- **Severidad:** 3

- **Heurística violada:** Usability: Visibilidad del estado del sistema.

- **Problema:** Las parcelas muestran un estado general como "Active", pero no existe una representación visual clara sobre posibles riesgos asociados al cultivo.

- **Recomendación:** Agregar indicadores visuales adicionales como niveles de riesgo climático, estados de cultivo o alertas asociadas.

![Problema 5](report/assets/problema-5.png)

---

**PROBLEMA #6:**

- **Severidad:** 2

- **Heurística violada:** Usability: Ayuda y documentación.

- **Problema:** La sección de perfil muestra diferentes planes disponibles, pero la información puede no ser suficiente para que el usuario comprenda qué beneficios obtiene al cambiar de plan.

![Problema 6](report/assets/problema-6.png)

- **Recomendación:** Añadir una comparación detallada entre planes y explicar las funcionalidades adicionales disponibles.

---

**PROBLEMA #7:**

- **Severidad:** 2

- **Heurística violada:** Inclusive Design: Flexibilidad y eficiencia de uso.

- **Problema:** La plataforma presenta información general, pero no adapta completamente la experiencia según características del usuario como ubicación o cultivos registrados.

![Problema 7](report/assets/problema-7.png)

- **Recomendación:** Implementar recomendaciones personalizadas basadas en ubicación, tipo de cultivo y condiciones climáticas actuales.

---

## 5.4. Video About-the-Product

La presente sección tiene como propósito introducir y detallar el contenido del **Video About-the-Product de AgroTrack**. Este recurso audiovisual ha sido desarrollado como una herramienta de comunicación estratégica orientada a dos audiencias clave.

Por un lado, está diseñado para los visitantes de la **Landing Page**, brindándoles una visión clara, visual y dinámica sobre el propósito de la plataforma, el problema que busca resolver y las principales características que diferencian a AgroTrack como una solución tecnológica enfocada en la gestión y monitoreo agrícola.

Por otro lado, sirve como una guía introductoria para los futuros usuarios de la aplicación, mostrando de manera práctica cómo interactuar con el sistema y ejecutar las tareas principales relacionadas con el monitoreo de condiciones del suelo, gestión de información agrícola, recepción de alertas y visualización de datos relevantes mediante el dashboard.

De esta manera, el video permite comunicar el valor de la solución y facilitar la comprensión de los principales procesos que AgroTrack busca optimizar dentro del contexto agrícola.

| **URL**          | **Inicio** | **Duración** |
|------------------|------------|--------------|
| https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQCkTU4cm894R6fEo-t8pc4-AVTzMh-HlJTa9Be-ru6pf6E?e=My3Hvs&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D    | 00:00      | 00:57 min    |

![Video About The Product](report/assets/about-the-product.png)

# Conclusiones

## Conclusiones y recomendaciones

### Validación de Problem Statements, Assumptions e Hypothesis Statements

**Problem Statement 1 (agricultores pequeños y decisiones de riego sin datos objetivos).** Las entrevistas de validación de usabilidad realizadas en el Sprint 3 (Lucía Alarcón y Jorge Ramírez) confirmaron que el problema identificado en el Capítulo I sigue siendo real y relevante: ambos usuarios señalaron que actualmente llevan el registro de sus cultivos en cuaderno o de memoria, y valoraron positivamente que la plataforma centralice el estado del suelo y las recomendaciones de riego en un solo lugar. Sin embargo, también se identificó que el mensaje de recomendación de riego (por ejemplo, "bajo") resultó **poco descriptivo** para el usuario, quien esperaba mayor contexto para confiar en la sugerencia. Esto valida parcialmente el problem statement: la necesidad existe, pero la solución actual todavía no comunica las recomendaciones con el nivel de claridad que un agricultor con poca experiencia tecnológica requiere.

**Problem Statement 2 (alertas climáticas anticipadas).** Este statement fue el que obtuvo mayor validación positiva. Lucía Alarcón y Jorge Ramírez destacaron que las alertas climáticas les permiten "planificar actividades y proteger sus cultivos con anticipación". No obstante, la evaluación heurística (Problema #2) evidenció que las alertas informan el riesgo pero no sugieren una acción concreta a tomar, lo que limita el impacto práctico de la funcionalidad frente a la hipótesis original.

**Problem Statement 3 (registro y seguimiento digital de cultivos).** Validado positivamente por los empresarios agrícolas entrevistados (Valeri Rojas, Christopher Mejía, Johan Contreras), quienes coincidieron en que el panel de control centraliza información que hoy gestionan de forma manual o en Excel. Christopher Mejía señaló explícitamente que el registro por parcela "ayuda a identificar dónde se produce más y dónde se pierde", validando el valor central de la propuesta.

**Problem Statement 4 (visibilidad centralizada para empresarios agrícolas PYMEs).** Fue el statement con mejor recepción cuantitativa: los cuatro empresarios entrevistados (Matías Carrillo, Valeri Rojas, Christopher Mejía, Johan Contreras) coincidieron en que el dashboard resuelve un problema real de dispersión de información. Sin embargo, todos ellos —de manera consistente— señalaron la misma brecha: **la ausencia de métricas financieras** (costo por hectárea, rentabilidad, costos operativos) necesarias para la toma de decisiones de inversión. Esto indica que el problem statement fue validado en su dimensión operativa, pero no cubre aún completamente la dimensión financiera del segmento empresarial.

De las ocho assumptions planteadas en el Lean UX Canvas, las validaciones realizadas durante el Sprint 3 permiten concluir lo siguiente:

- Se confirma que los agricultores **tienen dificultades reales** para decidir cuándo regar sin datos del suelo (Assumption 1), y que contar con datos de humedad les ayuda a tomar mejores decisiones (Assumption 2).
- Se confirma que los agricultores **valoran recibir alertas climáticas anticipadas** (Assumption 3): Lucía Alarcón y Jorge Ramírez destacaron que estas les permiten planificar y proteger sus cultivos con anticipación; sin embargo, la evaluación heurística (Problema #2) mostró que las alertas informan el riesgo pero no sugieren una acción concreta, lo que matiza el valor percibido de esta assumption en su implementación actual.
- Se confirma **parcialmente** que las recomendaciones automáticas de riego basadas en datos del suelo y del clima mejoran el uso del agua y reducen desperdicios (Assumption 4): los usuarios reconocen valor en recibir una recomendación automática, pero el mensaje actual (por ejemplo, "bajo") resultó poco descriptivo, por lo que el impacto real en el ahorro de agua todavía no puede confirmarse con el nivel de claridad necesario.
- Se confirma la preferencia por **herramientas simples y visuales** (Assumption 5): todos los entrevistados de ambos segmentos describieron la navegación como "sencilla" o "intuitiva".
- Se confirma que el registro digital **reemplaza favorablemente el papel o la memoria** (Assumption 6), validado explícitamente por Lucía Alarcón.
- La disposición a usar la plataforma si perciben beneficio (Assumption 7) se sostiene, pero surge una nueva condición no anticipada originalmente: los empresarios agrícolas condicionan la adopción a la disponibilidad de métricas financieras, un matiz que no estaba explícito en la assumption original.
- Se confirma que, aunque el ingreso de datos siga siendo manual en esta etapa del producto, los usuarios perciben valor en la plataforma en la medida en que las recomendaciones que reciben son útiles (Assumption 8): tanto agricultores como empresarios agrícolas valoraron positivamente centralizar en un solo lugar información que hoy gestionan en papel, de memoria o en Excel, aun sin automatización de la captura de datos.

Los Hypothesis Statements definidos en el Capítulo I establecían umbrales cuantitativos de éxito (60% de consulta de monitoreo antes de regar, 50% de acción preventiva ante alertas, reducción de consumo de agua tras 30 días, 40% de registro activo de cultivos en el primer mes). Es importante señalar que **estas métricas no han podido validarse cuantitativamente aún**, dado que las validaciones realizadas hasta el Sprint 3 corresponden a pruebas de usabilidad puntuales y no a un despliegue con uso continuado en campo durante los periodos de tiempo especificados en las hipótesis (2 semanas, 24 horas, 30 días, 1 mes). Las entrevistas de Sprint 3 ofrecen evidencia cualitativa favorable (los usuarios afirman que usarían la plataforma y que resuelve un problema real), pero el equipo reconoce que la validación cuantitativa de estas hipótesis queda pendiente como trabajo futuro, una vez la plataforma cuente con una base de usuarios activos y datos de uso reales.

### Conclusiones por Sprint

#### **Sprint 1 – Investigación, problema y Landing Page**

- **Sobre el análisis del problema y la investigación de usuario:** Se concluye que las seis entrevistas realizadas a agricultores pequeños y empresarios agrícolas de distintas regiones del Perú (Amazonas, Arequipa, Lima, Piura, Chachapoyas) permitieron validar la existencia de un problema recurrente: la toma de decisiones de riego por intuición, sin datos objetivos del estado del suelo, y la ausencia de herramientas de registro digital. Esta fase permitió construir el Problem Statement, los User Personas, los Empathy Maps, los User Journey Maps y el Big Picture Event Storming del dominio agrícola.

- **Sobre la propuesta de valor y validación inicial:** La primera versión de la Landing Page, desarrollada en HTML5, CSS3 y JavaScript con soporte bilingüe (EN/ES) mediante i18n, permitió comunicar de forma clara la propuesta de valor de AgroTrack. Su despliegue temprano funcionó como un medio de validación inicial de la idea de negocio frente a los dos segmentos objetivo (agricultores pequeños y empresarios agrícolas).

- **Sobre la documentación y modelado del proyecto:** La construcción del informe permitió consolidar los hallazgos del Problem Statement, Needfinding, User Personas, Empathy Maps, Journey Maps, Big Picture Event Storming y Ubiquitous Language, generando una visión integral del dominio agrícola. El uso de Domain-Driven Design desde esta etapa temprana facilitó una primera identificación de posibles bounded contexts del sistema.

- **Sobre la definición de requerimientos:** La especificación inicial de User Stories con criterios de aceptación en formato Gherkin, junto con el Impact Mapping y el Product Backlog priorizado por valor de negocio, permitió transformar las necesidades identificadas en las entrevistas en funcionalidades concretas, sirviendo de guía estructurada para los sprints siguientes.

#### **Sprint 2 – Desarrollo del Frontend (Web Application)**

- **Sobre el diseño e implementación de interfaces:** Se concluye que el desarrollo del Frontend Web Application, construido con Angular y Angular Material, permitió transformar los requerimientos funcionales en interfaces visuales e interactivas para los bounded contexts de Identity, Farming, Soil Monitoring, Climate Alerts y Support & Dashboard, alineadas con las necesidades identificadas en el Sprint 1.

- **Sobre la experiencia de usuario (UX/UI):** La construcción de vistas de registro, inicio de sesión, gestión de parcelas y cultivos, monitoreo del suelo y alertas climáticas, con soporte bilingüe (i18n) y atributos ARIA (a11y), permitió priorizar la facilidad de uso para agricultores con poca experiencia tecnológica.

- **Sobre la arquitectura frontend:** La modularización de componentes Angular por bounded context permitió mantener un código organizado y reutilizable, sentando la base para su posterior integración con los servicios REST reales desarrollados en el Sprint 3.

- **Sobre el avance funcional del producto:** El Sprint 2 permitió evidenciar un avance significativo hacia el producto mínimo viable (MVP), contando con vistas funcionales y navegables que representan los principales flujos del sistema, inicialmente sostenidas sobre datos simulados y posteriormente conectadas a los servicios backend reales en el Sprint 3.

#### **Sprint 3 – Desarrollo del Backend (Web Services)**

- **Sobre el diseño e implementación de la API REST:** Se concluye que el desarrollo del backend permitió transformar los requerimientos funcionales en servicios REST documentados y desplegados, cubriendo los cinco bounded contexts definidos en la arquitectura DDD de AgroTrack: Identity, Farming, Soil Monitoring, Alerts y Support & Dashboard.

- **Sobre la documentación de servicios:** La documentación de los endpoints mediante OpenAPI/Swagger permitió establecer un contrato claro entre el Frontend Web Application y el Web Service, facilitando la integración entre ambas capas y la validación de los flujos de usuario.

- **Sobre la arquitectura backend:** La organización del backend por bounded contexts siguiendo Domain-Driven Design permitió mantener una separación clara de responsabilidades. El backend fue desplegado en Render con base de datos MySQL en Aiven, aplicando GitFlow y Conventional Commits para el control de versiones.

- **Sobre la validación con usuarios reales:** Las entrevistas de validación (Lucía Alarcón, Jorge Ramírez, Valeri Rojas, Christopher Mejía, Johan Contreras, Matías Carrillo) y la evaluación heurística, detalladas en la subsección anterior, permitieron confirmar el valor central de la propuesta e identificar dos brechas relevantes: mensajes de recomendación poco descriptivos y ausencia de métricas financieras para el segmento empresarial.

- **Sobre el avance funcional del producto:** El Sprint 3 permitió reemplazar los datos simulados del Frontend por servicios reales, aunque el backend aún exponía sus endpoints sin un mecanismo de autenticación real, una brecha que quedó identificada como prioridad para el Sprint 4.

#### **Sprint 4 – Módulo IAM y consolidación del backend**

- **Sobre la implementación del módulo IAM:** Se concluye que la incorporación del bounded context de Identity and Access Management permitió habilitar un mecanismo real de autenticación en AgroTrack mediante los endpoints `POST /authentication/sign-up` y `POST /authentication/sign-in` (Technical Stories TS32 y TS33), que retornan un token JWT y los roles derivados del plan contratado (`FARMER` para BASIC/PRO, `AGRICULTURAL_MANAGER` para ENTERPRISE), además de exponer el catálogo de roles mediante `GET /roles` (TS34).

- **Sobre la consolidación de endpoints pendientes:** El Sprint 4 cerró una brecha de diseño heredada del Sprint 3, en la que `POST /users` mezclaba la creación de credenciales con la gestión del perfil de negocio. Las Technical Stories TS35 y TS36 separaron explícitamente la credencial de acceso (IAM) del perfil de negocio (Users), y la TS37 generalizó la protección JWT a todos los endpoints bajo `/users/**`, cerrando el vector de acceso no autorizado por el cual, hasta ese momento, cualquier cliente podía consultar o modificar el perfil de otro usuario sin restricción alguna.

- **Sobre la arquitectura y seguridad del sistema:** La incorporación de Spring Security y de un `JwtAuthenticationFilter` en el backend permitió establecer una capa de seguridad transversal a los demás bounded contexts del sistema, correspondiente a la implementación de este Sprint. Esto es especialmente relevante para el segmento de empresarios agrícolas (Problem Statement 4), cuya disposición a adoptar la plataforma depende en parte de la confianza en que su información de producción y rentabilidad no sea accesible por terceros.

- **Conclusión general del proyecto:** Finalmente, se concluye que AgroTrack cuenta con una arquitectura full-stack funcional, donde la Landing Page, el Frontend Web Application y el Web Service trabajan de forma integrada sobre una base de datos MySQL en producción, protegida mediante autenticación JWT real. El trabajo desarrollado a lo largo de los cuatro sprints permitió validar el problema, estructurar la solución, materializar la experiencia de usuario y consolidar los servicios backend que la sustentan, incluyendo el cierre del ciclo de seguridad de acceso, estableciendo una base sólida para las recomendaciones de Roadmap presentadas a continuación.


<br>
<br> 

### Recomendaciones (Roadmap post-curso)

Dado que el Sprint 4 marca el cierre del trabajo final del curso, las siguientes recomendaciones se plantean como el **Roadmap post-curso** de AgroTrack, es decir, los pasos que la startup Andes Smart debería priorizar si decide continuar evolucionando el producto más allá del alcance académico entregado:

1. **Enriquecer las recomendaciones de riego y las alertas climáticas con mensajes accionables.** En lugar de mostrar únicamente un nivel ("bajo", "riesgo de helada"), incorporar una breve sugerencia de acción concreta (p. ej. "Riega hoy antes de las 10 a.m." o "Cubre los cultivos sensibles esta noche"). Esto responde directamente al Problema #2 identificado en la evaluación heurística y a lo señalado por Jorge Ramírez en la entrevista de validación.
2. **Verificar de forma exhaustiva la integración end-to-end del módulo IAM entregado en el Sprint 4 con el Web Application**, confirmando que el flujo de sign-up/sign-in reemplace por completo cualquier lógica de autenticación remanente basada en MockAPI de sprints anteriores, y que el token JWT emitido se propague correctamente en todas las llamadas protegidas hacia `/users/**`.
3. **Agregar tooltips y etiquetas de texto a los botones de acción** (editar, eliminar parcela) para resolver el Problema #4 de la evaluación heurística, mejorando la accesibilidad para usuarios con menor familiaridad tecnológica.
4. **Incorporar métricas financieras básicas en el dashboard del empresario agrícola** (costo por hectárea, margen estimado, comparación entre parcelas), dado que fue la brecha señalada de forma consistente por los cuatro empresarios entrevistados. Esto requiere extender el bounded context de Dashboard con nuevos agregados de costos, y probablemente un nuevo Epic dedicado a "Gestión de Costos e Inversión".
5. **Habilitar notificaciones fuera de la plataforma** (WhatsApp o SMS) para las alertas climáticas, tal como fue sugerido explícitamente por Jorge Ramírez, considerando que el segmento de agricultores pequeños no siempre tiene acceso constante a una computadora o a la aplicación.
6. **Diseñar y ejecutar una validación cuantitativa de los Hypothesis Statements** una vez la plataforma tenga usuarios reales usándola de forma continua, para medir los umbrales originalmente planteados (60% de consulta antes de regar, 50% de acción preventiva, etc.) y así cerrar el ciclo de Lean UX con evidencia dura y no solo cualitativa.
7. **Iniciar la integración de sensores IoT de humedad y temperatura**, tal como estaba previsto en la visión original de Andes Smart, para eliminar la dependencia del registro manual de datos del suelo y aumentar la precisión y frecuencia de las recomendaciones de riego.
8. **Evaluar la migración hacia una aplicación móvil nativa o PWA**, dado que varios agricultores entrevistados mencionaron el celular como su dispositivo principal, y una experiencia optimizada para móvil facilitaría la adopción en zonas rurales con conectividad limitada.
9. **Explorar alianzas institucionales** con el MIDAGRI y la ANA, como se planteó en el análisis competitivo (Capítulo II), para ganar acceso a una base de usuarios más amplia y reforzar la credibilidad de la plataforma ante agricultores tradicionalmente reacios a adoptar tecnología.

Estas recomendaciones buscan asegurar que las siguientes iteraciones de AgroTrack no solo continúen expandiendo la cobertura funcional del backend y frontend, sino que respondan directamente a los vacíos identificados durante la validación con usuarios reales, consolidando el producto como una solución confiable y efectivamente adoptada por agricultores pequeños y empresarios agrícolas del Perú.

---

## Video About-the-Team

En esta sección, el equipo presenta el Video About-the-Team, un recurso audiovisual diseñado para dar a conocer a los miembros fundadores de la startup **Andes Smart**, responsable del desarrollo de **AgroTrack**. El objetivo del video es generar confianza tanto a nivel técnico como profesional, mostrando a las personas detrás de la solución y destacando sus contribuciones dentro del proyecto.

Durante el video, cada integrante presenta su rol dentro del equipo, las responsabilidades asumidas durante el desarrollo y los aportes realizados en áreas como análisis, diseño, implementación, documentación y validación con usuarios. Asimismo, se muestra la forma en que el equipo trabajó de manera colaborativa para superar desafíos y alcanzar los objetivos planteados en cada sprint.

Finalmente, el material transmite la visión compartida de Andes Smart: impulsar la transformación digital del sector agrícola mediante AgroTrack, una plataforma inteligente que ayuda a pequeños y medianos agricultores a optimizar la gestión de sus cultivos, mejorar la toma de decisiones y aumentar la productividad de manera sostenible.

| **URL**        | **Inicio** | **Duración** |
|----------------|------------|--------------|
| https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQAnzAghm3OvSbTwzSgvdHzSAdNmZKDTy05qS8Njy7f2gEw?e=aYAcrB&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D  | 00:00      | 06:22 min    |

![Video About The Team](report/assets/about-the-team.png)

---

# Bibliografía

        Agroptima. (s.f.). Agroptima: Software de gestión agrícola.
Recuperado el 26 de abril de 2026, de https://www.agroptima.com

        CropX Technologies. (s.f.). CropX agronomic farm management
system. Recuperado el 26 de abril de 2026, de https://www.cropx.com

        Google. (s.f.). Google HTML/CSS style guide.
https://google.github.io/styleguide/htmlcssguide.html

        Google. (s.f.). Google JavaScript style guide.
https://google.github.io/styleguide/jsguide.html

        Gothelf, J., & Seiden, J. (2021). Lean UX: Creating great
products with agile teams (3rd ed.). O'Reilly Media.

        Instituto Nacional de Estadística e Informática. (2012). IV
Censo Nacional Agropecuario 2012. Ministerio de Agricultura y Riego del
Perú.
https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1087/index.htm

        MDN Web Docs. (s.f.). CSS: Cascading Style Sheets. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/CSS

        MDN Web Docs. (s.f.). HTML: HyperText Markup Language. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/HTML

        MDN Web Docs. (s.f.). JavaScript reference. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript

        Ministerio de Agricultura y Riego. (2023). Plan estratégico
sectorial multianual del Ministerio de Agricultura y Riego 2022--2030.
Gobierno del Perú. https://www.midagri.gob.pe

        SpecFlow. (s.f.). Gherkin conventions for readable
specifications.
https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/

        Trimble Inc. (s.f.). Trimble agriculture: Precision farming
solutions. Recuperado el 26 de abril de 2026, de
https://agriculture.trimble.com

        W3Schools. (s.f.). HTML style guide and coding conventions.
https://www.w3schools.com/html/html5_syntax.asp


# Anexos


### Repositorios de Código Fuente

| Recurso | Enlace |
|---------|--------|
| Organización GitHub – AgroTrack Project | https://github.com/AgroTrack-Project |
| Repositorio – Informe del Proyecto | https://github.com/AgroTrack-Project/report |
| Repositorio – Landing Page | https://github.com/AgroTrack-Project/Landing-Page |
| Repositorio – Frontend Web Application | https://github.com/AgroTrack-Project/web-Application |
| Repositorio – Backend Web Services | https://github.com/AgroTrack-Project/web-services |

### Productos Desplegados

| Producto | URL |
|---------|-----|
| Landing Page | https://agrotrack-project.github.io/Landing-Page/ |
| Frontend Web Application (Cloudflare Workers) | https://agro-track.vitaltrek.workers.dev/home | 
| Documentación interactiva API – Swagger UI | https://agotrack.onrender.com/api/v1/swagger-ui/index.html#/ |

### Gestión del Proyecto – Tableros Trello

| Sprint | Enlace |
|--------|--------|
| Sprint 1 – Landing Page | https://trello.com/invite/b/69ec6b9c1f448409979be07f/ATTI57cb684f86da5dce34b16c20796587777599AEFD/agrotrack-sprint-backlog-1 |
| Sprint 2 – Frontend Web Application | https://trello.com/invite/b/6a082c484e76c24a6bf159db/ATTIeacb888e3799fbf438b8caf8a0d78ced55CA92BA/agrotrack-sprint-backlog-2 |
| Sprint 3 – Backend Web Services | https://trello.com/invite/b/6a386dfb1297005b1b046b88/ATTIf29aeadd54f0dac60d77b9b1cc2cf2ce5B4F6107/agrotrack-sprint-3 |
| Sprint 4 – Backend Web Services (IAM) | https://trello.com/b/GAgdFmxb/agrotrack-sprint-4 |

### Videos del Proyecto

| Descripción | Enlace |
|-------------|--------|
| Video de demostración – Sprint 1 (Landing Page) | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQCHKXSXfiGjTKYe4gDB3oUZAWgYlplm50CGrMfFiBHi4aI?e=fnoiA6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |
| Video de demostración – Sprint 2 (Web Application) | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120011_upc_edu_pe/IQAICJzo_YiLQ7CqTCNRwBTEAXCtfrOV6VxiAqzsegC73xo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=fk0ICb |
| Video de demostración – Sprint 3 (Web Services API) | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202323350_upc_edu_pe/IQANSlaoHDAvRrqH_iFNWhu7AaJ-uZhcqpvZBazMZA5JOiE?e=HwAWli&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |
| Video de demostración – Sprint 4 (IAM / Web Services API) | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202324623_upc_edu_pe/IQBe2DaJnk2nRITEOF8NEWw1AUNSwXuPQMT2jwS22LQeqag?e=6vj60X&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |
| Video – Flujo del Prototipo (Prototype Walkthrough) | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a267_upc_edu_pe/IQBGdqAI0J_NR7IAsWPnBl3TAe0ieQNo8cg4MmurJ2Owfuc?e=2yMdi8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |
| Video About-the-Product | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a827_upc_edu_pe/IQCkTU4cm894R6fEo-t8pc4-AVTzMh-HlJTa9Be-ru6pf6E?e=My3Hvs&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |


