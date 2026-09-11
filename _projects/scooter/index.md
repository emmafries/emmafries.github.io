---
layout: post
title: Medical Knee Scooter
description: Create a knee scooter to assist those with foot/ankle injuries


skills: 
- SolidWorks
- Solidworks FEA 
main-image: /scootbackground2.jpeg
---

---

## Goals
- Design and fabricate the scooter to handle the weight of the designated rider, maneuver easily, and be used on many road applications

---

## How
- Modeled the scooter in solidworks using the characteristics of PVC piping that will be used in construction

<div style="text-align: center;">
    <span style="font-size: 15px">SolidWorks Scooter Assembly</span>
</div>

{% include image-gallery.html images="scootcadasm.png" height="550" align="center" %}
<br>
- Ran SolidWorks Simulations using finite element analysis to test the deflection of the handle bar and main seat, simulating the load of the rider
<br>

<!-- FEA  -->
<div style="display: grid; grid-template-columns: 1fr 1fr; row-gap: 4px; column-gap: 60px; align-items: start;">

  <!-- Title row -->
  <div style="text-align: center; font-size: 15px; margin-top: 20px; margin-bottom: 0;">Vertical PVC Handlebar FEA</div>
  <div style="text-align: center; font-size: 15px; margin-top: 20px; margin-bottom: 0;">Horizontal PVC Seat FEA</div>

  <!-- Content row -->
  <div style="margin-top: 0px; text-align: center;">
    {% include image-gallery.html images="VerticalHandlebarBeam.png" height="550" %}
  </div>
  <div style="margin-top: 0px; text-align: center;">
    {% include image-gallery.html images="HorizontalSeatBeam.png" height="425" %}
  </div>
</div>
<!-- END FEA -->

---

## Results
- Fabricated the scooter out of the PVC piping using shop tools and PVC cement 
<br>
{% include image-gallery.html images="scootpvc.jpeg" height="550" align="left" %}
{% include image-gallery.html images="scoot.jpeg" height="550" %}

<div style="clear: both;"></div>

{% include image-gallery.html images="scootride.jpeg" height="550" align="left"%}

