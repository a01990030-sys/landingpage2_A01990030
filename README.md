# TΔLE — Thrust Aerospace Launch Engineering

Landing page estática de TΔLE con identidad visual espacial en tonos morados y dorados.

## Archivos

```text
TALE-GitHub/
├── index.html            # Página principal
├── README.md             # Este archivo
├── .nojekyll             # Evita procesamiento adicional de Jekyll
├── .gitignore            # Archivos locales que no se deben subir
└── assets/
    ├── tale-logo.webp    # Logotipo principal
    └── favicon.png       # Icono de la pestaña del navegador
```

## Visualizar localmente

No necesitas instalar nada. Abre `index.html` en tu navegador.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `tale-landing-page`.
2. Sube **todo el contenido** de esta carpeta, conservando la carpeta `assets`.
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. GitHub Pages publicará el sitio y mostrará la dirección en esa misma sección.

> Importante: `index.html` debe quedar en la raíz del repositorio. No subas solamente el HTML ni cambies de lugar la carpeta `assets`, porque el logotipo y el favicon se cargan desde ahí.

## Tecnologías

HTML y CSS integrados en `index.html`. No requiere Node.js, npm, frameworks, backend ni base de datos.
