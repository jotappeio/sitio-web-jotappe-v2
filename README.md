# Jotappe v2.0 — propuesta profesional (PDPP)

Desarrollo independiente de [jotappe.com](https://www.jotappe.com). Se tomó como referencia el prototipo Jotappe v2.0 y se preservaron las páginas existentes de cronometraje deportivo y resultados para revisión.

## Vista previa local
Ejecutar `python -m http.server 8000` en esta carpeta y abrir http://localhost:8000.

## Estructura
- `index.html`: presentación profesional, perfil integrador, áreas, trayectoria, formación, fotografía y contacto.
- `assets/site.css`: diseño adaptable verde natural (paleta inicial del prototipo).
- `cronometraje-deportivo.html`, `resultados.html`, `cronometraje/`: páginas históricas heredadas para pruebas, no revalidadas.
- `legal.html`, `404.html`, `vercel.json`: recursos auxiliares.

## Avisos importantes
- **Borrador en revisión**. No publicar en el dominio de producción sin autorización.
- La fotografía principal se sirve temporalmente desde el repositorio original mediante `raw.githubusercontent.com`; será sustituida por una copia WebP optimizada antes del despliegue definitivo. Esta dependencia de 17,7 MB debe resolverse.
- No se publica un CV descargable, ni perfiles privados ni documentación del proyecto.
- Las páginas históricas y sus scripts se conservaron, pero **no han pasado una prueba integral en navegador**.
- Se aplica `noindex` en la portada y `robots.txt` restrictivo durante el desarrollo. Antes de publicar, revisar canonical, sitemap, política de privacidad, Analytics y permisos del repositorio.
- Vercel aún no está conectado ni se ha verificado un despliegue.

## Pasos pendientes
1. Verificación visual en escritorio y móvil, navegación, recursos y páginas históricas.
2. Optimización y alojamiento local de la fotografía principal.
3. Revisión cromática (verde natural, grafito y verde, azul petróleo, claro) y accesibilidad.
4. Conexión a proyecto independiente de Vercel y revisión privada.
5. Autorización expresa antes de vincular el dominio público.
