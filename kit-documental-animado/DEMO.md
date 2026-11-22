# Demo para la tarjeta del Arsenal · Documental animado

Clip vertical 1080×1920 (9:16) a 30 fps, de 7,5 s a partir de un tramo de 8 s, **sin sonido**, que se entiende de un vistazo y hace loop limpio (fundido de 0.5 s del final al inicio). No gasta voz:
sin `palabras.json` el motor usa tiempos de palabra inventados. Sin @, sin datos personales ni marcas de terceros.

Preparación (una vez): instala la skill siguiendo `documental-animado/INSTALAR.md` y define `PY` con el Python de su entorno (y corre una vez `$PY -m playwright install chromium`):
```
PY=~/.venvs/documental-animado/bin/python          # Windows (Git Bash): PY="$HOME/.venvs/documental-animado/Scripts/python.exe"
```

## Variante: documental vertical
- **Qué se ve:** 1914 que rueda en la regla de años, la cámara que vuela al istmo de Panamá con sus dos puertos y la cifra de 82 km con odómetro (9:16).
- **Guion:** el de `documental-animado/ejemplos/canal-de-panama/` (no hay que escribir nada).
- **Comando** (desde la carpeta donde descomprimiste el kit):
```
cp -R documental-animado/ejemplos/canal-de-panama demo-canal-de-panama
$PY documental-animado/motor/variantes/documental/motor.py demo-canal-de-panama prueba 4.0      # cuadro de control: demo-canal-de-panama/revision/prueba.jpg
$PY documental-animado/motor/variantes/documental/motor.py demo-canal-de-panama demo 0.0 8.0 demo-canal-de-panama.mp4
```
- **Respaldo:** si el clip no sale, pide al dueño del kit el tramo de su video terminado (se entrega aparte, fuera del zip).
