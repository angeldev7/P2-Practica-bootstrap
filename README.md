# Práctica Bootstrap 5 — Proyección Personal y Profesional

Sitio web de portafolio personal y proyección profesional desarrollado en tres etapas: primero con **HTML** semántico, luego con **CSS** para la presentación visual, y finalmente con **Bootstrap 5** para la página de proyección responsiva.

---

## Descripción general

Este proyecto contiene el portafolio web de **Angel Steven Rodriguez Chavez**, estudiante de Ingeniería en Tecnologías de la Información en la ESPE. Incluye las páginas trabajadas en prácticas anteriores (inicio, búsqueda, contacto, portafolio) y una nueva página de **proyección personal, académica y profesional** construida con Bootstrap 5.

La página de proyección (`pages/proyeccion.html`) presenta las metas, habilidades por desarrollar, certificaciones futuras y el rol profesional al que aspira el estudiante, utilizando componentes de Bootstrap con enfoque **Mobile First**.

---

## Tecnologías utilizadas

- **HTML5** (etiquetas semánticas: `header`, `nav`, `main`, `section`, `article`, `aside`, `figure`, `footer`)
- **CSS3** (estilos personalizados, Flexbox, media queries)
- **Bootstrap 5.3** (CDN — sin instalación local)
- **Font Awesome 6** (iconografía)
- **JavaScript** (Bootstrap Bundle + interacciones del modal)

---

## Estructura de carpetas

```text
P2-Practica-bootstrap/
│
├── index.html                       # Página principal del portafolio
├── README.md                        # Este archivo
├── informe.md                       # Informe de la práctica Bootstrap
│
├── css/                             # Hojas de estilo
│   ├── general.css                  # Estilos compartidos entre páginas
│   ├── index.css                    # Estilos para la página de inicio
│   ├── buscar.css                   # Estilos para la página de búsqueda
│   ├── contacto.css                 # Estilos para la página de contacto
│   ├── portafolio.css               # Estilos para el portafolio
│   └── proyeccion.css               # Personalización visual sobre Bootstrap
│
├── pages/                           # Páginas internas del sitio
│   ├── buscar.html                  # Simulación de buscador
│   ├── portafolio.html              # Portafolio personal
│   ├── proyeccion.html              # Página de proyección (Bootstrap 5)
│   └── cto/
│       └── contacto.html            # Formulario de contacto
│
├── img/                             # Imágenes del sitio
│   ├── mino.jpg                     # Foto del gato Mino
│   ├── mundito.ico                  # Ícono del sitio
│   ├── Currents.webp                # Imagen de álbum musical
│   ├── borderline-album.jpg         # Imagen de álbum musical
│   ├── MoureDev by Brais Moure.jpg  # Imagen de inspiración personal
│   └── espe/
│       └── imagenEjemploEspe.png    # Logo de la ESPE
│
├── audio/                           # Audio del sitio
│   └── audioEjemploA7X.mp3
│
└── video/                           # Videos del sitio
    ├── AsaMitaka.mp4
    └── videoEjemploDiagnostica.mp4
```

---

## Componentes Bootstrap utilizados (página de proyección)

| Categoría | Componentes |
|-----------|-------------|
| Layout | Navbar, Container, Grid system |
| Contenido | Cards, Accordion, Carousel, List group, Table |
| Interacción | Buttons, Modal, Forms, Collapse |
| Feedback | Alerts, Badges, Progress bars |
| Media | Images (`img-fluid`) |
| Utilidades | Spacing (`my-4`, `g-4`), Typography (`display-5`, `lead`), Responsive (`col-lg-8`) |

### Combinaciones de componentes

- **Acordeón + Carrusel:** metas a corto plazo con galería de imágenes.
- **Cards + Badges + Botones + Imagen:** perfil profesional futuro.
- **Grid + Cards responsivas:** sección de proyectos futuros.
- **Modal + Formulario:** plan de mejora personal.
- **Tabla + Progress bars:** habilidades por desarrollar.
- **List group + Secciones:** navegación lateral conectada al contenido.

---

## Instrucciones para visualizar el sitio

1. Clonar o descargar el repositorio.
2. Abrir `index.html` en el navegador, o usar Live Server en el puerto 5500.
3. Navegar a la página de **Proyección** desde el menú principal.
4. Probar la vista responsiva con las herramientas de desarrollo (F12 → modo dispositivo).

---

## Autor

- **Nombre:** Angel Steven Rodriguez Chavez
- **Institución:** Universidad de las Fuerzas Armadas ESPE
- **Semestre:** 4to Semestre
- **Carrera:** Ingeniería en Tecnologías de la Información
- **GitHub:** [angeldev7](https://github.com/angeldev7)

---

## Etapas del aprendizaje

| Etapa | Enfoque | Páginas |
|-------|---------|---------|
| 1 — HTML | Estructura semántica | index, buscar, contacto, portafolio |
| 2 — CSS | Presentación visual y responsividad | Estilos en css/ con media queries |
| 3 — Bootstrap | Framework responsivo Mobile First | proyeccion.html con Bootstrap 5 CDN |
