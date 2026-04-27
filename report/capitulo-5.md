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

![logo-figma](assets/logo-figma.webp)

*Nota.* Obtenido de:
https://www.iebschool.com/hub/wp-content/uploads/2024/01/s-1024x529-1-768x397.png

**HTML:** Es el lenguaje de marcado utilizado para definir la estructura
base de una página web. Permite organizar el contenido mediante
elementos como títulos, párrafos, imágenes, enlaces, formularios y
secciones, facilitando una correcta distribución de la información
dentro del sitio web.

**Figura 2**\
*Logo de HTML*

![logo-html](assets/logo-html.png)

*Nota.* Obtenido de:
<https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/250px-HTML5_logo_and_wordmark.svg.png>

**CSS:** Es un lenguaje de estilos empleado para personalizar la
apariencia visual de una página web. Permite modificar colores,
tipografías, tamaños, márgenes, posiciones y diseños responsivos,
logrando una presentación más atractiva y adaptable a distintos
dispositivos.

**Figura 3**\
*Logo de CSS*

![logo-css](assets/logo-css.png)

*Nota.* Obtenido de:
<https://lineadecodigo.com/wp-content/uploads/2014/04/css.png>

**JavaScript:** Es un lenguaje de programación orientado al desarrollo
web que permite incorporar dinamismo e interactividad en las páginas.
Gracias a JavaScript, es posible validar formularios, manipular
elementos del DOM, responder a eventos del usuario y mejorar la
experiencia general de navegación.

**Figura 4**\
*Logo de JavaScript*

![logo-javascript](assets/logo-javascript.png)

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

![logo-git](assets/logo-git.png)

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

![logo-github](assets/logo-github.jpg)

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
  https://github.com/Edu-VLL/AgroTrack.git
- Repositorio correspondiente a la landing page:
  https://github.com/AgroTrack-Project/Landing-Page.git

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

  -----------------------------------------------------------------------
  Verificación                        Detalle
  ----------------------------------- -----------------------------------
  Carga de assets                     Logo, imágenes de cultivo y fotos
                                      de testimonios visibles

  Navegación                          Links del navbar redirigen a las
                                      secciones correctas (`#features`,
                                      `#plans`, `#audience`, `#demo`)

  Toggle de idioma                    Cambia correctamente entre EN y ES
                                      en todos los textos con `data-i18n`

  Menú hamburguesa                    Se abre y cierra correctamente en
                                      móvil; desaparece en desktop

  Formulario de demo                  Los campos `fullName` y `email`
                                      tienen validación `required` activa

  Responsive                          Sin scroll horizontal en ningún
                                      breakpoint
  -----------------------------------------------------------------------

### 5.2.1 Sprint 1

El primer sprint se centrará en la implementación de las secciones de
Página de inicio, Servicios y Aplicaciones de AgroTrack. El objetivo es
crear una interfaz clara y funcional que presente la plataforma y sus
principales características a los agricultores y empresas agrícolas.

#### 5.2.1.1 Sprint Planning 1

Ahora, mostraremos nuestro sprint planning. En esta sección, vamos a
explicar la reunión inicial del sprint realizado, detallando lo que se
planeó, acordó y revisó en la reunión.

  ----------------------------------------------------------------------------------
  Sprint \#       Sprint 1
  --------------- ------------------------------------------------------------------
  Sprint Planning En el sprint decidimos reunirnos para verificar el progreso de
  Background      cada integrante y del proyecto desde el punto de vista grupal.
                  Luego de ello buscamos mejoras y nuevas acciones.

  Date            2025-04-18

  Time            21:05 PM

  Location        Google Meet Group Call

  Prepared By     Velasquez Laquihuanaco, Eduardo David

  Attendees       Martínez Gaona, Pablo Afranio `<br>`{=html} Quispe Perez, Eder Edu
                  `<br>`{=html} Rodriguez Rojas, Miler Alexander `<br>`{=html}
                  Alfaro Mallma, Alberto Joaquin

  Sprint Review   Revisamos nuestras metas del negocio, discutimos las user stories
  Summary         y dimos feedback. También revisamos riesgos futuros y el avance
                  individual y grupal.

  Sprint          **Start:** Debemos comunicarnos más entre nosotros. `<br>`{=html}
  Retrospective   **Continue:** Hacer preguntas al Product Owner. `<br>`{=html}
  Summary         **Stop:** Dejar tareas para último momento. `<br>`{=html}
                  **Continue:** Hacer preguntas al product owner hacer reuniones
                  interdiarias para priorizar el avance

  Sprint Goal &   
  User Stories    

  Spring n Goal   Our focus is on implementing the core functionalities of the
                  landing page and user registration module. We believe this
                  provides a clear access point and an organized onboarding
                  experience for farmers and agricultural businesses. This will be
                  validated when users are able to successfully enter the platform,
                  complete the registration process, and navigate smoothly to their
                  main dashboard to manage agricultural activities.

  Sprint n        4
  Velocity        

  Sum of Story    7
  Points          
  ----------------------------------------------------------------------------------

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

![Sprint Backlog 1](assets/sprint-backlog.png)

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

![landing page](assets/landing-page-en-web.png)

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

![Repo de la landing pade](assets/git-repo-laning-page.jpeg)

*Nota.* Elaboración propia.

**Figura**\
*Evidencia de deployment 2*

![Landing page en funcionamiento](assets/landing-page-en-web.png)

*Nota.* Elaboración propia.

#### 5.2.1.8 Team Collaboration Insights during Sprint

![contribucion del equipo](assets/team-contribution.png)

*Nota.* Elaboración propia.

# Conclusiones

El desarrollo de AgroTrack nos permitió entender con mayor claridad los
principales problemas que enfrentan los pequeños agricultores y
empresarios agrícolas en el Perú. Se evidenció que muchas de sus
decisiones todavía se basan en la experiencia o la intuición,
principalmente por la falta de herramientas digitales accesibles y de
información confiable para la gestión de sus cultivos. Esto termina
afectando directamente la productividad, el uso del agua y, en muchos
casos, las pérdidas económicas.

Durante el trabajo, el análisis de entrevistas, la revisión de
competidores y el uso de Lean UX nos ayudaron a confirmar que sí existe
una necesidad real por soluciones tecnológicas más simples y adaptadas
al contexto local. En ese sentido, AgroTrack surge como una alternativa
pensada para ser fácil de usar, accesible y útil desde el primer
momento, sin requerir conocimientos técnicos avanzados.

También fue importante el trabajo en equipo, ya que permitió organizar
mejor las ideas y darle forma a una propuesta más clara, alineada tanto
a lo que necesita el usuario como a los objetivos del proyecto. Esto
hizo posible construir una base sólida para el producto, sustentada en
información recogida directamente de los usuarios.

En general, se puede concluir que AgroTrack tiene potencial para generar
un impacto positivo en el sector agrícola, ayudando a mejorar la toma de
decisiones, optimizar recursos y hacer más eficiente el trabajo en el
campo. Sin embargo, su verdadero valor dependerá de seguir validándolo
con usuarios reales y de ir incorporando mejoras progresivas, como la
integración de sensores y datos en tiempo real.

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
