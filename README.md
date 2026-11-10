# Sebastian Terleira — Portafolio

Portafolio personal de Sebastian Terleira, también conocido como Crazy Galanga. Presenta una introducción, proyectos web y enlaces de contacto en una página estática construida con HTML, CSS y Bootstrap.

## Sitio

URL propuesta para Vercel: <https://sebastian-portafolio-idat.vercel.app/>

## Secciones

- **Inicio** (`#home`): presentación y perfil.
- **Proyectos** (`#projects`): Brillaire, CarnesFrescas y Previta Care.
- **Contacto** (`#contact`): enlaces a GitHub y LinkedIn.

## Tecnologías

- HTML5
- CSS3
- Bootstrap 5.3.3, cargado desde jsDelivr con Subresource Integrity
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

`index.html` contiene las secciones del portafolio y carga Bootstrap y las hojas de estilo en el `<head>`. La navegación adaptable usa el componente Navbar de Bootstrap; los estilos propios están separados por sección dentro de `styles/`.

El proyecto utiliza el CDN de Bootstrap, por lo que requiere conexión a internet para cargar sus estilos y el menú desplegable en pantallas pequeñas. Las hojas CSS propias se cargan después de Bootstrap para conservar la personalización visual. Se incluyen animaciones CSS respetando la preferencia del usuario por movimiento reducido.

## Desarrollo local

Abre `index.html` directamente en un navegador o sirve la carpeta con cualquier servidor estático local. No se necesita un proceso de compilación.

## Sitemap

El sitemap XML está en [`sitemap.xml`](./sitemap.xml). Como el sitio es una página única, incluye la URL principal; las secciones internas se navegan mediante anclas y no son páginas independientes.
