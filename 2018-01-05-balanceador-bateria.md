---
layout: post
locale: es

title: Cargar baterías Li-Po de una manera segura y eficiente

# All content goes under this category in the URL to
# reference blog posts or news.
category: articles

# Tags for printing in the new.
tags:
#  - News
#  - DIY
#  - Prototypes
   - Guides

# Where should we display this content
# Articles will show as a new,
# but if you want them on the slider
# add the slider location.
locations:
# - slider
  - post

main_pic: "assets/images_articles/ccamacho/images/balancear-bateria.jpg"

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
published: true
#####################

---

En otras publicaciones ya hemos hablado sobre las baterías tipo LiPo, las 
cuales son la mejor alternativa para tus drones de carreras. Sin embargo, estas
mismas baterías resultan ser un tanto frágiles en cuanto a métodos de carga,
mantenimiento y almacenaje, ya que no se trata de una batería común que cuenta
con una sola pila de alimentación, por el contrario, las baterías tipo LiPo
están formadas por celdas de 3.7V altamente volátiles unidas en serie o en 
paralelo y hasta en ocasiones pueden estar unidas de forma mixta, es decir, 
tanto en serie como en paralelo. Esto quiere decir que una LiPo cuenta con 
tantas baterías como cantidad de celdas la compongan. 

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/diagrama.jpg">

El hecho de que una batería de este tipo, represente a varias baterías 
integradas unas con otras, brinda una serie de ventajas y desventajas que deben
tomarse en cuenta. Por ejemplo, las LiPo son mucho más ligeras y potentes que
una batería convencional. Pero esta misma potencia puede acarrear 
sobrecalentamientos o lo que es peor, una falla entre las cargas de la celda
que terminará por dañar la pila y en el peor de los casos también al aparato
conectado a ella, como puede ser el cargador o el drone. Para evitar que este
tipo de accidentes ocurra es necesario cargar por igual cada una de las células
y por ello necesitará un cargador de baterías LiPo con balanceador. 

### ¿Por qué es importante un cargador con balanceador?

Un cargador con balanceador es aquel que te permite saber cuándo cada celda de
tu batería se encuentra cargada al mismo nivel de voltaje que el resto. Esta
forma de calibrar la carga es considerada por muchos como un ajuste fino que
ayuda a alargar la vida útil de tu LiPo, pero también se trata de una medida de
seguridad importantísima que evita que tu pila pueda estallar o causar grandes
estragos. 

Lo primero que debes considerar es que el ciclo de carga de una batería LiPo,
consta de dos fases:

* En esta primera fase el cargador va a hacer circular toda la corriente que
pueda, dentro de los parámetros técnicos del mismo como salida de voltaje entre
otros, y va a ir monitoreando la tensión de la batería cuando se está cargando 
y cuando se encuentra en reposo, esto para evitar un sobrecalentamiento o 
subidón del voltaje. Llegado un cierto momento, la batería aún sin su carga 
completa va a llegar a un nivel que le avisará al cargador que ya está muy 
cerca del límite máximo, señal que dará inicio a la segunda fase.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/regulador.jpg">

* El cargador va a disminuir la intensidad de corriente que envía hacia la 
pila, esto lo hace porque ninguna de las celdas debe superar su capacidad 
máxima, que por lo general es de 4.2V, porque es cuando está cantidad se excede
que la pila tiende a explotar. Durante esta segunda fase el balanceador seguirá
monitoreando la batería al ser cargada y cuando está en reposo, cuando este 
último dato también indique una carga de 4.2V, tu pila estará cargada a su 
máxima capacidad.

Ahora bien, la única manera que tiene el cargador para saber en cada fase cuál
es la carga individual de cada celda y que estas sean exactamente iguales, es
con el cable balanceador. Porque no es lo mismo tener una batería de 2S o 2
celdas y que cada una de ellas este cargada con 4.2V para un total de 8.4V, a 
tener otra idéntica cuyas celdas estén cargadas con 4.1V y 4.3V respectivamente,
pues aunque sus cargas totales sean iguales, el exceso de carga en la celda de 
la segunda batería podría hacerla explotar. Y es está ligera diferencia la que 
el cable balanceador detecta con antelación, permitiéndonos abortar la recarga
de nuestra LiPo.

### ¿Cómo balancear las celdas de nuestra batería LiPo?

Existen dos formas de balancear una batería LiPo, una más engorrosa de la otra.
Aquí te hablaremos de la más sencilla y segura, que es donde intervienen los 
cargadores de LiPo balanceados. Existen muchos de estos artefactos en el
mercado pero uno de los más populares es el modelo iMax B6, el cual también
resulta ser uno de los más económicos con un costo aproximado de 22 dólares.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/imax.jpg">

El iMax B6 está pensado para baterías de hasta 6 celdas y puede alimentar una
corriente continua de 11 a 18V. Su modelo más básico no posee transformador
pero si cuenta con los cables necesarios para el proceso de carga. Para 
utilizarlo de manera segura solo debes seguir estos pocos pasos:

* Conecta el cargador al tomacorriente.

* Luego conecta los dos cables, tanto el de balanceo como el de carga a la 
batería LiPO, un vez que lo hayas hecho, oprime el botón que dice
<strong>BATT.TYPE</strong> hasta que la pantalla del cargador te muestre el 
siguiente mensaje:

<center><strong>PROGRAM SELECT</strong></center>
<center><strong>LIPO BATT</strong></center>

* Una vez leas el texto anterior es que debes pulsar el botón <strong>START</strong>
y seguidamente debes oprimir los controles de status que son los que dicen 
<strong>DESC.</strong> o <strong>INC.</strong> hasta que en la pantalla 
aparezcan los datos de la última recarga que se le hizo a la batería. Dichos
datos se muestran de la siguiente manera:

<center><strong>LIPO BALANCE</strong></center>
<center><strong>0.6 A 8.4V (2S)</strong></center>

* Luego presionamos <strong>START</strong> nuevamente y empezará a parpadear la
intensidad de carga, que en este ejemplo es el equivalente a 0.6 Amperios.

* Para establecer intensidad de carga deseada para tu batería debes presionar 
los botones <strong>DESC.</strong> o <strong>INC.</strong> tomando como 
referencia la mitad de la cantidad indicada de mAh, por ejemplo para una pila
de 1800 mAh la intensidad sería de 0.9 A y para una de 1600 mAh la intensidad 
adecuada es 0.8 A.

* Volvemos a oprimir el botón <strong>START</strong> para indicarle en esta 
ocasión el número de celdas que posee nuestra batería, aquí empezará a titilar
el dato de la pantalla que muestra el 8.4V, que es equivalente a 2 baterías.

* Nuevamente pulsamos <strong>DESC.</strong> o <strong>INC.</strong> para
establecer el número adecuado de celdas de nuestra LiPo, por ejemplo si se 
trata de una batería de tres celdas (3S) la cantidad adecuada sería
4.2V * 3 = 12.6V

* Pulsamos <strong>START</strong> y esperamos hasta que el cargador pite 
mostrando en la pantalla el siguiente mensaje:

<center><strong>BATTERY CHECK</strong></center>
<center><strong>WAIT...</strong></center>

De inmediato el mensaje cambiará al siguiente:

<center><strong>R: 3SER S: 3SER</strong></center>
<center><strong>CONFIRM(ENTER)/CANCEL(STOP)</strong></center>

Este último mensaje quiere decir que es aparato detectó 3 celdas (R) y que 
nosotros efectivamente le indicamos que eran 3 celdas (S), como el mensaje es
correcto pulsamos una vez más <strong>START</strong> y listo, nuestra batería 
se empezará a cargar de manera balanceada. En caso contrario, en que la R y la
S no sean iguales debes cancelar todo el proceso oprimiendo el botón 
<strong>BATT.TYPE</strong> 

Es importante que tengas en cuenta que el cargador nunca iniciará el proceso 
si el número de celdas no coincide con las que le hemos indicado. 



