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
    border-radius: 60%;
    width: 100%;
    height: 145px;
    background:#3B4CCA ;
    text-align:center;
    overflow:display;
    min-heigh:150px;
    border:4px solid #CC0000;
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
  font-family: PokemonSolid;
  background-color:#CC0000;
  color:#FFDE00;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}
.buttons {
    margin-top:-1%;
    padding:0px;
}

</style>

<div class="round_div">
<span class="logo">Dos Tres Amigoz</span>
<p class="buttons">
<button class="map_button">2D</button>
<button class="map_button">3D</button>
<button class="map_button">UltraSpace</button>
<button class="map_button" onclick="window.open(http://dostresamigoz.club/trainers/','_blank')">Trainers</button>
<button class="map_button" onclick="window.open('http://dostresamigoz.club/gyms','_blank')">Gyms</button>
<button class="map_button" onclick="window.open('https://pixelmonmod.com/wiki/Available_Pok%C3%A9mon','_blank')">Wiki</button>

  </p>



  <iframe style="position:fixed; top:150px; left:0; bottom:0; right:0; width:100%; height:80%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;" src="http://161.35.13.161:8123/?worldname=pixelmon_world&mapname=surface&zoom=4&x=417&y=64&z=-44#" frameborder="0"> </iframe>
</div>
