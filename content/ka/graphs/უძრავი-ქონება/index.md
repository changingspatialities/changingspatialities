---
title: უძრავი ქონება
subtitle: Python და ხელმისაწვდომი საცხოვრისი [თბილისში]
summary: Python და ხელმისაწვდომი საცხოვრისი [თბილისში]
lastmod: 2020-03-10
math: true
diagram: true
links:
  - icon_pack: fab
    icon: medium
    name: თავდაპირველად გამოქვეყნდა ბლოგზე
    url: 'https://medium.com/profoundly-seen/python-affordable-housing-tbilisi-7d36fa6cc4f9'
---
<style>
  img {
    transition:transform 0.25s ease;
    filter: grayscale(100%);
}
  img:hover {
    filter: grayscale(0);
}
</style>

<center><h3>თვიური და დღიური გაქირავება ბინების ტიპის, რაიონების და საცხოვრებელი ფართის მიხედვით</h3></center>

<p align="justify">
ეს ვიზუალები ნაწილია ჩვენს ბლოგზე დადებული პოსტის, რომელიც მიმოიხილავს უძრავი ქონების ერთ-ერთი საიტიდან მონაცემების გაფხეკვის (ინგლ. web-scraping) შედეგად მოპოვებულ ინფორმაციას. მონაცემების მოპოვების, გაწმენდის, დახარისხებისა და ვიზუალიზაციის მეთოდების შესახებ, ამ <a href="http://bit.ly/3aEdSc4">github</a> გვერდზე  არის დაწვრილებით ახსნილი.</p>

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
    <p>{{< figure src="/img/tbilisi_monthly_rent_bar_1.jpg" width=360 title="თვიური განცხადებების დისტრიბუცია <br> ბინის ტიპის და რაიონის მიხედვით">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_daily_rent_bar_1.jpg" width=360 title="დღიური განცხადებების დისტრიბუცია <br> ბინის ტიპის და რაიონის მიხედვით" >}}</p>
  </div>
</div>
<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_monthly_rent1.jpg" width=360 title="თვიური ქირის დისტრიბუცია <br> რაიონების მიხედვით">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_daily_rent1.jpg" width=360 title="დღიური ქირის დისტრიბუცია <br> რაიონების მიხედვით" >}}</p>
  </div>
</div>
<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_rent_dumbbell_plot1.jpg" width=360 title="სხვაობა საშუალო თვიურ ქირაში <br> ბინის ტიპის მიხედვით">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_rent_size_dumbbell_plot1.jpg" width=360 title="სხვაობა საშუალო საცხოვრებელ ფართში <br> თვიური გაქირავებისას ბინის ტიპის <br> მიხედვით" >}}</p>
  </div>
</div>
<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_daily_rent_dumbbell_plot.jpg" width=360 title="სხვაობა საშუალო დღიურ ქირაში <br> ბინის ტიპის მიხედვით">}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/tbilisi_daily_rent_size_dumbbell_plot.jpg" width=360 title="სხვაობა საშუალო საცხოვრებელ ფართში <br> დღიური გაქირავებისას ბინის ტიპის <br> მიხედვით" >}}</p>
  </div>
</div>
</body>
</html>

<font size="2">
    <b>გამოყენებული პროგრამები:</b> <i>Python & Adobe Illustrator</i>
</font>

