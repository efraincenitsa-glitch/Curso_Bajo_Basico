# Aprende Bajo – Pack 2024 (JEA, notas en español)

Incluye:
- `index.html` con nombres de notas en **español** (Do, Re, Mi, Fa, Sol, La, Si). Toggle para ♯/♭ afecta la visualización.
- Iconos con **silhueta de bajo al fondo** y tus iniciales **JEA** al frente: `icon-1024.png`, `apple-touch-icon.png`, `android-chrome-192x192.png`, `android-chrome-512x512.png`, `maskable-512x512.png`, `favicon-32x32.png`, `favicon-16x16.png`.
- `manifest.webmanifest` y `safari-pinned-tab.svg`.

## Publicar en GitHub Pages
1. Crea un repositorio (p. ej. `aprende-bajo-es`).
2. Sube todos los archivos de esta carpeta a `main`.
3. Settings → Pages → Source: *Deploy from a branch* → `main` → `/root` → Save.
4. Abre la URL en **Safari (iPhone)** → Compartir → **Añadir a pantalla de inicio**.

## Notas
- El Service Worker se registra en la primera visita y permite uso **offline**.
- La afinación y el audio usan letras (E, A, D, G) internamente, pero todo lo mostrado en el diapasón y selectores usa **Do‑Re‑Mi**.
- En “Patrones/Canciones” puedes escribir notas tanto en español (Mi, Fa#, Mib...) como en inglés (E, F#, Eb...).
