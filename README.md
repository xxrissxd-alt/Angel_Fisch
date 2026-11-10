# Fisch Guía
Compilar el APK (sin instalar nada): sube esta carpeta a un repo de GitHub → pestaña Actions → "Build APK" → descarga `fisch-guia-apk`.
Local: `npm i && npx cap add android && npx cap sync && npx cap open android`.
Actualización semanal: publica un `data.json` con la misma forma que `www/data.js` (objeto FISCH_DATA) y pega su URL en Novedades.
Pendiente: rellenar `req` (cañas/misiones previas) y `spots` con datos de fischipedia.org.
