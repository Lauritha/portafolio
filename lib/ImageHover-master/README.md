# ImageHover

[Demostración](http://zkreations.github.io/ImageHover/). Iconos por [Freepik](http://www.freepik.com)

## Instalación

[Descargar](https://github.com/zkreations/ImageHover/archive/master.zip) e incluir arriba de `</head>` el codigo css.

```html
<link rel="stylesheet" href="image-hover.min.css"/>
```

Tambien tienes la opcion de extraer el codigo css solo del efecto que necesites desde `image-hover.css` (la version sin comprimir).

### Utilizar Image Hover

Solo tienes que agregar un contenedor para la imagen (recomiendo `<a href="">` por sentido comun), y agregar la class **ihover [efecto]**, reemplazando [efecto] por uno de los preestablecidos: **fade, up, bottom, left, right, circle, circle2, circle3**.

```html
<a class="ihover [efecto]" href="#pageUrl"><img src="img/img-01.jpg"/></a>
```

## Limitaciones

* No puedes agregar un grupo de imagenes dentro de un contenedor, cada imagen requiere un contenedor independiente.