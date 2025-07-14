# VerdeModa

**VerdeModa** es una interfaz web sencilla de moda sustentable a través de una estructura modular basada en la metodología BEM.

WIP
(ACTUALIZACIÓN V2 .- A la fecha, este repositorio cumple con los requerimientos hasta ABP4)
--

## 📁 Estructura del proyecto

proyecto-bem/
├── html/
│   ├── index.html
│   ├── catalog.html
│   ├── contact.html
│   ├── product.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   ├── img1.png
│   │   ├── favicon.png
│   │   ├── planta.jpg
│   │   ├── polera1.png
│   │   ├── totebag.jpg
│   │   ├── instagram.svg
│   │   └── facebook.svg
├── scss/
│   ├── style.scss
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   ├── _colors.scss
│   │   ├── _mixins.scss
│   │   └── _functions.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _responsive.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _hero.scss
│   │   ├── _footer.scss
│   │   └── _container.scss
│   ├── components/
│   │   ├── _buttons.scss
│   │   ├── _cards.scss
│   │   └── _form.scss
├── README.md

## 🔧 Tecnologías utilizadas

- HTML
- CSS3 con metodología BEM
- SASS con estructura modular
- Estructura de carpetas según patrón 7-1
- Aplicación del modelo de cajas de CSS
- Diseño responsivo

## 💻 Instalación y compilación

1. Clona el repositorio o descarga los archivos
2. Instala SASS si no lo tienes:

```bash
npm install -g sass 
```
3. En la terminal, ejecuta:

```
sass --watch scss/main.scss css/styles.css
```

4. Abre `html/index.html` en tu navegador para visualizar el sitio

---

Este proyecto es parte de una actividad educativa de TD
Bootcamp de Desarrollo de aplicaciones Front End Trainee 2025.