# Sebastian Terleira — Portafolio

Portafolio personal de Sebastian Terleira, también conocido como Crazy Galanga. Presenta una introducción, proyectos web y enlaces de contacto en una página estática construida con HTML y CSS.

## Sitio

URL propuesta para Vercel: <https://sebastian-portafolio-idat.vercel.app/>

## Secciones

- **Inicio** (`#home`): presentación y perfil.
- **Proyectos** (`#projects`): Brillaire, CarnesFrescas y Previta Care.
- **Contacto** (`#contact`): enlaces a GitHub y LinkedIn.

## Tecnologías

- HTML5
- CSS3
- Vercel para el despliegue del sitio estático

## Estructura

```text
.
├── index.html
├── sitemap.xml
├── assets/
│   ├── logo/
│   └── projects/
└── styles/
    ├── GlobalStyles.css
    ├── contact.css
    ├── header.css
    ├── homeSection.css
    ├── index.css
    └── projects.css
```

`index.html` contiene las secciones del portafolio. `styles/index.css` importa los estilos globales y los estilos específicos del encabezado y de cada sección.

## Desarrollo local

Abre `index.html` directamente en un navegador o sirve la carpeta con cualquier servidor estático local. No se necesita un proceso de compilación.

## Sitemap

El sitemap XML está en [`sitemap.xml`](./sitemap.xml). Como el sitio es una página única, incluye la URL principal; las secciones internas se navegan mediante anclas y no son páginas independientes.
