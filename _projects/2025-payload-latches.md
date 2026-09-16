---
layout: project
title: Payload Latches
order: 1
description: Hatchet payload system
technologies: [Onshape, 3D Printing, FEA, Sheet Metal]
image: /assets/images/LatchExplodedCAD.png
---

This payload dropper I designed uses four off the shelf rotary latches that are mounted the the frame with 5052 aluminum sheet metal, a shackle, and rope. We wanted the mounting of the payload to be as flexible as possible, and I wanted to keep it simple, so I went with this design which mounts the latch to the drone with a lot of degrees of freedom which eventually get constrained once the payload is ratchet strapped on. It worked consistently at the military demo where we won the contract and during our video shoot a couple months later.

In a later iteration I made the aluminum sheet metal parts 40% lighter (but also added a 3D printed case and trigger for the manual override to make it look nicer). I used thread-forming screws for the first time in the case, and I found that if they are toleranced correctly they work pretty well with 3D printed parts.

The image with a blue bar (aluminum 6061) and an eyebolt was meant to go under the center of Hatchet and mount a payload latch and then a hanging load from a long-line. Used basic FEA and math for it.


<div class="media-grid">

  <figure class="wide">
    <video autoplay loop muted playsinline>
      <source src="{{ '/assets/videos/Bagdrop.mp4' | relative_url }}" type="video/mp4">
    </video>
  </figure>

  <figure>
    <img src="{{ '/assets/images/LatchV1.jpg' | relative_url }}" alt="Example 2">
  </figure>

  <figure>
    <img src="{{ '/assets/images/LatchExploded1CAD.png' | relative_url }}" alt="Example 2">
  </figure>

  <figure>
    <img src="{{ '/assets/images/LatchCAD.png' | relative_url }}" alt="Example 2">
  </figure>
  
  <figure>
    <img src="{{ '/assets/images/PayloadMounting.jpg' | relative_url }}" alt="Example 1">
  </figure>

  <figure>
    <img src="{{ '/assets/images/LatchCompare.jpg' | relative_url }}"
         alt="latch plate comparison">
    <figcaption>Left is v1, right is v2</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/images/LatchV2.jpg' | relative_url }}" alt="Example 2">
  </figure>

</div>
