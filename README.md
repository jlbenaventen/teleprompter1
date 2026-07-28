# Teleprompter

Teleprompter web, de un solo archivo HTML, para usar con la cámara de tu computador. Corre 100% en el navegador: no requiere instalación, servidor ni conexión a internet una vez descargado.

## Características

- Editor de texto integrado (pega o escribe tu guion).
- Vista previa de tu cámara (webcam) con opción de espejo, para verte mientras lees.
- Grabación de video + audio (descarga un `.webm`/`.mp4` al detener), sin el texto superpuesto en el video final.
- Control de velocidad de scroll, tamaño de letra y ancho del texto (para reducir el movimiento lateral de los ojos).
- Línea guía central y control de oscurecimiento sobre la imagen de cámara para mejorar la legibilidad del texto.
- Modo espejo de texto (para teleprompters físicos con vidrio reflectante).
- Modo pantalla completa.

## Uso

1. Descarga `teleprompter.html` y ábrelo con Chrome o Edge (doble clic).
2. Pega tu guion en el cuadro de texto y presiona "Editar texto" para ocultarlo.
3. Presiona "Activar cámara" si quieres verte mientras lees.
4. Ajusta velocidad, tamaño de letra, ancho de texto y oscurecimiento a tu gusto.
5. Presiona "Play" para iniciar el scroll, o "Grabar" para grabar video + audio.

### Atajos de teclado

- `Espacio`: play / pausa
- `↑` / `↓`: aumentar / disminuir velocidad
- `C`: mostrar/ocultar controles
- `R`: reiniciar scroll

## Privacidad

Todo el procesamiento (cámara, micrófono, grabación) ocurre localmente en tu navegador. Nada se envía a ningún servidor.

## Compatibilidad

Probado en navegadores basados en Chromium (Chrome, Edge). El acceso a cámara/micrófono desde un archivo local (`file://`) generalmente funciona en estos navegadores, pero puede variar. Si tienes problemas, prueba sirviendo el archivo con un servidor local simple (por ejemplo `python -m http.server`) o publicándolo en GitHub Pages (que usa HTTPS).

## Licencia

MIT — ver [LICENSE](LICENSE).
