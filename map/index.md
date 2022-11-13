---
layout: none
title: Server Map
tags: [Minecraft]
date: 2021-01-01
comments: false
---
<meta http-equiv="Content-Security-Policy" content="allow">
<style>
@font-face {
    font-family: CraftFont;
    src: url("/assets/fonts/Minecraft.ttf") format('truetype');
    font-weight: bold;
    font-style: normal;
}
body {
  background-color:black;
  margin:0px;
}
*{
    font-family:CraftFont;
}
.header_div{

  height:100px;
  border-radius: 1%;
   background-image: url("/assets/img/banner.png")
}
.logo {
  font-size:32px;
  color:#FA5204;
  padding:5px;
   text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
}
.logo:hover {
  color:black;
  text-shadow: -1px 0 , 0 1px #FA5204, 1px 0 #FA5204, 0 -1px #FA5204;
}
.map_button{
  padding:2px;
  border-radius: 5%;
  background-color:#FA5204;
  color:#black;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}
.map_button:hover{
  color:#FA5204;
  background-color:black;
  border-color:#FA5204;
  border-width:2px;
  border-style:solid;
  cursor: pointer;
}
</style>
<div class="header_div">
<center>
<br>
<span class="logo">Dos Tres Amigoz</span>
<p class="buttons">
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=flat&zoom=2&x=14&y=64&z=391';">🧭 2D </button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=surface&zoom=3&x=-126&y=64&z=206';">🌎 3D </button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=spawn&zoom=3&x=-198&y=64&z=240';">🔦 Mob Spawn</button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world&mapname=cave&zoom=4&x=-239&y=64&z=300';">⛏ Caves</button>
<button class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world_nether&mapname=flat&zoom=4&x=67&y=64&z=0';">🌋 The Nether</button>
<button style="display:none;" class="map_button" onclick="document.getElementById('main_map').src = 'http://161.35.13.161:8123/?worldname=world_the_end&mapname=flat&zoom=4&x=0&y=64&z=0';">🎇 The End</button>
<button class="map_button" onclick="window.open('https://minecraft.fandom.com/wiki/Item?so=search#List_of_items','_blank')">📚 Minecraft Wiki </button>
  </p>
</center>
  <iframe id="main_map" style="position:fixed; left:0; top:100px; bottom:0; right:0; width:100%; height:100%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;" src="http://161.35.13.161:8123/?worldname=world&mapname=surface&zoom=3&x=-126&y=64&z=206" frameborder="0"> </iframe>
</div>
