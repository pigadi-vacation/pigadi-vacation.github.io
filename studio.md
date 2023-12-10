---
title: "Studio for Rent"
permalink: /studio
---


Studio
====
The studio is well-suited for 2 people and close to the beach. <a href="{{ site.url }}" style="float: right;">Back</a>

### Rooms
* Studio containing
    * 1 double bed
    * Living room area with a couch and TV
    * Kitchen
        * Fridge
        * French press (coffee)
        * Water boiler
        * Sandwich toaster
        * Various utilities for cooking 
            * Stove with oven
            * Pans and pots
            * Tableware
* 1 bath room

### Outdoor
Garden furniture on the large balcony

### Entertainment
* WLAN included
* TV

### Facilities
* Towels
* bed linen
* Soap and toilet paper
* Clothes hanger
* Air conditioning
* Heating

### Safety
* Fire extinguisher
* First aid kit
* Smoke Detector

### Location
* Separate access to the studio
* 80m to the harbor
* 200m to the free public beach

### Miscellaneous
* Long-term stays are possible
* No pets allowed
* Smoking prohibited
* No parties allowed


{% assign left = "studio.png, studio_living.png, studio_kitchen.png" | split: ", " %}
{% assign right = "studio_balcony.png, studio_bath.png, studio_bed.png" | split: ", " %}
<div class ="image-gallery">
{% for i in (0..2) %}
    <div class="box">
    <a href="{{ site.imagesurl }}{{ name }}">
      <img width=200 height=200 src="{{ site.imagesurl }}{{ left[i] }}" alt="{{ left[i] }}"  class="img-gallery" />
      <img width=200 height=200 src="{{ site.imagesurl }}{{ right[i] }}" alt="{{ right[i] }}"  class="img-gallery" />
     </a>
    </div>
 {% endfor %}
</div>
