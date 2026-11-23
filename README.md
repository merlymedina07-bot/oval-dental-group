# Oval Dental Group — Sitio web

Sitio web de **Oval Dental Group**, clínica odontológica ubicada en **Bogotá, Colombia — Cra. 19A #79-18**.

Este repositorio contiene la **versión estática exportada** del sitio en vivo:
👉 https://ovalodontologia.abacusai.app

> Nota: es la versión compilada (HTML, CSS, JS, imágenes y videos), lista para servirse como sitio estático. No incluye el código fuente original en Next.js.

## Contenido

- `index.html` — página principal
- `politica-de-privacidad.html` — política de privacidad
- `tratamiento-de-datos.html` — política de tratamiento de datos
- `_next/` — recursos compilados (JS/CSS)
- `images/`, `videos/` — material multimedia
- `favicon.svg`, `robots.txt`
- `.nojekyll` — necesario para que GitHub Pages publique la carpeta `_next/`

## Cómo publicar con GitHub Pages

1. En el repositorio, ir a **Settings → Pages**.
2. En **Source**, elegir **Deploy from a branch**.
3. Seleccionar la rama **main** y la carpeta **/ (root)**, y pulsar **Save**.
4. En unos minutos el sitio quedará disponible en:
   `https://merlymedina07-bot.github.io/oval-dental-group/`

## Ver localmente

```bash
python3 -m http.server 8000
# luego abrir http://localhost:8000
```
