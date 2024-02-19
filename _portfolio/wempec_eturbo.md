---
title: "Bearingless Machines (BSPM) for Aerial E-Turbocharger Application"
excerpt: "Exploration of using bearingless motor technology to create a new generation of electric turbochargers for aerial vehicles."
collection: portfolio
header: 
  overlay_color: #0a0a0a
  overlay_filter: rgba(240, 240, 240, 0.5)
  overlay_image: /images/gallery_cover/Turbocharger_nasa.png
  show_overlay_excerpt: true	
  caption: "Photo credit: **NASA**"

classes: wide

---

# Overview
This is an ongoing project for the U.S. Army Combat Capabilities Development Command’s Army Research Laboratory to explore using bearingless motor technology to create a new generation of electric turbochargers for aerial vehicles.

[UW Article](https://engineering.wisc.edu/news/11-5m-army-funding-supports-aircraft-hybrid-electric-engine-research-at-uw-madison/){: .btn .btn--info .btn--large} 

<br>

# Current Responsibility
- Characterization of a bearingless motor in a static bearingless dynamometer test-stand.

- I am responsible for developing the control code to operate the prototype machine. 

- Conduct experiments to prove speed-power capapility of prototype. The goal of the project is to demonstrate a bearingless machine at 160 kRPM!

- Prepare reports, documentation and slides to present to project stakeholders in a monthly review meeting.

# Technical Details

- All of the control algorithm in developed in MATLAB Simulink. The top-level simulation combines both the controller as well as the plant. The plant models the electrical and mechanical elements of a bearingless machines

[<img src="/images/portfolio/Simulink_capture.png" width="1000" >](/images/portfolio/Simulink_capture.png)

- The controller follows a cascaded approach with a outer motion controller followed by an inner current regulator. 
- Complex Vector Current Regualation (CVCR) is used for current regulation. Several other current regulation techniques were implented and benchmarked experimentally before zeroing in on CVCR.
- Rotor position sensing at speeds such as 160 kRPM is a challenge. As part of this project, I have developed sensorless algorithm to estimate the rotor position. This work as resulted in [confernce publication](/publications/).