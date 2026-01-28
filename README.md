# Elite Café

Sitio estático (mobile / tablet / desktop) usando **Bootstrap 5** para la maquetación y **SCSS/SASS** para estilos propios.

## Estructura
- `index.html`
- `Pages/` (páginas internas)
- `Image/` (recursos)
- `scss/` (código SASS)
- `css/main.css` (CSS compilado desde SCSS)

## Compilar SASS
Requiere Node.js.

```bash
npm install
npx sass scss/main.scss css/main.css --no-source-map
```

> GitHub Pages no compila SCSS automáticamente: el sitio usa el CSS ya generado en `css/main.css`.

## GitHub Pages
En GitHub:
- **Settings → Pages → Deploy from branch**
- Branch: `main`
- Folder: `/ (root)`

Luego acceder desde la URL de Pages del repositorio.
