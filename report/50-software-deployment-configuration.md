# 5.1.4. Software Deployment Configuration
 
Esta sección describe la configuración y los pasos necesarios para desplegar la Landing Page de AgroTrack a partir del repositorio de código fuente.
 
**Repositorio:** [https://github.com/agrotrack-project/Landing-Page](https://github.com/agrotrack-project/Landing-Page)  
**URL publicada:** [https://agrotrack-project.github.io/Landing-Page/](https://agrotrack-project.github.io/Landing-Page/)  
**Rama de producción:** `develop`
 
---
 
**Landing Page**
 
**Stack:** HTML5 + CSS3 + JavaScript vanilla  
**Plataforma de despliegue:** GitHub Pages
 
**Estructura del repositorio**
 
```
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
```
 
**Pasos de despliegue**
 
1. Confirmar que la rama `develop` contiene la versión estable de la Landing Page y que `index.html` se encuentra en la raíz del repositorio.
2. En el repositorio de GitHub, ir a **Settings → Pages**.
3. En la sección **Build and deployment**, configurar:
   - **Source:** Deploy from a branch
   - **Branch:** `develop`
   - **Folder:** `/ (root)`
4. Hacer clic en **Save**. GitHub Pages generará automáticamente la URL pública.
5. Esperar entre 1 y 2 minutos y verificar que la página carga correctamente en:
   `https://agrotrack-project.github.io/Landing-Page/`
6. Comprobar que el diseño responde correctamente en desktop (≥ 1025px), tablet (769–1024px) y móvil (≤ 768px).
7. Verificar que el toggle de idioma (EN | ES) funciona correctamente en todos los breakpoints.
### Actualizaciones posteriores
 
Cada `git push` a la rama `develop` desencadena un redespliegue automático en GitHub Pages. No se requiere ninguna acción manual adicional.
 
```bash
# Flujo estándar para publicar cambios
git add .
git commit -m "feat: update hero section copy"
git push origin develop
```
 
GitHub Pages tomará los nuevos archivos y publicará la versión actualizada en aproximadamente 1 minuto.
 
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