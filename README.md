# Batalla contra Sans

## Descripción

Este es un pequeño proyecto web en HTML, CSS y JavaScript que simula una escena de batalla contra Sans, inspirado en el videojuego *Undertale*. Al hacer clic en el botón **Iniciar Batalla**, se muestra un mensaje dramático, se reproduce música de fondo (como *Megalovania*) y la pantalla simula un pequeño temblor, recreando el ambiente tenso de un combate.

## Archivos incluidos

* `index.html` → El archivo principal de la página web.
* `imagenes/SANS.png` → La imagen de Sans que se mostrará en la batalla (asegúrate de tenerla en una carpeta llamada `imagenes`).
* `MEGALOVANIA.mp4` → El archivo de audio que se reproduce al iniciar la batalla (debe estar en la misma carpeta que el HTML, o ajusta la ruta si está en otra parte).

## Cómo usar

1. Asegúrate de tener todos los archivos mencionados (HTML, imagen y audio).
2. Abre el archivo `index.html` en tu navegador web.
3. Haz clic en **Iniciar Batalla** para ver la animación, los mensajes y escuchar la música.

## Notas importantes

* El archivo de música se llama `MEGALOVANIA.mp4` en el código, pero usualmente los navegadores manejan mejor formatos como `.mp3` o `.ogg`. Si tienes problemas para que el audio funcione, considera convertirlo a uno de esos formatos y actualiza la referencia en el código:

  ```html
  <audio id="battleMusic" src="MEGALOVANIA.mp3" preload="auto"></audio>
  ```

* Para que la imagen de Sans cargue correctamente, asegúrate de tenerla ubicada en la carpeta `imagenes` al lado del archivo HTML.

* El efecto de temblor es básico usando `translate`, pero puedes ajustarlo en el JavaScript si quieres un efecto más dramático (mayor desplazamiento, más repeticiones, etc.).

## Créditos

* Inspirado por *Undertale* de Toby Fox.
* Proyecto web sencillo para fines educativos o de diversión personal.
