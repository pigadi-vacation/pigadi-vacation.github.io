---
title: "Apartment for Rent"
permalink: /apartment
---

Apartment
====

The apartment is suitable for a maximum of 4 adults and 2 children. <a href="{{ site.url }}" style="float: right;">Back</a>

## General Information

### Rooms
* 1 bed room with a doble bed and 1 bunk bed
* 1 bed room with a double bed
* 1 bathroom
* 1 kitchen living
    * Fridge
    * Coffee machine
    * Water boiler
    * Sandwich toaster
    * Various utilities for cooking 
        * Cooking plates
        * Pans and pots
        * Tableware


### Entertainment & Outdoor
* WLAN included
* TV
* Garden furniture on the terrace

### Facilities
* Towels
* Bed linen
* Soap and toilet paper
* Clothes hanger
* Air conditioning
* Heating

### Safety
* Fire extinguisher
* First aid kit
* Smoke Detector

### Special Information for Families
* 1 travel bed for children

### Location
* Separate access to the apartment at ground level
* 80m to the harbor
* 200m to the free public beach

### Miscellaneous
* Long-term stays are possible
* No pets allowed
* Smoking prohibited
* No parties allowed


{% assign left = "apartment_couch.png, apartment_bath.png, apartment_kitchen.png" | split: ", " %}
{% assign right = "apartment_small_bed_room.png, apartment_large_bed_room_2.png, apartment_terrace.png" | split: ", " %}
<div class ="image-gallery">
{% for i in (0..2) %}
    <div class="box">
    <a href="{{ site.imagesurl }}{{ left[i] }}">
      <img width=200 height=200 src="{{ site.imagesurl }}{{ left[i] }}" alt="{{ left[i] }}"  class="img-gallery" />
    </a>
    <a href="{{ site.imagesurl }}{{ right[i] }}">
      <img width=200 height=200 src="{{ site.imagesurl }}{{ right[i] }}" alt="{{ right[i] }}"  class="img-gallery" />
    </a>
    </div>
 {% endfor %}
</div>
