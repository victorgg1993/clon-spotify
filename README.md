## Introducción

En este ejercicio vamos a construir una versión simplificada de la _landing page_ de Spotify:

![Spotify image](https://i.imgur.com/xVD0bm6.jpg)

<br>

Se proporcionan todas las imágenes necesarias, incluido un [documento con la copia completa del sitio web](./spotify-prototype.pdf)** como referencia.

## Requisitos

- Primero haz un _Fork_ de este repositorio
- Después clona __tu__ repositorio

## Entrega

Una vez que tengas el resultado:

```shell
$ git add .
$ git commit -m "done"
$ git push origin master
```
Envía la gh-page de tú repositorio vía slack(canal #ejercicios)

## Instrucciones

En la carpeta `images` se encuentran todas las imágenes necesarias.

Escribe el código HTML y CSS en los ficheros `index.html` y `styles/style.css`, respectivamente.

La página tiene 4 secciones, que te ayudarán a estructurar el HTML.

<br>

![](https://res.cloudinary.com/ihwebdeb/image/upload/v1571085836/Ironhack/spotify-prototype_1x_ahk8ep.jpg)

Iteraciones:

### Iteración 1: Navbar

- El navbar se posiciona en `position: fixed`.
- Alinea el logo a la izquierda y el `ul` con los links a la derecha, utiliza `float` or `flex`.

### Iteración 2: Imagen grande con texto

- Revisa [esta guía](https://css-tricks.com/centering-css-complete-guide/) para centrar elementos.

### Iteración 3: Sección "What is on Spotify"

- Observa cómo cada una de las cajas ocupa un 1/3 de su contenedor.

### Iteración 4: Sección verde

- Existen 2 secciones principales, un elemento que contiene el texto y otro con la imagen del reproductor de Spotify a la derecha.
- Posiciona el logo de Spotify con valor absoluto con respecto a su contenedor.
