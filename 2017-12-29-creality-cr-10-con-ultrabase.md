---
layout: post
locale: es

title: Ultrabase CR-10 Mini

# All content goes under this category in the URL to
# reference blog posts or news.
category: articles

# Tags for printing in the new.
tags:
#  - News
   - DIY
#  - Prototypes
   - Guides

# Where should we display this content
# Articles will show as a new,
# but if you want them on the slider
# add the slider location.
locations:
# - slider
  - post

main_pic: "assets/images_articles/ccamacho/images/cr-10_ultrabase_00.jpg"

author: Press
author_flickr_picid: 36411317561

gitlab_author_id: ccamacho

#####################
# Only change this
# to true when ready
# to be published
# This must be done
# only by the global
# admin
# Hide this posts
published: false
#####################

---

En el siguiente artículo adaptaremos una Anycubic Ultrabase a
un clon de la Creality CR-10 Mini.
La cama caliente que trae por defecto esta impresora 3D
es de una calidad regular/mala,
en este caso si queremos utilizarla hay que utilizar cinta de carrocero o
lacas para evitar que se adhieran las piezas.
El calentamiento es irregular y en algunos casos la base no es completamente plana
con lo que las piezas tienen a despegarse o a doblarse a medida que se enfría el filamento.
Por eso hemos decidido utilizar una cama caliente de considerable mejor calidad, con la
única desventaja que hemos perdido algunos centímetros cuadrados del área de impresión.

Comenzaremos este artículo con el siguiente disclaimer:
"Todo lo descrito aquí, es para propósitos informativos.
El autor ni el sitio web donde esté publicada esta información
no es ni se hará  responsable de cualquier accidente, error, daño, uso,
mal uso de la información presentada."
La persona que use esta información, es bajo su propio riesgo,
y asumirá cualquier consecuencia y responsabilidad";
"El autor no es responsable del uso ilegal de esta información";
"Cualquier copyright, o propiedad intelectual es propiedad de su propietario".

### Lista de materiales

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_01.jpg" alt="">
        <p class="text-white">
La lista de compras de los componentes que necesitaremos antes de llevar a cabo
este tutorial DIY estará compuesta principalmente por tornillos,
muelles, arandelas, tuercas y conectores de energía para nuestra cama caliente.
Todos estos disponibles fácilmente en grandes superficies.
</p>

<p>
Como comentamos anteriormente, todos los materiales para este tutorial pueden
ser encontrados fácilmente en tiendas no especializadas.
En nuestro caso y para España, hemos conseguido los materiales en
las siguientes grandes superficies, los muelles y arandelas cóncavas las hemos conseguido en el
Leroy Merlin, la tornillería (tornillos M4, tuercas autoblocantes, mariposas, arandelas en general)
podemos conseguirla a un buen precio en el Bricomart, el conector de 6 pines
lo hemos conseguido en Conectrol (Madrid) pero hemos pedido cualquier conector de 6 pines
disponible on lo cual podríamos utilizar cualquier otro.
</p>

</div>

Necesitaremos:

- Una (1) cama caliente Anycubic Ultrabase.
- Cuatro (4) Muelles de 2cm de alto (Hemos comprado unos más largos y los hemos cortado a la medida necesaria).
- Cuatro (4) uniones lineales "conectores" de muebles de 4 huecos.
- Cuatro (4) tuercas autoblocantes M4.
- Cuatro (4) tornillos M4 cabeza plana de 4cm de largo.
- Ocho (8) arandelas cóncavas.
- Un (1) conector de 6 pines para la conexión eléctrica de la cama caliente.
- Un (1) rollo de cinta americana.

### Ensamblado

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_02.jpg" alt="">
        <p class="text-white">
Lo primero que haremos será presentar y soldar el conector de 6 pines tanto en la cama caliente como en la salida de
la controladora de la CR-10 Mini.
Es de vital importancia que los cables del conector que vamos a utilizar coincidan en el mismo orden que estaban anteriormente, es decir, que
el positivo coincida con el positivo de la cama caliente y el negativo de la misma manera,
la sonda para medir la temperatura de la cama caliente no tiene polaridad.
</p>
<p class="text-white">
Desde la unidad de control de la CR-10 podrán observar que el conector que sale a la cama caliente tiene 6 cables (2 rojos, 2 negros y 2 amarillos). 
En este caso, tanto como los negativos como los positivos salen del mismo puerto de la fuente de alimentación o MOSFET, con lo que solo utilizaremos
1 para cada uno de ellos (positivo y negativo) y dejaremos los otros 2 sin conectar.
Tanto la Creality CR-10 Mini como la Anycubic Ultrabase funcionan con 12V con lo que no tendremos
problemas de voltajes.
</p>
</div>

<br/>

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_022.jpg">

Podemos ver distintas vistas del conector de 6 pines, en este caso el conector que sale de la unidad de control
de la CR-10 Mini salen 6 cables (imagen derecha) y a la cama caliente solo van 4 (Imagen derecha y centro).
La conexión del sensor térmico no tiene polaridad, sin embargo para la cama caliente 
deberemos respetar la polaridad (no es necesario) por convención del cableado ya que está indicada en la leyenda
de la cama caliente.

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_03.jpg" alt="">
        <p class="text-white">
Seguidamente atornillaremos como se puede ver en la imagen, las uniones de 4 huecos, los tornillos M4, las tuercas autoblocantes M4, y los tornillos originales
de la Anycubic Ultrabase. El resultado final puede verse en la imagen a la izquierda.
</p>
<p class="text-white">
Es importante destacar que la orientación de las placas conectoras debe seguir la orientación que se ve en la imagen, de lo contrario no
coincidirán con los huecos de la base de la CR-10 Mini con los tornillos de la Ultrabase.
Es algo bueno en general, ya que tendremos dos huecos disponibles en la parte trasera de la cama caliente para adaptar quizá
un juego de luces LED o algún otro accesorio como por ejemplo una webcam
que queramos adaptar en esa parte. En futuros artículos adaptaremos un protector para el cable de la cama caliente a uno
de estos tornillos.
</p>
</div>

<br/>

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_033.jpg">

Podemos ver 3 vistas sobre cómo ensamblar la unión en la cama caliente, en este
caso el tornillo original de la Anycubic Ultrabase lo hemos recortado para que no moleste.
 
<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_04.jpg" alt="">
        <p class="text-white">
Una vez atornillada la base procederemos a presentar los muelles junto a la arandela cóncava.
</p>
<p class="text-white">
En este caso debemos
instalar todos los muelles en el mismo sentido, al recortar el tamaño del muelle podremos ver que hay un lado nivelado y otro no,
debemos dejarlos todos del mismo lado.
</p>

<p class="text-white">
La arandela cóncava nos permitirá eliminar el desnivel causado por el corte del muelle.
</p>
</div>


{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_044.jpg">

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_05.jpg" alt="">
        <p class="text-white">
Después utilizaremos cinta americana resistente al calor para dar un poco mas se sujeción a los tornillos originales de la Ultrabase.
En este caso la cinta que utilizamos soporta hasta 120 grados centígrados y es ignífuga con lo que no debería haber riesgo de incendio.
</p>


        <p class="text-white">
La cinta americana es un tipo de cinta adhesiva que se caracteriza por añadir
una malla de fibras naturales o sintéticas parecida a una venda como refuerzo.
El lado adhesivo es siempre de color blanco. El lado no adhesivo normalmente es
gris metálico, aunque se puede encontrar en negro. puede usar para unir o reparar
tubos flexibles, tapar rasgones en ropas, tiendas de campaña y velas de barco,
fijar tuberías provisionalmente, etc.
</p>


</div>

Procederemos a presentar la cama caliente con los soportes atornillados
y asegurados para un último ajuste y podremos ver que ajusta bastante
bien a las dimensiones de los huecos originales.

Aquí podremos ver una vista inferior sobre como queda la base ya instalada correctamente.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_066.jpg">

En caso de utilizar como base del proyecto una CR-10 de medidas estándar
(30cm x 30cm) hay disponible una Ultrabase con esas dimensiones, con lo que
habría que ver la cama caliente que mejor se adapte, en este caso la Keenovo
de 30cm x 30cm sería un acierto. Sin embargo, habría que probar distintas maneras
de adaptar las dimensiones de la cama caliente a la base de la CR-10.


