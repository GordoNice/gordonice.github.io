---
title: 'Movement of a charged particle in electromagnetic field'
date: 2021-06-16
permalink: /posts/2021/06/part_movement/
tags:
  - physics
  - visualization
  - glowscript
  - vpython
  - lecture
---

![](https://ivangordeev.com/images/glowscript/partmovement.png)

This visualization was done as an illustrative material for lecture on the
"Physics and Technology of Accelerators" at Dubna State University. Coded with
[VPython](https://vpython.org/) and powered by [GlowScript](https://www.glowscript.org).

The control of the motion of a charged particle in electric and magnetic fields
is described by the following formula:

$$\vec{F}=\frac{d\vec{p}}{dt}=\vec{F}_{\text{el.}}+\vec{F}_{\text{mag.}}=Q\vec{E}+Q[\vec{v}, {\vec{B}}]$$

In the program you can control parameters from formula and check what changes.

Thus, in order to act on a moving charged particle, a force $\vec{F}$. The first
component ($\vec{F}\_{\text{el.}}$) sets the action from the electric field, the
second ($\vec{F}\_{\text{mag.}}$) --- represents the strength of the magnetic field.

The electric field accelerates (or slows down) the movement of the particle,
while the magnetic field only changes the direction of movement.

Try this out on a GlowScript site or right here below!

[Direct link to GlowScript site with the program](https://www.glowscript.org/#/user/Gordonice/folder/PhysTechAccelLections/program/Lec01pipe)

<iframe src="/files/glowscript/Lec01pipe.html" style="width: 100%; height: 800px;border: none;"></iframe>
