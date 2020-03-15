---
title: Demography
subtitle: Uneven population geography [in Georgia]
summary: Uneven population geography [in Georgia]
lastmod: 2020-03-10
math: true
diagram: true
image:
  placement: 
  caption: ''
links:
  - icon_pack: fab
    icon: medium
    name: First published on our blog
    url: 'http://bit.ly/3aYzgJi'
---
<style>
  img {
    max-width: 1200px;
    transition:transform 0.25s ease;
    filter: grayscale(100%);
}
  img:hover {
    filter: grayscale(0);
}
</style>
<p align="justify">
These visuals were fisrt published on our blog and provide solid basis for discussion on spatial peculiarities of current demographic situation in Georgia. 
Further analysis on Georgia's demographic change over the last decades was published on <a href="http://bit.ly/2Wdgae2">Demotrends</a>, a website curated by researchers in population studies.
</p>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/population_map_general_transparent_1.png" width=360 title="Population density per 1 sq.km. grid">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/population cartogram.png" width=360 title="Demographic cartogram" >}}</p>
  </div>
</div>
<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/pop_comparison.png" width=360 title="Demographic comparison between <br> two geographic entities in Georgia">}}</p>
  </div>
  <div class="row">
    <div class="column" style="">
     <p>{{< figure src="/img/Top 3 cities.png" width=360 title="Population per 1 sq.km. density visuals <br> for three major Georgian cities">}}</p>
  </div>
</div>
<div class="column" style="">
    <p>{{< figure src="/img/skyline_georgia_en.png" width=360 title="Georgia's demographic 'profile' <br> from Batumi to Kakheti" >}}</p>
  </div>
  <div class="row">
    <div class="column" style="">
     <p>{{< figure src="/img/population_beats_1.png" width=360 title="Georgia's demographic 'profile' <br> using so called [joylines](http://localhost:1313/ka/interactive/population-lines/)">}}</p>
  </div>
</div>
</body>
</html>

<font size="2">
    <b>Tools Used:</b> <i>ArcMap; ArcScene & Adobe Illustrator</i>  <br> <b>Data:</b> <a href="http://gis.geostat.ge/GeoMap/layersw/index.html"><i>GeoStat</i></a>
</font>