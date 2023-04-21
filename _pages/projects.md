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
Animations of potential vorticity, made using [pyqg](https://github.com/pyqg/pyqg) in order to provide
an elementary example of the differences between QG and SQG dynamics, following Held et al., 1995.
All models are initialized with the same surface/upper layer buoyancy anomaly
with no background flow or planetary vorticity gradient.


<video autoplay="autoplay" loop="loop" width="1120" height="630">
  <source src="/images/comb1.mp4" type="video/mp4">
</video>


## Shallow water tide model with self-attraction and loading

I made a linear, single-layer, viscous, non-rotating
shallow water model with tidal and wind forcing to explore
using different predictor and predictor-corrector schemes
when applying self-attraction and loading (SAL) forcing
in an ocean model.
The code for the model can be found in a Github repository
[here](https://github.com/mjclobo/swTideModel).


<video autoplay="autoplay" loop="loop" width="1120" height="630">
  <source src="/images/sw_tide_wind_2.mp4" type="video/mp4">
</video>


