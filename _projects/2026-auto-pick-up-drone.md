---
layout: project
title: Auto-pickup Drone and Payload Target
order: 3
description: a 10 in quad that was tethered to hatchet and whose purpose was to mate the long line with the payload target
technologies: [Onshape, 3D Printing, FEA, CNC Milling]
image: /assets/images/AutoPickup.jpg
---

A 10 in quad prototype that was intended to be hung from Hatchet and then attach to a target which was connected to a payload. The project was ultimately canceled, but it would have fixed the problem of a passive guide cone hanging below Hatchet being too difficult too control by giving us much more control authority over the guide cone. Also, being able to pick up things by flying over them would have been incredibly valuable because it would have meant that Hatchet could pick up and drop payloads entirely without human intervention, making the process safer, more efficient (because we avoid take off and landing which use a lot of energy), and it would have allowed Hatchet to make multiple payload trips in one flight. Physically, the drone had a load bearing aluminum section (200 lbs FOS 3 I think) with an actuated dowel pin and an inductive sensor to detect when the target is able to be locked in with the pin, as well as an edge-compute camera to localize with respect to the target. It also had 8 guiding carbon fiber tubes and a small guiding cone in the center. The inductive sensor, actuated pin, camera, and I think the load bearing stuff too all worked as designed, but the project had some other problems...

I pretty much did everything for this project except the initial conception, and I think the project failed for a couple of big reasons. One was that the guide cone I used on the drone was actually made up of 8 sticks and a smaller guide cone in the middle to reduce drag and moments of inertia, but we only found out after flying and trying to connect with the target that it didn't really help guide the drone onto the target, I think because the 8 sticks didn't help much and the drone would freak out whenever the guide touched the cone. This freaking out points to what I think is another big issue, which is that the regular control algorithms for drones are definitely not designed to have the drone be attached to a long line from above and have sticks coming out of them that touch things attached to the ground.

My main takeaways are that it helps to be able sniff out big problems before you make big commitments and that getting an initial proof-of-concept prototype out quickly is almost always very valuable. Even though the main idea for this project (guiding drone on string) was not mine, meaning I didn't start out with a wrong idea, I did fail see a problem and I just went along with it. More importantly though, if I'd gotten a proof-of-concept prototype out more quickly (it took like 3 months to get the first flying one), that maybe tested less of the other less important features and tested the most important ones, we might have had time to try a different approach. This was a rare project where I had near complete ownership, but it didn't really work out.

I also designed a pyramid-shape, flat-packable target with a load-bearing (up to 200 lbs FOS 3 i think) piece. We also tested a different configuration of this drone where we removed the 8 carbon fiber tubes on the bottom and replaced them with a hook and then changed the target to something that held a rope, like in an arresting cable on a carrier, Zipline's drone catchers, or when a plane picks up a banner. This was much easier to capture the target, but because the drone had a long stick on it it flew poorly.

<div class="media-columns">

  <img src="{{ '/assets/images/AutoPickupCAD.png' | relative_url }}" alt="Example 1">

  <img src="{{ '/assets/images/Target.jpg' | relative_url }}" alt="Example 2">

  <img src="{{ '/assets/images/TargetFolded.jpg' | relative_url }}" alt="Example 2">

  <img src="{{ '/assets/images/TargetCAD.png' | relative_url }}" alt="Example 2">

  <img src="{{ '/assets/images/TargetBotCAD.png' | relative_url }}" alt="Example 2">

  <img src="{{ '/assets/images/RopeTarget.jpg' | relative_url }}" alt="Example 2">

</div>
