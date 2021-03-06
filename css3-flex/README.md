# Reto #1: CSS3 Flex

El siguiente reto fue propuesto por [Michael](github.com/michael-saeek) en el grupo de
desarrolladores Full Stack de Discord. La propuesta es la siguiente:

*"Utilizando únicamente Flexbox en CSS3, generar el siguiente arreglo"*
![diseño propuesto](diseno.png)

## Iniciando el proyecto

Antes que nada, generé un nuevo proyecto de *html* al cual llamé **css3-flex** con una estructura similar
a la siguiente:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,
    initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Flex Sandbox</title>
  </head>
  
  <body>
  
  </body>
</html>
```

Ahora bien, el diseño sugerido es un contenedor que a su vez aloja 9 contenedores dentro de sí. Ésto
podemos resolverlo fácilmente añadiendo un contenedor **<div>** y los restantes dentro de éste:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,
    initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Flex Sandbox</title>
  </head>
  
  <body>
    <div>
      </div>1</div>
      </div>2</div>
      </div>3</div>
      </div>4</div>
      </div>5</div>
      </div>6</div>
      </div>7</div>
      </div>8</div>
      </div>9</div>
    </div>  
  </body>
</html>
```

## Añadiendo estilos con CSS

## ¿Y ahora, cómo movemos el texto?
