# Cambios de Claude en la demo pública

- **2026-10-10:** `index.html` se recompiló desde `SalusNatura/control_de_asistencia`, rama `claude/gallant-ritchie-pvsg1j` (incluye `main` hasta 5ece586). Se generó con `npm run build -w web` en modo demostración y se incrustaron el JS y el CSS en un único `index.html`. Novedades visibles: estado «Notificación pendiente», «Consolidada sin oposición», «Requiere revisión», y ya no se muestra «Rechazada» para estados desconocidos.
- Se verificó en Chromium que el archivo carga sin errores y muestra la tabla de la demostración.
- Detalle de los cambios en `docs/CAMBIOS_CLAUDE.md` del repositorio privado.
