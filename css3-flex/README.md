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
podemos construirlo fácilmente añadiendo un contenedor **div** 
principal y otros 9 dentro de él. Para tener una visualización temporal en el sitio web, añadí 
números a cada contenedor interno y agregué algunas clases que serán útiles
al trabajar con los estilos:

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
    <div class="flexbox-container">
      <div class="box tl">1</div>
      <div class="box tc">2</div>
      <div class="box tr">3</div>
      <div class="box cl">4</div>
      <div class="box c">5</div>
      <div class="box cr">6</div>
      <div class="box bl">7</div>
      <div class="box bc">8</div>
      <div class="box br">9</div>
    </div>  
  </body>
</html>
```



## Añadiendo estilos con CSS

Una vez que tenemos lista nuestra estructura inicial, podemos agregar algo de estilos a nuestro diseño. Para
empezar, si abrimos la página web en su estado actual notaremos es imposible determinar dónde
termina un contenedor y termina el siguiente. 

``` css


```



## ¿Y ahora, cómo movemos el texto?
