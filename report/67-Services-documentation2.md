#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2 no se desplegaron Web Services propios (RESTful API), dado que el alcance del sprint estuvo centrado en la implementación del frontend de la Web Application. Para soportar el funcionamiento de la aplicación en producción, el equipo configuró un servidor MockAPI hospedado que actúa como API provisional, permitiendo que el frontend consuma datos estructurados mediante endpoints REST simulados.

A continuación se documentan los principales endpoints del servidor MockAPI que el frontend consume durante este sprint:

---

**Gestión de Usuarios y Planes**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/users` | GET | `GET /users` | Sin parámetros. | Retorna la lista de todos los usuarios registrados en la plataforma con su plan asignado y datos de perfil. | `{ "id": "1", "name": "Luis Quispe", "email": "luis@agrotrack.com", "planId": "2" }` |
| `/users/:id` | GET | `GET /users/{id}` | `id` (path, requerido): ID del usuario. | Retorna el detalle completo de un usuario específico, incluyendo su plan activo y datos de cuenta. | `{ "id": "1", "name": "Luis Quispe", "planId": "2", "createdAt": "2026-01-10" }` |
| `/users` | POST | `POST /users` | Body JSON requerido: `name`, `email`, `planId`. | Registra un nuevo usuario en la plataforma y retorna el objeto creado con su ID asignado. | `{ "id": "5", "name": "Ana Torres", "email": "ana@mail.com", "planId": "1" }` |
| `/plans` | GET | `GET /plans` | Sin parámetros. | Retorna los planes de suscripción definidos en el sistema con nombre, límite de parcelas y precio. | `{ "id": "2", "name": "Pro", "plotLimit": 10, "price": 49.9 }` |
| `/plans/:id` | GET | `GET /plans/{id}` | `id` (path, requerido): ID del plan. | Retorna el detalle de un plan específico, incluyendo sus características y límites operativos. | `{ "id": "1", "name": "Básico", "plotLimit": 3, "price": 0 }` |

---

**Configuración y Soporte**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/alert_preferences` | GET | `GET /alert_preferences?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna las preferencias de alertas climáticas configuradas por el usuario (canales de notificación, umbrales). | `{ "id": "1", "userId": "1", "email": true, "sms": false, "threshold": "high" }` |
| `/alert_preferences/:id` | PUT | `PUT /alert_preferences/{id}` | `id` (path, requerido). Body JSON: campos a actualizar (`email`, `sms`, `threshold`). | Actualiza las preferencias de notificación del usuario. Retorna el objeto actualizado. | `{ "id": "1", "userId": "1", "email": true, "sms": true }` |
| `/support_tickets` | GET | `GET /support_tickets?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna los tickets de soporte enviados por el usuario, con estado y fecha de creación. | `{ "id": "10", "userId": "1", "subject": "Error al registrar parcela", "status": "open", "createdAt": "2026-04-20" }` |
| `/support_tickets` | POST | `POST /support_tickets` | Body JSON requerido: `userId`, `subject`, `description`. | Crea un nuevo ticket de soporte y lo asocia al usuario. Retorna el objeto creado con ID asignado. | `{ "id": "11", "userId": "1", "subject": "Consulta sobre plan", "status": "open" }` |

---

**Gestión de Parcelas y Cultivos**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/plots` | GET | `GET /plots?userId={id}` | `userId` (query, recomendado): ID del usuario para filtrar parcelas. | Retorna la lista de parcelas del usuario con nombre, ubicación, tamaño en hectáreas y estado. | `{ "id": "101", "name": "Parcela Norte", "location": "Ica", "size_hectares": 5, "status": "active", "user_id": "1" }` |
| `/plots/:id` | GET | `GET /plots/{id}` | `id` (path, requerido): ID de la parcela. | Retorna el detalle completo de una parcela específica, incluyendo fecha de creación. | `{ "id": "101", "name": "Parcela Norte", "location": "Ica", "size_hectares": 5, "status": "active" }` |
| `/plots` | POST | `POST /plots` | Body JSON requerido: `id`, `name`, `location`, `size_hectares`, `status`, `user_id`, `created_at`. | Registra una nueva parcela asociada al usuario. Retorna el objeto creado con su ID asignado. | `{ "id": "105", "name": "Parcela Sur", "location": "Arequipa", "size_hectares": 3, "status": "active" }` |
| `/plots/:id` | PUT | `PUT /plots/{id}` | `id` (path, requerido). Body JSON: campos a actualizar (`name`, `location`, `status`). | Actualiza los datos o estado de una parcela existente. Retorna el objeto actualizado completo. | `{ "id": "101", "name": "Parcela Norte Actualizada", "status": "inactive" }` |
| `/plots/:id` | DELETE | `DELETE /plots/{id}` | `id` (path, requerido): ID de la parcela a eliminar. | Elimina una parcela del sistema. Retorna el objeto eliminado como confirmación. | `{ "id": "101", "name": "Parcela Norte" }` |
| `/crops` | GET | `GET /crops?plotId={id}` | `plotId` (query, recomendado): ID de la parcela para filtrar cultivos. | Retorna la lista de cultivos registrados en una parcela con tipo, fechas y estado. | `{ "id": "201", "type": "Uva", "sowing_date": "2026-01-15", "harvest_date": "2026-06-20", "status": "growing", "plot_id": "101" }` |
| `/crops/:id` | GET | `GET /crops/{id}` | `id` (path, requerido): ID del cultivo. | Retorna el detalle completo de un cultivo específico vinculado a su parcela. | `{ "id": "201", "type": "Uva", "sowing_date": "2026-01-15", "status": "growing" }` |
| `/crops` | POST | `POST /crops` | Body JSON requerido: `id`, `type`, `sowing_date`, `harvest_date`, `status`, `plot_id`. | Registra un nuevo cultivo y lo vincula a la parcela indicada. Retorna el objeto creado. | `{ "id": "208", "type": "Espárrago", "sowing_date": "2026-03-01", "status": "growing", "plot_id": "101" }` |
| `/crops/:id` | PUT | `PUT /crops/{id}` | `id` (path, requerido). Body JSON: campos a actualizar (`type`, `status`, `harvest_date`). | Actualiza los datos de un cultivo existente. Retorna el objeto actualizado completo. | `{ "id": "201", "type": "Uva", "status": "harvested", "harvest_date": "2026-06-18" }` |
| `/crops/:id` | DELETE | `DELETE /crops/{id}` | `id` (path, requerido): ID del cultivo a eliminar. | Elimina un cultivo del sistema. Retorna el objeto eliminado como confirmación. | `{ "id": "201", "type": "Uva", "plot_id": "101" }` |

---

**Monitoreo del Suelo e Irrigación**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/soil_records` | GET | `GET /soil_records?plotId={id}` | `plotId` (query, recomendado): ID de la parcela. Sin parámetro retorna todos los registros. | Retorna los registros de humedad y temperatura del suelo de una parcela, ordenados por fecha descendente. | `{ "id": "301", "plotId": "101", "humidity": 62, "temperature": 18.5, "recordedAt": "2026-05-10T08:00:00" }` |
| `/soil_records` | POST | `POST /soil_records` | Body JSON requerido: `plotId`, `humidity`, `temperature`, `recordedAt`. | Registra una nueva medición del estado del suelo de una parcela. Retorna el objeto creado. | `{ "id": "310", "plotId": "101", "humidity": 55, "temperature": 20.1, "recordedAt": "2026-05-14T09:30:00" }` |
| `/irrigation_recommendations` | GET | `GET /irrigation_recommendations?plotId={id}` | `plotId` (query, recomendado): ID de la parcela. | Retorna las recomendaciones de riego generadas para la parcela, con cantidad sugerida y justificación. | `{ "id": "401", "plotId": "101", "recommendedLiters": 200, "reason": "Humedad por debajo del 40%", "date": "2026-05-10" }` |
| `/irrigation_schedules` | GET | `GET /irrigation_schedules?plotId={id}` | `plotId` (query, recomendado): ID de la parcela. | Retorna los programas de riego planificados para la parcela con fecha, hora y estado de ejecución. | `{ "id": "501", "plotId": "101", "scheduledAt": "2026-05-15T06:00:00", "liters": 180, "status": "pending" }` |
| `/irrigation_schedules` | POST | `POST /irrigation_schedules` | Body JSON requerido: `plotId`, `scheduledAt`, `liters`. | Crea un nuevo programa de riego para la parcela indicada. Retorna el objeto creado con ID asignado. | `{ "id": "510", "plotId": "101", "scheduledAt": "2026-05-16T06:00:00", "liters": 200, "status": "pending" }` |
| `/irrigation_schedules/:id` | PUT | `PUT /irrigation_schedules/{id}` | `id` (path, requerido). Body JSON: campos a actualizar (`status`, `liters`). | Actualiza el estado o los parámetros de un programa de riego existente. | `{ "id": "501", "plotId": "101", "status": "completed" }` |

---

**Alertas Climáticas y Reportes**

| Endpoint | Verbo HTTP | Sintaxis de llamada | Parámetros | Descripción | Ejemplo de Response |
|---|---|---|---|---|---|
| `/climate_alerts` | GET | `GET /climate_alerts?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna las alertas climáticas activas y pasadas del usuario (heladas, sequías, lluvias extremas) con severidad y fecha. | `{ "id": "601", "userId": "1", "type": "frost", "severity": "high", "message": "Helada esperada esta noche en Ica", "issuedAt": "2026-05-13T18:00:00" }` |
| `/yield_summaries` | GET | `GET /yield_summaries?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna los resúmenes de rendimiento de producción por parcela y temporada para el dashboard del empresario agrícola. | `{ "id": "701", "userId": "1", "plotId": "101", "crop": "Uva", "yieldKg": 4200, "season": "2026-Q1" }` |
| `/loss_summaries` | GET | `GET /loss_summaries?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna los resúmenes de pérdidas registradas por parcela y temporada, incluyendo causa y porcentaje de pérdida. | `{ "id": "801", "userId": "1", "plotId": "101", "cause": "Helada", "lossPercentage": 12, "season": "2026-Q1" }` |
| `/water_consumptions` | GET | `GET /water_consumptions?userId={id}` | `userId` (query, recomendado): ID del usuario. | Retorna el historial de consumo de agua por parcela y temporada para análisis de eficiencia hídrica. | `{ "id": "901", "userId": "1", "plotId": "101", "liters": 12400, "season": "2026-Q1", "month": "Enero" }` |

---

**URL base del servidor MockAPI:** `https://6a02c43e0d92f63dd25406d7.mockapi.io/api/v1`

Commits relacionados con la configuración del servidor MockAPI y la integración del frontend:

| Commit ID | Descripción |
|---|---|
| `a3f2c91` | `feat(farming): implement plot and crop bounded context` |
| `b7e4d02` | `feat(farming): configure MockAPI environment and api endpoints` |
| `c1a8f53` | `feat(monitoring): implement soil records and irrigation services` |
| `d5b3e74` | `feat(alerts): implement climate alerts and notification preferences` |
| `e9c6a15` | `feat(analytics): implement yield, loss and water consumption summaries` |

La implementación formal del RESTful API con Spring Boot será abordada en el Sprint 3.
