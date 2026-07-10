#### 5.2.4.7. Software Deployment Evidence for Sprint Review.

En el transcurso del Sprint 4, el equipo verificó y actualizó el despliegue productivo del **Web Service de AgroTrack**, confirmando la estabilidad de la infraestructura configurada en sprints previos y aplicando los ajustes necesarios derivados de los nuevos endpoints implementados. Se mantuvo el uso de **Aiven** como proveedor de la base de datos MySQL y **Render** como plataforma de hosting del backend.

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

<br>