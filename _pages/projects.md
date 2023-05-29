---
title: 'Projects'
layout: single
permalink: /projects/
author_profile: true
excerpt: 'This is where I will post projects as I dig them up/create new ones'
header:
  overlay_image: /images/AGU_ke.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

## Quasi-geostrophy and surface quasi-geostrophy
Here are a couple of animations of potential vorticity evolution,
made using [pyqg](https://github.com/pyqg/pyqg), that provide
elementary examples of the differences between QG and SQG dynamics.


This first animation follows a basic example from Held et al., 1995.
All models are initialized with the same surface/upper layer buoyancy anomaly
with no background flow or planetary vorticity gradient.


<video autoplay="autoplay" loop="loop" width="1120" height="630">
  <source src="/images/comb_two_panel.mp4" type="video/mp4">
</video>


In this second animation we compare a barotropic QG model (left)
with an SQG model (right) using an initial condition with energy at a few
wavenumbers around 9 and random phases (similar to that of Fig. 11.8
in Vallis, 2017).
The barotropic animation is run 4x as fast as the SQG animation.
One thing to note is the much greater stability/persistence
of long, thin structures in the barotropic model than in the
SQG one.

<video autoplay="autoplay" loop="loop" width="1120" height="630">
  <source src="/images/comb_9wav.mp4" type="video/mp4">
</video>



## DIY rotating tank 
I recently scrapped together a rotating tank setup (with a phone mount)
from an old
record player and some nuts and bolts.
The video below shows some eddies forming in the tank
as viewed from a non-inertial, rotating frame of reference.

In the future I plan on using the tank to exhibit topographic Rossby
waves and baroclinic instability.

{% include video id="raEENcJgxic" provider="youtube" %}

![rotating tank](/images/rot_tank.jpg)

## Shallow water tide model with self-attraction and loading
I made a linear, single-layer, viscous, non-rotating
shallow water model with tidal and wind forcing to explore
using different predictor and predictor-corrector schemes
when applying self-attraction and loading (SAL) forcing
in an ocean model.


<video autoplay="autoplay" loop="loop" width="1120" height="630">
  <source src="/images/sw_tide_wind_2.mp4" type="video/mp4">
</video>


