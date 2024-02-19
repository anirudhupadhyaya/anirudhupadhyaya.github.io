---
layout: splash
title: "Projects"
permalink: /portfolio/
author_profile: false
header: 
  overlay_color: #0a0a0a
  overlay_filter: rgba(240, 240, 240, 0.4)
  overlay_image: /images/portfolio/windings/bp5_stator.jpg

intro: 
  - excerpt: I am currently in the process of updating/adding new items to my portfolio, some pages here are not fully completed yet. I am hoping to have them done by the end of August.


feature_row:
- url: /portfolio/wempec_eturbo/
  image_path: /images/gallery_cover/Turbocharger_nasa.png
  title: Bearingless Machines (BSPM) for Aerial E-Turbocharger Application
  excerpt: Army Research Laboratory (ARL) and UW’s ERC & Severson Research Group to explore using bearingless motor technology to create a new generation of electric turbochargers for aerial vehicles.
  btn_class: btn--primary
  btn_label: "Read More"

feature_row2:  
- url: /portfolio/bosch_BMS/
  image_path: /images/portfolio/BMS_stock.png
  title: Low cost Battery Management System for 12V Li-ion battery
  excerpt: Thrust to create a low-cost 12V BMS solution as part of embracing electrification for the Indian market during my stint at Bosch India.
  btn_class: btn--primary
  btn_label: "Read More"
photo_gallery:
- url: https://photos.app.goo.gl/JPcHQWNW28xP1x7h8
  title: Photo Gallery
  excerpt: Photo album for various past projects.
  btn_label: View Here
  btn_class: btn--info
---
<style>
  #show_bg {
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.6)),
    url('/images/gallery_cover/photo_gallery.png');
    width: 100%;
    height: 300px;
    background-size: cover;
    color: white;
    padding:100px
  }

  /* Container holding the image and the text */
  .container {
  position: relative;
  text-align: center;
  }

  /* Bottom right text */
  .text-block {
    position: absolute;
    top: 50%;
    left: 50%;
    background-color: black;
    opacity: 0.7;
    color: white;
    transform: translate(-50%, -50%);
    padding:40px;
    border-radius: 10px;
  }

  .container .btn {
  /* position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%); */
  background-color: #00BFFF;
  color: white;
  font-size: 16px;
  padding: 12px 24px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  }

  .container .btn:hover {
    background-color: #48D1CC;
  }

    
</style>

<!-- {% include feature_row id="intro" type="center"%} -->

# Active Projects
{: .text-center}
<br/>

{% include feature_row %}

# Past Projects
{: .text-center}
<br/>


{% include feature_row id="feature_row2"%}

<!-- {% include feature_row id="photo_gallery" type="center"%} -->

<div class="container">
  <div id='show_bg'>
    <div class="text-block">
      <h1 style="color: white;">Interested in seeing more?</h1>
      <p>Check my photo gallery in Google Photos!</p>
      <a href="https://photos.app.goo.gl/JPcHQWNW28xP1x7h8"><button class="btn"><u>View Here</u></button></a>
    </div>
  </div>
</div>

<br/>