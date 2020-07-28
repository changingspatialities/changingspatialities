---
title: დემოგრაფია
subtitle: მოსახლეობის უთანასწორო გეოგრაფია 
summary: მოსახლეობის უთანასწორო გეოგრაფია
date: 2020-04-09
lastmod: 2020-04-10
math: true
diagram: true
image:
  placement: 
  caption: ''
links:
  - icon_pack: fab
    icon: medium
    name: თავდაპირველად გამოქვეყნდა ბლოგზე
    url: 'http://bit.ly/2TMVmHz'
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
ეს ვიზუალები, თავდაპირველად გამოქვეყნდა ჩვენს ბლოგზე და მოკლედ განიხილავს დემოგრაფიული ვითარების რამდენიმე მნიშვნელოვან სივრცით ასპექტს.
საქართველოში დემოგრაფიული სიტუაციის უფრო დეტალური ანალიზი გამოქვეყნდა ამ სფეროს მკვლევარების მიერ შექმნილ ვებ-გვერდზე <a href="http://bit.ly/2Wdgae2">Demotrends</a>.
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
    <p>{{< figure src="/img/population_map_general_transparent_1 - georgian.png" width=360 title="მოსახლეობის რაოდენობა 1 კვ.კმ. ბადეზე">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/population cartogram - georgian.png" width=360 title="დემოგრაფიული კარტოგრამა" >}}</p>
  </div>
</div>
<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/pop comparison georgian.png" width=360 title="დემოგრაფიული განაწილება <br> საქართველოს ორ გეოგრაფიულ ერთეულს შორის">}}</p>
  </div>
  <div class="row">
    <div class="column" style="">
     <p>{{< figure src="/img/Top 3 cities georgian.png" width=360 title="საქართველოს სამი უდიდესი ქალაქის <br> დემოგრაფიული ვიზუალი">}}</p>
  </div>
</div>
<div class="column" style="">
    <p>{{< figure src="/img/skyline_georgia.png" width=360 title="საქართველოს დემოგრაფიული 'პროფილი' <br> ბათუმიდან კახეთამდე" >}}</p>
  </div>
  <div class="row">
    <div class="column" style="">
     <p>{{< figure src="/img/population_beats_1.png" width=360 title="საქართველოს დემოგრაფიული 'პროფილი' <br> ე.წ. [joylines](http://localhost:1313/ka/interactive/population-lines/) მეშვეობით">}}</p>
  </div>
</div>
</body>
</html>

<font size="2">
    <b>გამოყენებული პროგრამები:</b> <i>ArcMap; ArcScene & Adobe Illustrator</i>  <br> <b>მონაცემები:</b> <a href="http://gis.geostat.ge/GeoMap/layersw/index.html"><i>საქსტატი</i></a>
</font>