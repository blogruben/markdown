# Imagenes

```
![Texto alternativo](/ruta/a/la/imagen.jpg){:class="img-responsive"}

![imagen google](/resources/google.png)
```

![imagen google](/resources/google.png)

# Imagen link a youtube

### Buscar imagen de video

Para hacer una imagen con link a un video de youtube, 
necesitamos sabe la ruta de la miniatura de la portada del video
vamos a ``https://thumbnailsave.com``, ponemos la url del video y nos dice 
donde esta el thumbnail para que los podamos usar como imagen link.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/3ZwHGekEtAs/sddefault.jpg)](https://www.youtube.com/watch?v=3ZwHGekEtAs&ab_channel=midulive)

# Placeholder Retina

![](filename.mp3)

```
!video[ title ]( url ){ size=10 }
!audio[ title ]( url ){ size=10 duration=10 cycle=forever }
!youtube[ title ]( url ){ size=10 cycle=forever }
```

Video link to a mp4 local

![](filename.mp4)

# Imagen

```md
Imagen con link: 
![Texto alternativo, si no  encuentra la imagen](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Texto al pasar el raton")
```

Imagen con link: 
![Texto alternativo, si no  encuentra la imagen](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Texto al pasar el raton")

# Gif


Tomar captura de la pantalla con ``https://www.screentogif.com/``



# Chapas

Escudo o shields es para mostrar metricas de github o otros servicios.

Para montar las URLs: [Shields.io](https://shields.io/)

Por ejemplo, navegamos a Download - GitHub all releases

```
https://img.shields.io/github/downloads/blogruben/Markdown/total
```

Se veria algo asi mostrando las descargas: ![GitHub all releases](https://img.shields.io/github/downloads/atom/atom/total) 

En mi caso no hay releases por lo que se veria asi ![GitHub all releases](https://img.shields.io/github/downloads/blogruben/Markdown/total) 


Si el repositorio esta mal se queda en estado de error ![GitHub all releases](https://img.shields.io/github/downloads/bloedgrube/Mardown/total)

