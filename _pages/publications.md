---
layout: page
permalink: /publications/
title: CATLAB
description: <b>C</b>reative <b>A</b>I <b>T</b>echnologies research lab, currently hosted at <a href="https://cmpe.boun.edu.tr">Bogazici University, Department of Computer Engineering</a>. 
years: [2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

<hr>
<h1 class="post-title" style="font-family: 'Crimson Text', serif;">Team</h1>

<b>Principal Investigator</b>:  <a href="">Dr. Pinar Yanardag</a><br>
<b>Team Members</b>: xxx<br>
<b>Alumni:</b> xxx

<hr>
<h1 class="post-title" style="font-family: 'Crimson Text', serif;">Acknowledgement</h1>
We would like to acknowledge the support from 2232 International Fellowship for Outstanding Researchers Program of TUBITAK (Project No: 118c321). We also acknowledge the support of NVIDIA Corporation through the donation of the TITAN X GPU and GCP research credits from Google.  

 
