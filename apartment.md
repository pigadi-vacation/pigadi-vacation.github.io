---
title: "Apartment for Rent"
permalink: /apartment
---

Apartment
====

The apartment is suitable for a maximum of 4 adults and 2 children.

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



### Outdoor
Garden furniture on the terrace

### Entertainment
* WLAN included
* TV

### Facilities
* Towels
* bed linen
* Soap and toilet paper
* Clothes hangar
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


{% assign filenames = "apartment_couch.png, apartment_bath.png, apartment_kitchen.png, apartment_small_bed_room.png, apartment_large_bed_room_2.png, apartment_terrace.png" | split: ", " %}
<div class ="image-gallery">
{% for name in filenames %}
    <div class="box">
    <a href="{{ site.imagesurl }}{{ name }}">
      <img src="{{ site.imagesurl }}{{ name }} " alt="{{ name }}"  class="img-gallery" />
     </a>
    </div>
 {% endfor %}
</div>
