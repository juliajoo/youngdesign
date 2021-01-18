---
layout: post
title: "ICU Soundscape"
date1: 2018-09-01
date2: 2019-01-29
description: An Audience Participatory Interactive Installation for Dutch Design Week 2018 Embassy of Health Exhibition
image: /assets/images/icusoundscape/smartbench-main.gif
author: Jooyoung Park
tags: 
  - Interactive Art
  - Installation Design
  - Physical Computing
  - Critical Alarm Fatigue
  - Interface Design
image_sliders:
  - smartbench_background
---
ICU Soundscape is an interactive installation design addressing the seriousness of medical alarm cacophony problems in intensive care units (ICU). It was designed as an introductory installation for <a href="https://delftdesignlabs.org/criticalalarmslab/" target="_blank">TU Delft Critical Alarms Lab</a> Exposition with other master graduation projects of the lab. The audience were introduced to a rather unfamiliar target context of ICU by playing the sounds of critical alarms themselves. Each string made out of medical tubes embodied one of the alarm noises in the ICU of Erasmus MC. The audience could create their own alarm cacophony by plucking the strings.

ICU Soundscape was exhibited at Dutch Design Week 2018 Embassy of Health and supported by <a href="https://vanberloagency.com/" target="_blank">VanBerlo</a>.

<hr/>

### Background
Alarm sounds are of crucial importance in this space of ICU as an auditory cue notifying clinicians if immediate action is required - they often signify the difference between life and death. However, they also create a stressful environment for many users. Patients themselves or their families sometimes turn them off, which can lead to a critical situation. The cacophony of alarm sounds also leads to clinicians’ alarm fatigue, in which important signals could be missed.
<hr/>

### Goals

The design goal was to provide an immersive introductory experience of the alarm cacophony, the main problem context of the ICU to laymen audience. While onboarding the audience to the problem context, we wanted the experience to be engaging and playful instead of giving them a didactic impression. 
<hr/>

### Design Process
<ins>**Sketching & Modelling**</ins>
We decided to endow the audience with a power to create the alarm cacophony themselves to make the experience still playful within the seriousness of the topic. A cylinder shaped design with harp-like playable strings attached around its rim was chosen since we found it both intriguing and easy to reassemble. To enhance the quality of immersive experience, we used medical tubes as strings and placed actual or 3D-printed model objects of medical equipment in the middle of the soundscape.

<ins>**Electronics Work & Installation Assembling**</ins>
We mapped alarm sounds collected from Erasmus MC ICU into each tube string using Arduino, tilt sensors, and MaxMSP software. Tilt sensors were attached on the bottom part of the string to detect the user's plucking behavior and actuate respective sound files through MaxMSP. Through iterative testing, the sensitivity of the tilt sensors had to be adjusted to avoid the sounds from playing by themselves. Afterwards, the whole components were assembled. 
<hr/>

### Final Outcome
