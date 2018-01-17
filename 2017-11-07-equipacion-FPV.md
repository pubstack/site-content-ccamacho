---
layout: post
locale: es

title: "FPV, inmersión total en carreras de drones"

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
  - slider
  - post

main_pic: "assets/images_articles/ccamacho/images/fpv-equipment-00.jpg"

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

#WORDS: 1082
#PPW_EN: 0.005
#PPW_ES: 0.001
#TOTAL: 1.082
#TID: 64C204085P6882337
---

Una de las características que más les gusta a los pilotos
de carreras de drones, es contar con la posibilidad de sumergirse
completamente en la experiencia de vuelo, algo que logran a través
del equipo FPV (First Person View) o Vista en Primera Persona.
Se trata de un conjunto
de componentes que permiten a los pilotos sentir que van a dentro del
dron.

El equipo FPV es uno de los requisitos indispensables dentro del
mundo de las carreras de drones, ya que se trata del medio a
través del cual tanto el piloto como los miembros de su grupo
podrán visualizar el recorrido y dirigirse de forma óptima
durante todo el trayecto.

#### Componentes que integran el sistema FPV de los drones.

Los sistemas FPV están integrados por cuatro componentes indispensables,
los cuales se explicarán en detalle a continuación:

* **Cámara:**
La cámara es el dispositivo que captará las imágenes del recorrido
y las proyectará sobre los lentes o pantalla del piloto. Hoy en día
se utilizan tanto cámaras de tipo analógico como de tipo
digital, sin embargo, las más populares en el medio de las carreras
de drones son las analógicas. La razón
es que este tipo de equipo es que tiene menos latencia
en la transmisión del vídeo.
    <div class="nk-gap-1"></div>
    <div class="nk-post-text mt-0">
    <img style="height: 155px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/fpv-equipment-01.jpg" alt="">
    <p class="text-white">
    Para elegir la cámara 
    solo deberás prestar atención a un pequeño detalle, que es el
    relacionado con el número de líneas horizontales o TVL. 
    Este dato te indicará que tan buena será la resolución y calidad de
    la imagen proyectada por la cámara, ya que mientras más grande sea
    el número que acompaña a las siglas TVL, mejor será la transmisión.
    </p>
    </div>

* **Transmisor de vídeo (vídeo Tx):**
El transmisor de vídeo es el dispositivo encargado de enviar la
señal captada por la cámara hacia nuestra pantalla o lentes.
No se debe confundir esta señal con la de radio que se
encarga de dirigir al dron. La primera
solo se encarga de transmitir imágenes y la segunda de dirigir
al dron durante su recorrido, ambas señales viajan por
separado y se debe evitar a toda costa que 
interfieran entre sí.
    <div class="nk-gap-1"></div>
    <div class="nk-post-text mt-0">
    <img style="width: 350px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/fpv-equipment-02.jpg" alt="">
    <p class="text-white">
    Los transmisores de vídeo pueden trabajar en diferentes frecuencias,
    cada una de las cuales aportará una serie de ventajas y
    desventajas para el piloto, veamos cada
    una de ellas en detalle.
    </p>
    </div>
    - **Frecuencia de 900MHz:** Es la frecuencia más baja,
    por lo tanto es la que tiene mayor alcance y nivel de
    penetración cuando hay presencia de obstáculos.
    No obstante, también es la que posee la antena más
    grande y pesada y podría ser ilegal su uso en ciertos paises.
    - **Frecuencia de 1.3 GHz:** Para utilizar esta
    frecuencia es necesario poseer un permiso de
    frecuencia radiofónica, tal como ocurre con las emisoras radiales.
    - **Frecuencia de 2.4 GHz:** Esta es la
    frecuencia presente en las emisoras,
    por lo tanto no se aconseja que sea
    la frecuencia utilizada para las emisiones de vídeo,
    porque puede generar interferencias al momento de pilotar
    nuestro drone.
    - **Frecuencia de 5.8 GHz:** Es la frecuencia más alta de todas,
    esto le brinda ciertas limitaciones como menor alcance y
    problemas de transmisión cuando hay obstáculos en la vía.
    Pero también, resulta ser el equipo con las antenas más
    pequeñas y ligeras, por lo que presenta menos nivel de
    interferencias con las ondas que emite el quipo de la emisora,
    de allí que sea la frecuencia recomendada para el sistema
    FPV de tu dron de carreras.

* **Receptor de vídeo (Vídeo Rx):**
Es el encargado de recibir inalámbricamente la señal de vídeo
enviada por el transmisor, ambos deben trabajar en la misma
frecuencia, es decir, si el transmisor trabaja con una
frecuencia de 5.8 GHz el receptor también debe operar a
una frecuencia de 5.8 GHz, de lo contrario nuestro
sistema FPV no funcionará.
    <div class="nk-gap-1"></div>
    <div class="nk-post-text mt-0">
    <img style="height: 155px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/fpv-equipment-03.jpg" alt="">
    <p class="text-white">
    La parte más importante del receptor de vídeo es la antena,
    ya que dependiendo del modelo tendrán mayor o
    menor alcance.
    Aunque el tema de las antenas es bastante amplio, aquí solo
    hablaremos de los 4 modelos más comunes que se suelen
    encontrar en el mercado, los cuales son: 
    </p>
    </div>
    1. Antenas de polarización lineal omnidireccional.
    2. Antenas de polarización circular omnidireccional.
    3. Antenas de polarización lineal direccional.
    4. Antenas de polarización circular direccional.

    Las diferencias esenciales entre cada una de ellas son las siguientes.
    Las antenas direccionadas emiten su señal con mayor
    potencia en una dirección determinada y poseen mayor
    alcance de transmisión, por eso están pensadas para
    largas distancias. En cambio las omnidireccionales
    emiten la misma potencia en todas las direcciones y
    son más eficientes en distancias cortas.
    Cada tipo de antena viene calibrada para una frecuencia
    en concreto, así que es importante estar al tanto si son de 2.4
    GHz o 5.8GHz.

    Las antenas que suelen venir adheridas al transmisor.
    por lo general son de gama baja. Esto quiere decir que
    tanto calidad de la imagen como el alcance de la señal
    son de poca calidad. En consecuencia, es común que
    la mayoría de los pilotos las reemplacen
    por unas de mejor calidad.

* **Gafas o pantallas:**
Elegir entre gafas o pantallas, ya es una decisión de gusto
personal. Aunque la mayoría de los pilotos prefieren las
gafas porque les brindan un mayor nivel de inmersión en
la competencia, estas también resultan ser más costosas.
Si te estas iniciando en el mundo de las carreras de drones
puedes empezar con un monitor sin pantalla azul. La razón
de este consejo; es que si la señal es baja o de mala calidad,
esta no se pierda completamente y sea sustituida por un
rectángulo azul, sino que por el contrario se siga
captando el camino aún con interferencia.
    <div class="nk-gap-1"></div>
    <div class="nk-post-text mt-0">
    <img style="height: 155px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/fpv-equipment-04.jpg" alt="">
    <p class="text-white">
    Si deseas vivir la experiencia de las carreras de drondes
    en primera persona, puedes invertir un poco de tú dinero en unas
    gafas fatshark, las cuales son las mejores del mercado,
    en cuanto a señal y calidad de imagen.
    Para elegir el
    modelo que más se adapta a tus necesidades solo debes
    tomar en consideración dos factores esenciales:
    </p>
    </div>
    1. **El campo de visión o FOV**: Es el campo de visión que
    tendrán las gafas en ángulo horizontal, es decir, a mayor
    número de grados mayor será el tamaño de las imágenes
    captadas por las gafas. Lo recomendable es no comprar
    gafas con un FOV menor a 25 grados.

    2. **Resolución:** Se trata de la calidad de la imagen,
    por experiencia lo mejor es mantener la resolución del
    vídeo dentro de los parámetros estándar que traen las
    gafas desde la fábrica.

Que esperas para tener tu equipo de FPV y adentrarte en las carreras de drones!!!

