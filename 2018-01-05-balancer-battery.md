---
layout: post
locale: en

title: Charging Li-Po batteries safely and efficiently

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

In other publications we have already talked about LiPo type batteries, which 
are the best alternative for your racing drones. However, these same batteries
turn out to be somewhat fragile in terms of charging, maintenance and storage
methods, since it is not a common battery that has a single power supply cell;
on the contrary, LiPo batteries are formed by highly volatile 3.7V cells 
connected in series or in parallel and sometimes even in a mixed way, that is,
both in series and in parallel. This means that a LiPo has as many batteries as
there are cells in it. 

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/diagrama.jpg">

The fact that actually a battery of this type represents several batteries 
integrated with each other provides a series of advantages and disadvantages
that must be taken into account. For example, LiPo are much lighter and more 
powerful than a conventional battery. But this same power can lead to 
overheating or worse, a failure between the charges of the cell that will end
up damaging the battery and in the worst case, also to the device connected to 
it, such as the charger or the drone. To prevent this type of accident from
happening, it is necessary to charge each of the cells equally, and for this 
you will need a LiPo battery charger with balancer.

### Why is a charger with balancer important?

A charger with balancer is one that lets you know when each cell of your 
battery is charged to the same voltage level as the rest. This way of 
calibrating the charge is considered by many as a fine adjustment that helps
to extend the life of your LiPo, but it is also a very important safety measure
that prevents your battery from exploding or causing great damage.

The first thing to consider is that the charging cycle of a LiPo battery 
consists of two phases:

* In this first phase the charger will circulate all the current that it can, 
within the technical parameters of It as voltage output among others, and will
keep monitoring the tension of the battery when it is charging and when it is 
at rest, this to avoid overheating or voltage overcharge. After a certain time,
the battery still without its full charge will reach a level that will notify 
the charger that it is already very close to the maximum limit, signal that 
will start the second phase.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/regulador.jpg">

* The charger will decrease the intensity of current that it sends to the 
battery, this is because none of the cells must exceed its maximum capacity,
which is usually 4.2V, because it is when this amount exceeds that the battery
tends to explode. During this second phase the balancer will continue to 
monitor the battery when it is charged and when it is at rest, when this last
data also indicates a charge of 4.2V, your battery will be charged at its 
maximum capacity.

Now, the only way that the charger has to know in each phase which is the
individual charge of each cell and that these are exactly the same, is with the
balancing cable. Because it is not the same to have a 2S or 2 cell battery and
that each of them is charged with 4.2V for a total of 8.4V, to have another 
identical one whose cells are charged with 4.1V and 4.3V respectively, because
although their total charges are equal, the excess charge in the cell of the 
second battery could make it explode. And it is a slight difference that the
balancer cable detects in advance, allowing us to abort the recharging of our
LiPo. 

### How to balance the cells of our LiPo battery?

There are two ways to balance a LiPo battery, one more complicated than the
other. Here we will talk about the simplest and safest, which is where the 
balanced LiPo chargers intervene. There are many of these devices in the market
but one of the most popular is the iMax B6 model, which also turns out to be
one of the cheapest with an approximate cost of $ 22.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/imax.jpg">

The iMax B6 is designed for batteries of up to 6 cells and can supply a direct
current of 11 to 18V. Its most basic model does not have a transformer but it
does have the necessary cables for the charging process. To use it safely you
should only follow these few steps:

* Connect the charger to the outlet.

* Then connect the two cables, both the balancing one and charging one to the 
LiPo battery, once you have done that, press the button that 
says **BATT.TYPE** until the charger screen shows you the 
following message:

<center><strong>PROGRAM SELECT</strong></center>
<center><strong>LIPO BATT</strong></center>

* Once you read the previous text, you must press the <strong>START</strong>
button and then you must press the status controls that are the ones that say
**DESC.** or <strong>INC.</strong> until the screen shows the 
data of the last recharge that was made to the battery. These data are shown
as follows:

<center><strong>LIPO BALANCE</strong></center>
<center><strong>0.6 A 8.4V (2S)</strong></center>

* Then we press <strong>START</strong> again and the charge intensity will
begin to blink, which in this example is the equivalent of 0.6 Amperes.

* To set the desired charge intensity for your battery you must press the
<strong>DESC.</strong> or <strong>INC.</strong> buttons taking as a reference
half of the indicated amount of mAh, for example for a battery of 1800 mAh the
intensity would be 0.9 A and for one of 1600 mAh the appropriate intensity
is 0.8 A.

* We press the <strong>START</strong> button again  to indicate this time the
number of cells that our battery has, here will begin to blink the data of the
screen that shows the 8.4V, which is equivalent to 2 batteries.

* We press <strong>DESC.</strong> or <strong>INC.</strong> once more to 
establish the appropriate number of cells of our LiPo, for example if it is a
three-cell battery (3S) the appropriate amount would be 4.2V * 3 = 12.6V

* We press <strong>START</strong> and wait until the charger beeps showing the
following message on the screen:

<center><strong>BATTERY CHECK</strong></center>
<center><strong>WAIT...</strong></center>

To immediately change the text to the following:

<center><strong>R: 3SER S: 3SER</strong></center>
<center><strong>CONFIRM(ENTER)/CANCEL(STOP)</strong></center>

This last message means that the device detected 3 cells (R) and that we 
effectively indicated that they were 3 cells (S), as the message is correct, 
press once more <strong>START</strong> and ready, our battery will start 
charging in a balanced way . Otherwise, in which the R and the S are not 
equal you must cancel the whole process by pressing the 
<strong>BATT.TYPE</strong> button.

It is important that you bear in mind that the charger will never start the
process if the number of cells does not match the ones we have indicated.


