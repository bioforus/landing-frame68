# TranscriData · Landing (Frame 68)

Sitio estático listo para publicar.

## Estructura
- `index.html`
- `css/`, `js/`, `img/`, `assets/`

## Publicar con GitHub Pages (recomendado por simplicidad)
1. Sube este repositorio a tu cuenta de GitHub (puedes arrastrar los archivos desde el navegador).
2. Ve a **Settings → Pages**.
3. En **Build and deployment** elige: **Source: Deploy from a branch**.
4. **Branch: `main`** y **Folder: `/ (root)`**.
5. Guarda. En 1-2 minutos tendrás una URL del tipo `https://tuusuario.github.io/nombre-del-repo/`.

## Publicar con Netlify (desde GitHub)
1. En Netlify: **Add new site → Import from Git**.
2. Conecta con GitHub y selecciona este repositorio.
3. **Build command**: *déjalo vacío* (no hay build).
4. **Publish directory**: `/` (raíz del repo).
5. Deploy.

## Publicar con Vercel (desde GitHub)
1. En Vercel: **New Project → Import Git Repository**.
2. Selecciona este repo.
3. Framework: **Other** (estático).
4. **Build Command**: vacío. **Output directory**: `/`.
5. Deploy.

> Si quieres evitar que Google indexe el staging: añade en `index.html` `<meta name="robots" content="noindex,nofollow">` y mantenlo mientras sea staging.
