# Estefania Velasquez Vinces

Dashboard profesional público con filtros, certificados, CV y modo presentación.

## Publicación
GitHub Settings → Pages → Deploy from a branch → main → /docs → Save.

## Actualizaciones
Editar `docs/profile.json` para actualizar textos, experiencia y referencias a certificados. Sustituir `docs/CV-Estefania-Velasquez.pdf` para actualizar el CV descargable. Subir documentos públicos a `docs/certificados/` y agregar su referencia en profile.json. GitHub controla quién puede editar. No existe guardado desde el antiguo panel de administración en esta versión estática.

Para cambios de diseño: npm install y npm run build. Antes de compilar, sincronizar los datos de docs/profile.json y sus archivos hacia public/ para conservar las últimas ediciones.
