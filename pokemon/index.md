---
layout: none
title: Pixelmon Map
tags: [Minecraft]
date: 2021-01-01
comments: false
---
<style>
@font-face {
    font-family: PokemonSolid;
    src: url("/assets/fonts/PokemonSolid.ttf") format('truetype');
    font-weight: bold;
    font-style: normal;
}
@font-face {
    font-family: PokemonHollow;
    src: url("/assets/fonts/PokemonHollow.ttf") format('truetype');
    font-style: normal;
}
body {
  background-color:black;
  font-family: PokemonSolid;
}

.round_div {
    border-radius: 5%;
    width: 100%;
    height: 145px;
    background:#3B4CCA ;
    text-align:center;
    overflow:display;
    min-heigh:150px;
    border:5px solid #CC0000;
}
.logo {
  font-size:32px;
  color:#CC0000;
  padding:0px;
  margin-bottom:0x;
}
.logo:hover {
  color:#FF0000;
}
.map_button{
  border-radius: 25%;
  font-family: PokemonSolid;
  background-color:#CC0000;
  color:#FFDE00;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}
.map_button:hover{
  color:#CC0000;
  background-color:#FFDE00;
  cursor: pointer;
}
.buttons {
    margin-top:-1%;
    padding:0px;
}

</style>

<div class="round_div">
<span class="logo">Dos Tres Amigoz</span>
<p class="buttons">
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=flat&zoom=0&x=900&y=64&z=-1816';">2D</button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=surface&zoom=1&x=235&y=64&z=-2126';">3D</button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=DIM72&mapname=flat&zoom=2&x=525&y=64&z=-530';">UltraSpace</button>
<button class="map_button" onclick="window.open('http://dostresamigoz.club/trainers/','_blank')">Trainers</button>
<button class="map_button" onclick="window.open('http://dostresamigoz.club/gyms','_blank')">Gyms</button>
<button class="map_button" onclick="window.open('https://pixelmonmod.com/wiki/Available_Pok%C3%A9mon','_blank')">Wiki</button>

  </p>



  <iframe id="main_map" style="position:fixed; top:150px; left:0; bottom:0; right:0; width:100%; height:90%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;" src="http://161.35.13.161:8123/?worldname=world&mapname=flat&zoom=0&x=900&y=64&z=-1816" frameborder="0"> </iframe>
</div>
