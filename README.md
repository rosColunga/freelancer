# Freelancer
##### Ejercicio de maquetación utilizando los fundamentos de HTML y CSS.

* **Srint 2** _Retos de código_

***

## Objetivo

El reto consiste en maquetar una replica de el sitio **Freelancer**, como se muestra a continuación:

![Freelancer Website](docs/fullpage.png)

## Descripción código HTML

* Dentro del archivo base `index.html` se enlaza dentro de la etiqueta <**head**> el vínculo al archivo de estilos `main.css`, las fuentes tipográficas *Montserrat* y *Lato* desde `Google Fonts`y el vínculo a las carpetas de tipografía iconográfica [Font Awesome](http://fontawesome.io/).

* Debajo a la misma altura de <**head**>, se coloca la etiqueta de estructura <**body**>, la cual contiene todo aquello que es visible dentro de la página web.

* Contenidas en <**body**> se encuentran *5 secciones* principales:
  1. <*nav*> Contine el menú de navegación dentro de la página, con dos elementos, uno situado a la derecha y otro a la izquierda

  2. <*section id="fs-container"*> Contiene todo aquello independiente al menú de navegación, pero que se muestra dentro de la primera pantalla, con elementos de texto e imagen centrados.

  3. <*section id="sc-container"*> Contenedor de la "segunda pantalla", dando scroll down en la web. En esta sección encontramos la galería de fotos del portafolio dentro de un *Grid* o retícula clase: "portfolio-gallery"

  4. <*section id="about-s"*> Tercera sección que contiene un texto a dos columnas y un botón para descargar el tema *Freelancer* para mostrar tu portafolio.

  5. <*section id="contact"*> Cuarta sección del documento (además del *nav*) en el cual se muestra un formulario elaborado a base de la etiqueta <*input*>, y la estructura de un botón para enviar los datos ingresados.

  6. <*footer class="footer"*> Combinación de texto con los datos de contacto e iconos obtenidos vía *Font Awesome* en 3 columnas; cerca del margen inferior una leyenda de Copyright.

* Para finalizar se cierran las etiquetas contenedoras: <*body*> y <*html*> de la estructura de nuestro archivo.



## Descripción código CSS
###### Dentro del archivo CSS se otorgan estilos a la estructura dada por el HTML

* Por medio del selector universal identificado por un asterisco, se le dan características a todo el documento. En este caso se indicó prescindir del *margen y padding* y que las propiedades *width, height, border y margin* sean las medidas incluídas solo en el contenido por medio de border-box.

* Se emplean clases reutilizables como *.float-right, .float-left, .to-uppercase*; donde podemos repetir la misma "función" para diferentes elementos dentro de la web, sin importar su ubicación.

* Al nombrar las *clases, id's, y elementos bloque o inline* del HTML, podemos modificar sus características. De esta manera definimos dentro de las 5 secciones, el tamaño, el color, familia de fuente, tamaño y fonde de todos los elementos dentro de las secciones de que consta la estructura.

* *:hover* nos permite manipular la reacción de un elemento al posicionar el cursor sobre de él. En el caso de las fotografías del portafolio se modifica la opacidad y en el caso de las redes sociales en el footer, cambiar el color de fondo con un efecto "retardado" de 3 segundos.

* Los colores son indicados con su valor Hexadecimal, un código seguido de un símbolo de gato (#) que indica las cantidades tonales en una escala del "0" al "9" y a partir del "10" tomando valores de la "k" a la "l", para definir el color.


  > Nota: Ver resultado final en Github Projects de este repositorio
