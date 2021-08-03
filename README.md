# Proyecto grupal módulo-1  Contact us by DIV-as

Este repositorio recoge el proyecto grupal del módulo 1 del curso intensivo de programación front-end impartido en Adalab. El curso está enfocado a mujeres sin conocimientos previos de programación. <br>
En este proyecto hemos desarrollado nuestra primera web colaborativa. Para ello hemos creado una web con la información social de todos los miembros del equipo. ¡Esta ha sido nuestra primera experiencia de trabajo en equipo relacionada con programación!<br>
La web consta de varias páginas:
- una página principal (Home) con la información principal sobre el equipo.
- una página de contacto con un formulario para que puedan ponerse en contacto con nosotras.

El stack tecnológico aplicado en este repositorio es:

- Maquetación: HTML5, CSS3, Flexbox, CSS Grid, SASS, BEM.
- Manejo de Slack, GitHub, GitHub projects, VSCode, Gulp, Terminal, Zeplin.
- Experiencia en planificación y ejecución de proyectos bajo el marco de trabajo Scrum.

## Fases de proyecto:

### Primera. Versión móvil de la web
- Desarrollar la versión para móvil de la web (página principal) con HTML y CSS.
- Crear el contenido de la web: textos e imágenes.
- Crear la infraestructura necesaria: repositorio en GitHub y con acceso para todos los miembros del equipo.
- Publicar web en GitHub Pages.


### Segunda. Versión responsive de la web
- Hacer la web para el resto de tamaños de pantalla (tablet, desktop)

### Tercera. Mejora de tecnología
- Integración con gulp para automatización de tareas.
- Dividir HTML en partials.
- Pasar el CSS a Sass (también usando partials).
- Aplicar las técnicas avanzadas:
   - Grid en la sección de "quiénes somos"
   - Añadir animaciones y transiciones

### Cuarta. Formulario de contacto
- Realizar el formulario de contacto para todos los dispositivos.
- Hacer que funcione el envío usando el servicio formspree.io.

## Plantilla de proyecto utilizada: Adalab web starter kit

Plantilla creada en **node y gulp**. ¿Y qué es un Starter kit? Pues es una **plantilla de proyecto con funcionalidades preinstaladas y preconfiguradas**.

En el Kit hay 3 tipos de ficheros y carpetas:

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, CSS, JS...
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

## Guía de inicio rápido

> **NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) para trabajar con este Starter Kit:

### Pasos a seguir cada vez que queremos arrancar un proyecto desde cero:

1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

### Pasos para arrancar el proyecto:

Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que te pongas a programar.** Para ello ejecuta el comando:

```bash
npm start
```

Este comando:

- **Abre una ventana de Chrome y muestra tu página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **refresca tu página en Chrome**.
- También **procesa los ficheros** HTML, SASS / CSS y JS y los **genera y guarda en la carpeta `public/`**. Por ejemplo:
- Convierte los ficheros SASS en CSS.
- Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

## Estructura de carpetas

La estructura de carpetas tiene esta pinta:

```
src
 |─ html
 |   └─ partials
 ├─ images
 | 
 ├─ scss
 |  ├─ components
 |  ├─ core
 |  └─ layout
 └─ pages
 
```

