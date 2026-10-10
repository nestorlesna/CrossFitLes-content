# CrossFitLes-content

Contenido público de la app **CrossFit Les** (clases, ejercicios con sus SVG, catálogos y planes).
La app lo descarga desde *Configuración → Contenido online → Actualizar contenido*.

- `manifest.json`: versión del contenido (`contentVersion`) y hash. La app lo baja primero.
- `content/content.json`: todo el contenido. Lo genera la app con *Publicar contenido* (sólo en
  `npm run dev` en la PC del administrador). No editar a mano.

Para publicar: *Publicar contenido* en la app → `git add -A && git commit -m "contenido vN" && git push`.
