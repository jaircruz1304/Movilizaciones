# Changelog

## v2.0.0

- Carga directa de PDF GPS desde la plataforma hacia SharePoint.
- Administración GPS restringida a `jcruzg@fias.org.ec`.
- Lectura normal y escritura incremental para el administrador mediante MSAL.
- Automatización con GitHub Actions y Poppler.
- Procesamiento, validación, hash SHA-256 y deduplicación.
- Integración incremental de JSON mensuales.
- Auditoría de cargas, duplicados y rechazos.
- JSON GPS de producción movidos a SharePoint protegido; ya no se publican en GitHub Pages.
- Workflow de Pages separado del workflow de datos GPS.
- Modo claro/oscuro y diseño responsive.
- Logo oficial FIAS.
- Filtro por conductor.
- Comparación de períodos.
- Indicadores de horas de uso, vehículos y conductores activos.
- Exportación CSV, Excel y PDF.
- Panel de cola e historial para administración GPS.
- Parser validado con enero–julio 2026: **35.979 puntos GPS**.

- Reducción del permiso delegado de carga a `Files.ReadWrite` y heartbeat mensual no sensible para mantener activo el cron de GitHub Actions en repositorios públicos.
