---
layout: post
locale: en

title: Ultrabase CR-10 Mini

# All content goes under this category in the URL to
# reference blog posts or news.
category: articles

# Tags for printing in the new.
tags:
#  - News
   - DIY
   - Prototypes
   - Guides

# Where should we display this content
# Articles will show as a new,
# but if you want them on the slider
# add the slider location.
locations:
  - slider
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
published: true
#####################

---

In the following article we will install an Anycubic Ultrabase to
a Creality CR-10 Mini clone.
The heated bed that this 3D printer has by default
it is a regular/bad quality heated bed.
In this case, if we want to use it, we must use tape or
lacquers to prevent the pieces from warping or sticking off.
The heating is irregular and in some cases the base is not completely flat
which will make the pieces to detach or bend as the filament cools.
That's why we decided to use a better heated bed of considerable better quality, with the
only disadvantage that we have lost a few square centimeters of the printing area.

We will start this article with the following disclaimer:
"Everything described here is for informational purposes.
The author or the website where this information is published
is not and will not be responsible for any accident, error, damage, use,
misuse of the information presented."
The person who uses this information is at its own risk,
and will assume any consequence and responsibility";
"The author is not responsible for the illegal use of this information";
"Any copyright, or intellectual property is the property of its owner."

### Materials list

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_01.jpg" alt="">
        <p class="text-white">
The purchases list of the components that we will need before carrying out
this DIY tutorial will be mainly composed of screws,
springs, washers, nuts and power connectors for our heated bed.
All these easily available on large hardware stores.
</p>

<p>
As we discussed earlier, all the materials for this tutorial can be
be easily found in non-specialized stores.
In our case and for Spain, we have obtained the materials in
the following large hardware stores, the springs and concave washers we have bought them in the
Leroy Merlin, the general hardware (M4 screws, self-locking nuts, butterflies, washers in general)
we can get it at a good price in the Bricomart, the 6-pin connector
we have bought it in Conectrol (Madrid) but we have ordered any 6-pin connector
available on which we could use any other.
</p>

</div>

We will need:

- One (1) Anycubic Ultrabase heated bed.
- Four (4) springs of 2cm high (We have bought some longer ones and we have cut them to the necessary lenght).
- Four (4) linear plates "connectors" for furniture with 4 holes.
- Four (4) M4 self-locking nuts.
- Four (4) M4 flat head screws 4cm long.
- Eight (8) concave washers.
- One (1) 6-pin connector for the electrical connection of the heated bed.
- One (1) roll of duck tape.

### Building it up

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_02.jpg" alt="">
        <p class="text-white">
The first thing we will do is present and weld the 6-pin connector both in the heated bed and in the output of
the controller of the CR-10 Mini.
It is of vital importance that the cables of the connector that we are going to use coincide in the same order as they were previously, that is, that
the positive coincides with the positive of the heated bed and the negative in the same way,
The probe to measure the temperature of the heated bed has no polarity.
</p>
<p class="text-white">
From the control unit of the CR-10 you can see that the connector that comes out to the heated bed has 6 cables (2 red, 2 black and 2 yellow).
In this case, as much as the negatives as the positives leave from the same port of the power supply or MOSFET, so forth, we will only use
1 for each of them (positive and negative) and leave the other 2 without connecting.
Both the Creality CR-10 Mini and the Anycubic Ultrabase work with 12V so we will not have any
voltage problems.
</p>
</div>

<br/>

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_022.jpg">

We can see different views of the 6-pin connector, in this case the connector that leaves the control unit
from the CR-10 Mini, 6 cables come out (right image) and only 4 go to the heated bed (right and center image).
The connection of the thermal sensor does not have polarity, however for the heated bed
we must respect the polarity (it is not necessary) by convention of the wiring, since it is indicated in the legend
of the heated bed.

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_03.jpg" alt="">
        <p class="text-white">
Next, we will screw as you can see in the image, the 4 holes plate, the M4 screws, the self-locking nuts M4, and the original screws
of the Anycubic Ultrabase. The final result can be seen in the image on the left.
</p>
<p class="text-white">
It is important to emphasize that the orientation of the connector plates must follow the orientation shown in the image, otherwise
they will not coincide with the holes of the base of the CR-10 Mini with the screws of the Ultrabase.
It's a good thing in general, since we'll have two holes available in the back of the heated bed to adapt maybe
a set of LED lights or some other accessory such as a webcam
that we want to adapt in that part. In future articles we will adapt a protector for the cable of the heated bed to one
of these screws.
</p>
</div>

<br/>

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_033.jpg">

We can see 3 views on how to assemble the plates in the heated bed, in this
If the original screw of the Anycubic Ultrabase has been trimmed so that it does not bother.
 
<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-right mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_04.jpg" alt="">
        <p class="text-white">
Once the base is bolted we will proceed to present the springs next to the concave washer.
</p>
<p class="text-white">
In this case we must
install all the springs in the same direction, by cutting the size of the spring we can see that there is one level and one not,
we must leave them all on the same side.
</p>

<p class="text-white">
The concave washer will allow us to eliminate the unevenness caused by the cutting of the spring.
</p>
</div>


{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_044.jpg">

<div class="nk-post-text mt-0">
    <img style="height: 255px;" class="pull-left mt-0" src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_05.jpg" alt="">
        <p class="text-white">
Then we will use heat-resistant duck tape to give a little more subjection to the original Ultrabase screws.
In this case the tape we use supports up to 120 degrees Celsius and is fire resistant so there should be no risk of fire.
</p>


        <p class="text-white">
Duck tape is a type of adhesive tape that is characterized by adding
a mesh of natural or synthetic fibers similar to a bandage as reinforcement.
The adhesive side is always white. The non-adhesive side is usually
metallic gray, although it can be found in black. Can use to join or repair
flexible tubes, covering tears in clothes, tents and boat sails,
temporarily fix pipes, etc.
</p>


</div>

We will proceed to present the heated bed with bolted supports
and insured for a final adjustment and we can see that it fits quite
well to the dimensions of the original holes.

Here we can see a bottom view on how the base is already installed correctly.

{:.nk-post-img}
<img src="/assets/images_articles/{{ page.gitlab_author_id }}/images/cr-10_ultrabase_066.jpg">

In case of using as a basis of the project a CR-10 of standard measures
(30cm x 30cm) there is an Ultrabase available with these dimensions, with which
you would have to see the heated bed that suits you best, in this case the Keenovo
30cm x 30cm would be a success. However, one should try different ways
to adapt the dimensions of the heated bed to the base of the CR-10.


