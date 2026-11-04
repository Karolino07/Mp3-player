 
# Reproductor de música en HTML

Reproductor de música de código abierto que cabe en **un solo archivo HTML**, sin dependencias, sin servidor y sin subir nada a internet. Tus canciones se quedan en tu navegador.

## Características

- Carga de canciones arrastrando archivos o con el selector (mp3, ogg, wav, flac, m4a)
- Play/pausa, anterior, siguiente, aleatorio y repetir
- Barra de progreso y control de volumen
- Carátulas leídas de las etiquetas ID3 de los mp3
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

- Las carátulas solo se leen de mp3 con ID3v2.3 o v2.4.
- La playlist no se guarda al recargar la página.

## Ideas para contribuir

- Carátulas para M4A y FLAC
- Título y artista desde las etiquetas
- Guardar la playlist (IndexedDB)
- Versión PWA para instalar en el celular
- Temas y skins

## Música

Usa tus propios archivos o música con licencia libre (por ejemplo Jamendo o Free Music Archive). No subas canciones con derechos de autor al repositorio.

## Licencia

[MIT](LICENSE)
