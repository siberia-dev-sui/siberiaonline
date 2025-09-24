# Siberia Online

Sitio web estático del proyecto "Siberia Online". Incluye páginas HTML, hojas de estilo CSS, recursos de imagenes y un script JS mínimo para interactividad.

## Requisitos

- Python 3 (para un servidor HTTP local rápido)
- Navegador web moderno

## Ejecutar en local

Desde la carpeta del proyecto:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Luego abre: `http://127.0.0.1:8000/`

## Estructura del proyecto

- `index.html`: página principal
- `portfolio.html`, `services.html`, `contact-us.html`, `case-studies/*.html`: páginas adicionales
- `css/`: estilos (`normalize.css`, `webflow.css`, `hugos-spectacular-site-2ba462.webflow.css`)
- `js/webflow.js`: scripts del sitio
- `images/`: recursos gráficos y assets

## Despliegue

El código vive en GitHub. Para publicar cambios:

```bash
git add -A
git commit -m "feat: descripción breve del cambio"
git push origin main
```

### GitHub Pages (opcional)

Si deseas publicar el sitio con GitHub Pages:

1. En GitHub, ve a Settings → Pages.
2. En "Build and deployment", elige "Deploy from a branch".
3. Selecciona la rama `main` y la carpeta `/root`.
4. Guarda. La URL quedará disponible tras unos minutos.

Repositorio: https://github.com/siberia-dev-sui/siberiaonline.git


