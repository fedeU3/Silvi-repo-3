# Wrapped 💚

Un "Spotify Wrapped" de la relación, en formato stories para celular, que termina con una invitación y un ticket descargable.

## Cómo editarlo

Todo se edita en el objeto `CONFIG` al principio del `<script>` en `index.html`:

- **Slides**: cada una tiene un `tipo` (`intro`, `numero`, `lista`, `foto`, `texto`, `resumen`, `pregunta`, `ticket`) y un color de `fondo`. Se pueden agregar, sacar o reordenar.
- **Fotos**: van en `images/` (por ejemplo `images/foto-1.jpg`). Si falta alguna, aparece un recuadro avisando.
- **Música** (opcional): poné un `music.mp3` al lado del `index.html`. Empieza a sonar cuando ella toca la primera pantalla.
- **Ticket**: fecha, hora, lugar y dress code del plan.

## Cómo se usa

- Tocar a la derecha → siguiente · tocar a la izquierda → anterior · mantener apretado → pausa.
- En la pregunta, el "No" se escapa y el "Sí" crece.
- "Guardar ticket" abre el menú de compartir del celular (o descarga un PNG en compu).

## Publicarlo

GitHub Pages: Settings → Pages → Deploy from branch → `main` → Save. Mandale el link.
