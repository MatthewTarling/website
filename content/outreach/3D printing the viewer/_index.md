---
title: 3D printing the viewer
summary: 
date: "2021-08-19"
type: book
draft: false
toc: false
weight: 8
---

All the components for the thin section viewer can easily be printed on an entry level 3D printer. Three of the components require supports: the two 'follow brackets' and the 'main drive bracket'. 

Although is my first foray into 3D printing, if you run into any problems printing the parts, I might be able to help you troubleshoot them.


{{% staticref "uploads/slideviewerSTL.zip" "newtab" %}}Download the .STL files{{% /staticref %}}

Here are all the 3D printed parts you will need to build the slide viewer. 

<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="ring_gear.png" alt="Ring gear (x2)" style="max-width: 100%;">
    <p>Ring gear (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="turn_gear.png" alt="Turn gear" style="max-width: 100%;">
    <p>Turn gear</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="main_drive_bracket.png" alt="Main drive bracket" style="max-width: 100%;">
    <p>Main drive bracket</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="main_drive_gear.png" alt="Main drive gear" style="max-width: 100%;">
    <p>Main drive gear</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="follow_bracket.png" alt="Follow bracket (x2)" style="max-width: 100%;">
    <p>Follow bracket (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="follow_gear.png" alt="Follow gear (x2)" style="max-width: 100%;">
    <p>Follow gear (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="central_follow_gear_holder.png" alt="Central follow gear holder (x2)" style="max-width: 100%;">
    <p>Central follow gear holder (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="central_follow_gear.png" alt="Central follow gear" style="max-width: 100%;">
    <p>Central follow gear</p>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="support_post.png" alt="Support post (x2)" style="max-width: 100%;">
    <p>Support post (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="connector_post.png" alt="Connector post (x2)" style="max-width: 100%;">
    <p>Connector post (2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="polariser_ring.png" alt="Polariser ring (x2)" style="max-width: 100%;">
    <p>Polariser ring (x2)</p>
  </div>
  <div style="flex: 0 0 25%; padding: 10px; text-align: center;">
    <img src="grub_screw.png" alt="Grub screw (x2)" style="max-width: 100%;">
    <p>Grub screw (x2)</p>
  </div>
</div>



In addition to these parts, you will also find 2 tools, a drive gear with a hex bit hole and a template to cut out the polarisers:

<div style="display: flex; justify-content: space-between;">
  <div style="flex: 0 0 48%; padding: 10px; text-align: center;">
    <img src="hexgear.png" alt="Image 1" style="max-width: 100%;">
    <p>Hex drive gear</p>
  </div>
  <div style="flex: 0 0 48%; padding: 10px; text-align: center;">
    <img src="poltemp.png" alt="Image 2" style="max-width: 100%;">
    <p>Polariser template</p>
  </div>
</div>

Once you've printed everything, all that remains is to [assemble the viewer!](https://matthewtarling.github.io/outreach/assembly/)

<video id="myVideo" src="printing.mp4" title="Title" autoplay loop></video>
<script>
  const video = document.getElementById('myVideo');
  video.autoplay = true;
</script>
