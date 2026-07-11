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
