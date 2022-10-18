---
title: Georgia on Fire
subtitle: Mapping fire prevalence using Kepler.gl
summary: Mapping fire prevalence using Kepler.gl
date: 2020-02-13
math: true
diagram: true
image:
  placement: 3
  caption: ''
---
<style>
  img {
    transition:transform 0.25s ease;
    filter: grayscale(100%);
}
  img:hover {
    filter: grayscale(0);
}

  img:active {
  pointer-events: none;
  -webkit-touch-callout: none
}
</style>
<p style="padding: 0 7em 2em 0;"></p>
<p align="justify">
    I built the interactive map embedded below, with <a href="https://kepler.gl/">kepler.gl</a> - a python library using Jupyter NB. It is an open source geospatial visualisation platform launched by Uber’s visualisation team and enables users to perform various types of analysis such as heatmaps, choropleth, flows or grids, among others. Additionally, it allows to visualise data in either 2D or 3D and has built-in timeline capability.</p>

<p align="justify">
    To read the complete article, head over to our <a href="https://medium.com/profoundly-seen/georgia-on-fire-972e1349cd5b">blog</a>.</p>

<p align="justify">
    For a fullscreen version of the interactive tool, visit github <a href="https://georgiaonfire.github.io/">page</a>.</p>
<p style="padding: 0 7em 2em 0;"></p>

<iframe src="https://georgiaonfire.github.io/" style="border:0px #ffffff none;" name="myiFrame" scrolling="no" frameborder="1" marginheight="0px" marginwidth="0px" height="600px" width=100% allowfullscreen></iframe>
<p style="padding: 0 7em 2em 0;"></p>

<font size="2">
    <b>Tools Used:</b> <i>Kepler.gl library in Python</i>  <br> <b>Data:</b> <a href="https://data.world/nasa/meteorite-landings"><i>FIRMS by NASA</i></a>
</font>