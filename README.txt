# Cátedra Sicómoro – URJC en Sistemas Complejos

Este paquete contiene una web estática lista para publicar.

## Contenido
- `index.html` (página principal con pestañas)
- `base_image.png` (imagen de cabecera)
- `urjc.png` (logo URJC)
- `logo_sicomoro.webp` (logo Fundación Sicómoro)

## Cómo publicarla (GitHub Pages)
1. Crea un repositorio nuevo en GitHub (por ejemplo `catedra-sicomoro`).
2. Sube estos archivos a la raíz del repo.
3. En **Settings → Pages**, elige **Deploy from a branch**, selecciona la rama (`main`) y carpeta `/root`.
4. Guarda y espera a que GitHub genere la URL.

> Para cambiar la imagen de portada, sustituye `base_image.png` por otra con el mismo nombre.
> Para cambiar colores, edita las variables CSS `--brand` (rojo URJC) y `--brand-2` (verde Sicómoro) en `index.html`.
