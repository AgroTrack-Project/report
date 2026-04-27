# 5.1.3. Source Code Style Guide & Coding Conventions
 
El equipo de AgroTrack adopta las siguientes convenciones de código para garantizar consistencia, legibilidad y mantenibilidad en los repositorios del proyecto. Todos los identificadores, comentarios y documentación se redactan **en inglés**, sin excepción.
 
Para este primer avance, los lenguajes utilizados son HTML, CSS y JavaScript, correspondientes al desarrollo de la Landing Page.
 
---
 
**HTML**
 
Se adopta la **W3Schools HTML Style Guide and Coding Conventions** como referencia principal, complementada con la **Google HTML/CSS Style Guide**.
 
**Nomenclatura y estructura**
- Los nombres de archivos HTML van en `kebab-case`: `index.html`.
- Los atributos se escriben siempre en minúsculas: `class`, `id`, `href`, `src`, `type`, `aria-label`.
- Se usan comillas dobles para todos los valores de atributos: `class="site-header"`.
- La indentación es de **4 espacios**; no se usan tabulaciones.
- Se declara siempre el `DOCTYPE` y el atributo `lang` en la etiqueta `<html>`: `<html lang="en">`.
- Se usan elementos semánticos de HTML5 en lugar de `<div>` genéricos cuando corresponde: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- El atributo `alt` es obligatorio en todas las etiquetas `<img>`.
- Se evitan estilos en línea (`style="..."`); todo estilo va en la hoja CSS externa `css/style.css`.
- Los atributos de accesibilidad (`aria-label`, `aria-expanded`, `aria-controls`) se incluyen en todos los elementos interactivos.
- Los textos traducibles llevan el atributo `data-i18n` con su clave correspondiente para el sistema i18n.
- Los event listeners se declaran en el archivo `js/script.js`; no se usan atributos `onclick` en línea salvo en los botones que invocan funciones globales (`toggleLanguage`, `toggleMobileMenu`).
**Ejemplo — estructura base del proyecto:**
```html
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
 
**Ejemplo — sección con i18n y semántica correcta:**
```html
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
 
---
 
**CSS**
 
Se adopta la **Google HTML/CSS Style Guide** como referencia principal.
 
**Nomenclatura**
- Los selectores de clase usan `kebab-case`: `.site-header`, `.hero-section`, `.plan-card`, `.feature-card`.
- Los identificadores (`id`) se reservan para anclas de navegación y elementos únicos del DOM: `#features`, `#plans`, `#audience`, `#demo`, `#navCollapse`, `#fullName`, `#email`.
- No se usan estilos de `id` para reglas CSS generales; se prefieren clases.
- Los modificadores de estado o variante se nombran con doble guion BEM: `.plan-card--active`, `.hamburger-button.active`, `.nav-collapse.open`.
- Las variables CSS siguen el patrón `--descriptive-name` y se declaran en `:root`.
**Formato**
- Cada declaración en su propia línea, con punto y coma al final.
- Un espacio entre el selector y la llave de apertura `{`.
- Indentación de **4 espacios**.
- Las propiedades se ordenan siguiendo el criterio: posicionamiento → modelo de caja → tipografía → visual → miscelánea.
- El uso de `!important` se evita; si es necesario, se documenta con un comentario explicativo.
- Los colores, tamaños y espaciados reutilizables se definen como variables en `:root`.
**Variables globales (design tokens del proyecto):**
```css
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
 
**Ejemplo — navbar y header:**
```css
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
 
**Ejemplo — botones con estados:**
```css
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
 
**Ejemplo — hamburger menu con animación de estado activo:**
```css
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
 
**Responsive design — mobile-first con tres breakpoints:**
```css
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
 
---
 
**JavaScript**
 
Se adopta la **Google JavaScript Style Guide** como referencia principal.
 
**Nomenclatura**
- Variables y funciones: `camelCase` → `currentLanguage`, `toggleLanguage()`, `toggleMobileMenu()`.
- Constantes de datos: `camelCase` cuando es un objeto de configuración → `translation`.
- Archivos: `kebab-case` → `script.js`.
**Convenciones generales**
- Se usa `let` para variables que cambian de valor (como `currentLanguage`) y `const` para datos que no se reasignan (como el objeto `translation`).
- Se usan funciones declaradas con `function` para las funciones globales invocadas desde el HTML (`toggleLanguage`, `toggleMobileMenu`).
- Las funciones se documentan con JSDoc indicando tipo de parámetros y comportamiento.
- Los comentarios de bloque (`/** */`) se usan para describir el propósito de funciones y objetos complejos.
- Los comentarios en línea (`//`) explican el *por qué* de una decisión, no el *qué* hace el código.
- Los textos de la interfaz nunca se escriben directamente en JS; se gestionan exclusivamente a través del objeto `translation` usando claves `data-i18n`.
**Ejemplo — sistema de internacionalización (i18n):**
```javascript
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
 
**Ejemplo — menú hamburguesa con accesibilidad:**
```javascript
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