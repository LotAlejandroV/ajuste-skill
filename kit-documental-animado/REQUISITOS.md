# Requisitos · Documental animado

- **Claude:** Claude Code con un plan de pago (Pro o Max). Recomendado Max: Claude arma las escenas y revisa cuadro a cuadro.
- **Computadora:** Mac (chip Apple M1–M4 recomendado; también Intel). Windows 10/11: **preparado (auditado), falta probarlo en una PC**.
- **Memoria y disco:** 16 GB recomendados (8 GB con `--procesos 1`). ~6 GB libres (librerías + Whisper ~1.6 GB + navegador del motor ~0.3 GB).
- **Programas** (los instala Claude): Python 3.12 (o 3.11), ffmpeg, las librerías de `requirements.txt` y el navegador sin ventana de Playwright (Chromium).
- **Cuenta de pago:** ElevenLabs para la voz (plan Starter o superior para usar tu voz clonada). Medido: 226 caracteres por 12 s de video; un video de ~60 s gasta ~1,100. Tope por video: 2,500.
- **Tiempo de render:** medido en una Mac M4 Pro con 24 GB: ~30 s de render para 12 s de video a 60 fps (2 procesos, 30 cuadros/s), más ~1 min de voz y verificación. Lo más largo es que Claude arme y revise las escenas.
- **Lo que pones tú:** el tema (o tu guion). Fotos opcionales (libres o tuyas); sin fotos funciona con mapas, fechas y cifras. Música no hace falta.
