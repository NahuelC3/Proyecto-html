# Portafolio Personal — Nahuel Carbajal

Portafolio de Nahuel Carbajal, estudiante de desarrollo web. Sitio estático de 5 páginas,
desarrollado con HTML5 semántico, SCSS (arquitectura de partials) y Bootstrap 5, con
animaciones nativas y AOS, totalmente responsivo y optimizado para SEO.

## 🔗 Sitio en vivo
[Ver el sitio desplegado](https://proyecto-html-cyan.vercel.app/)

## 🛠️ Tecnologías
- HTML5 semántico
- SCSS (variables, mixins con parámetros, extend, partials, nesting)
- Bootstrap 5.3
- AOS (Animate On Scroll)
- Git y GitHub

## 📁 Estructura del proyecto
- index.html + pages/ (sobre-mi, proyectos, servicios, contacto)
- scss/ — código fuente de estilos (utilities, base, layout, components)
- styles/ — CSS compilado
- assets/ — imágenes del proyecto

## ⚙️ Cómo correr el proyecto localmente

Requisitos: [Node.js](https://nodejs.org/) (incluye npm).

1. Clonar el repositorio y entrar a la carpeta:
   ```bash
   git clone https://github.com/NahuelC3/Proyecto-html.git
   cd Proyecto-html
   ```
2. Instalar las dependencias de desarrollo:
   ```bash
   npm install
   ```
3. Compilar el SCSS a `styles/styles.css`:
   ```bash
   npm run build
   ```
   Para recompilar automáticamente al guardar cambios en `scss/`:
   ```bash
   npm run watch
   ```
4. Abrir `index.html` en el navegador. Se recomienda servirlo con un servidor local
   (por ejemplo la extensión Live Server de VS Code) para que la navegación entre
   `index.html` y las páginas de `pages/` funcione sin problemas de rutas.
