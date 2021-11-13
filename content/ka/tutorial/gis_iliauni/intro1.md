---
title: ტუტორიალი - ნაწილი 1
linktitle: მონაცემების შესახებ
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  example:
    parent: ტუტორიალი
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

ამ ნაწილში გავეცნობით სივრცითი მონაცემების ტიპებს, მათი შენახვისა და გაზიარების ფორმებს. ასევე, მოკლედ შევეხებით გეორეფერენსირების, კოორდინატთა სისტემის და სხვა მნიშვნელოვანი ტერმინების მნიშვნელობას.

## 1. ვექტორული მონაცემები

ვექტორული მონაცემები წარმოადგენს ბუნებრივი გარემოს, ლანდშაფტისა და მისი ელემენტების რეპრეზენტაციის საშუალებას. იგი ეყრდნობა <b>თანმიმდევრული წერტილების (ვერტექსი)</b> და <b>ხაზების</b> წყობას. ვექტორული მონაცემები ასევე წარმოდგენილია <b>პოლიგონების</b> სახით. პოლიგონი წარმოადგენს წერტილებისა (ვერტექსები) და ხაზების ერთობლიობას და ქმნის შეკრულ სივრცით ერთეულს. 

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

</head>
<body>

<div class="row">
  <div class="column" style="">
    <p>{{< figure src="/img/landscape_geometry.jpeg" width=100% title="სურ. 1.ა. როგორ გადაითარგმნებოდა მოცემული ბუნებრივი ლანდშაფტი წარმოდგენილი GIS გარემოში. მდინარეები (ლურჯი) და გზები (მწვანე) წარმოდგენილია ხაზების, ხეები წერტილების (წითელი), ხოლო ნაგებობები პოლიგონების (თეთრი) სახით.<br>წყარო: qgis დოკუმენტაცია">}}</p>
  </div>
</div>

</body>
</html>

### 1.1. წერტილები (ვერტექსები)


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
    <p>{{< figure src="/img/points-vector-300x205.png" width=50% title="სურ. 1.1.ა. წერტილები<br>წყარო: gisgeography.com" >}}</p>
  </div>
  <div class="column" style="">
    <p>{{< figure src="/img/point_feature.png" width=50% title="სურ. 1.1.ბ. წერტილოვანი მონაცემები აღწერს კონკრეტული ფიზიკური ერთეულის ლოკაციას სივრცეში <br>წყარო: qgis დოკუმენტაცია ">}}</p>
  </div>
</div>
</body>
</html>

## 1.2. რასტრული მონაცემები

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

## განსხვავება ვექტორულ და რასტრულ მონაცემებს შორის

## 3D

Mesh, TIN, xyz 

## გეორეფერენსირება 

კოორდინატებში დასმა

## კოორდინატთა სისტემა

UTM

## მონაცემთა შენახვისა და გაზიარების ფორმები 

### ბაზები, შეიპფაილები, Online Map Services

WMS, WMTS