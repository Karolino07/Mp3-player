# Reproductor de música en HTML

Reproductor de música de código abierto que cabe en **un solo archivo HTML**, sin dependencias, sin servidor y sin subir nada a internet. Tus canciones se quedan en tu navegador.

## Características

- Carga de canciones arrastrando archivos o con el selector (mp3, ogg, wav, flac, m4a)
- Play/pausa, anterior, siguiente, aleatorio y repetir
- Barra de progreso y control de volumen
- Carátulas, título y artista leídos de las etiquetas ID3 de los mp3
- La playlist se guarda en el navegador (IndexedDB) y vuelve al recargar
- Controles en la pantalla de bloqueo y en las notificaciones (Media Session API)
- Visualizador de barras con la Web Audio API
- Atajos de teclado
- Tema claro u oscuro según el dispositivo

## Uso

Abre `index.html` en tu navegador, o publícalo con GitHub Pages
(*Settings → Pages → Deploy from a branch → main / root*).

## Atajos

| Tecla | Acción |
|-------|--------|
| Espacio | Play / pausa |
| N / P | Siguiente / anterior |
| S | Aleatorio |
| R | Repetir |
| ← / → | Retroceder / avanzar 5 s |

## Limitaciones conocidas

- Las etiquetas solo se leen de mp3 con ID3v2.3 o v2.4.
- La playlist guardada depende del espacio que deje el navegador; si es muy grande puede no guardarse.

## Ideas para contribuir

- Carátulas para M4A y FLAC
- Versión PWA para instalar en el celular
- Temas y skins

## Música

Usa tus propios archivos o música con licencia libre (por ejemplo Jamendo o Free Music Archive). No subas canciones con derechos de autor al repositorio.

## Licencia

[MIT](LICENSE)
