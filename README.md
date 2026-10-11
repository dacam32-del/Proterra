# TerrenoMatch

Micro-app web para **compra y venta de terrenos y propiedades** (local y nacional).

Diseñada para ser atractiva, con búsqueda inteligente (Match), filtros únicos y conexión directa entre compradores y vendedores.

## Características

- Búsqueda **Local / Nacional**
- **Match inteligente** (% de compatibilidad según tu propósito)
- Filtros avanzados: precio, superficie, tipo, características (suelo fértil, plusvalía, servicios, piscina, etc.)
- **Mapa interactivo** (Leaflet + OpenStreetMap) con marcadores que se actualizan con los filtros
- Alertas por email / WhatsApp (demo)
- Publicación de terrenos y propiedades
- Diseño optimizado para **celular** (navegación inferior, modales tipo bottom sheet, botones grandes)
- Animaciones suaves

## Tecnologías

- HTML + CSS + JavaScript (vanilla)
- Tailwind CSS (CDN)
- Font Awesome (CDN)
- Leaflet (mapa)

## Cómo usarla

1. Descarga o clona este repositorio.
2. Asegúrate de que estén todos los archivos de imagen (`.jpg`) en la misma carpeta que `terrenos-app.html`.
3. Abre `terrenos-app.html` en tu navegador.

### Publicarla en GitHub Pages

1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En *Source* selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos tendrás una URL pública como:
   `https://tuusuario.github.io/nombre-del-repo/terrenos-app.html`

## Archivos importantes

- `terrenos-app.html` → Aplicación principal
- Imágenes de ejemplo:
  - `campo-verde.jpg`
  - `lote-residencial.jpg`
  - `casa-moderna.jpg`
  - `propiedad-rural.jpg`
  - `casa-familiar.jpg`

## Notas

- Es una **demo estática**. Los datos de propiedades son de ejemplo.
- El sistema de Match, alertas y publicación funciona de forma simulada (ideal para prototipo o presentación).
- Puedes personalizar las ubicaciones, precios y características editando el array `listings` dentro del HTML.

---

Hecho con ❤️ para facilitar la compra y venta de terrenos y propiedades.
