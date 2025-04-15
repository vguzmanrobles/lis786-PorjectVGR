---
title: Images
layout: page
permalink: /images
image: https://th.bing.com/th/id/OIP.adt7-9X6KOzWvpkjadEFEwHaJs?rs=1&pid=ImgDetMain
variable: Violet's Sweet Salon
---


{% for pictures in site.pictures  %}
<!-- DO SOMETHING -->
<h3>{ pictures.title}}</h3>
<p>
    <img src="{{pictures.image}}" alt="alt text">
</p>




