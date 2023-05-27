---
title: Mapping Changing Spatialities 
subtitle: Mappy Portfolio 
summary: urban planning and analysis, shaded relief & interactive mapping
date: 2023-05-19
math: true
diagram: false

#links:
  #- icon_pack: fab
  #  icon: medium
  #  name: თავდაპირველად გამოქვეყნდა ბლოგზე
  #  url: 'http://bit.ly/2TMVmHz'
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta property='og:title' content='Mapping Changing Spatialities'/>
    <meta property='og:image' content='https://imgur.com/9Ww0MYu'/>
    <meta property='og:description' content='Mappy Portfolio'/>
    <meta property='og:url' content='https://gkankia.xyz/portfolio/mappy-portfolio/'/>
    <title>Mapping Changing Spatialities</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">   
</head>
<style>
@media print {
    html,
    body {
       display: none;
    }
 }
@import url(https://necolas.github.io/normalize.css/8.0.1/normalize.css);
@import url(https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Noto+Sans+Mono:wght@100;200;300;400;500;600;700;800;900&display=swap);
/* loading local fonts */
@font-face {
    font-family: 'high_alpineregular';
    src: url('https://gkankia.xyz/fonts/highalpine-webfont.woff2') format('woff2'),
         url('https://gkankia.xyz/fonts/highalpine-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'belltopo_sansbold';
    src: url('https://gkankia.xyz/fonts/belltoposans-bold-webfont.woff2') format('woff2'),
         url('https://gkankia.xyz/fonts/belltoposans-bold-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'belltopo_sansbold_italic';
    src: url('https://gkankia.xyz/fonts/belltoposans-bolditalic-webfont.woff2') format('woff2'),
         url('https://gkankia.xyz/fonts/belltoposans-bolditalic-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'belltopo_sansitalic';
    src: url('https://gkankia.xyz/fonts/belltoposans-italic-webfont.woff2') format('woff2'),
         url('https://gkankia.xyz/fonts/belltoposans-italic-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'belltopo_sansregular';
    src: url('https://gkankia.xyz/fonts/belltoposans-regular-webfont.woff2') format('woff2'),
         url('https://gkankia.xyz/fonts/belltoposans-regular-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
/* removing default hugo parameters from the portfolio page */
/*#navbar-main {
  visibility: hidden !important;
  display: none; 
}*/
.article-container.pt-3 {
  visibility: hidden !important;
  display: none; 
}
.share-box {
  visibility: hidden !important;
  display: none; 
}
.article-widget {
  visibility: hidden !important;
  display: none; 
}
.media.author-card.content-widget-hr {
  visibility: hidden !important;
  display:none;
}
.article-container {
  max-width: 100%;
  margin: auto;
  padding: 10px;
}
.article-metadata {
  visibility: hidden !important
}
/* portfolio page customization */
* {
    box-sizing: border-box;
}
#cover-map {
  height: 500px;
  margin: 0 auto !important;
  padding-right: 0 !important;
  padding-left: 0 !important;
}
.mapboxgl-canvas-container {
  margin: 0 auto !important;
  padding-right: 0 !important;
  padding-left: 0 !important;
}
body {
    font-family: 'belltopo_sansregular' !important;
    font-size: 50pt;
    color: #333;
    margin: 0 auto;
    padding-right: 19px;
    padding-left: 19px;
    -webkit-user-select: none;
    -webkit-touch-callout: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}
#page-title {
    z-index: 2;
}
header {
    font-family: 'high_alpineregular' !important;
    font-size: 60pt;
    background-color: #ffffff;
    height: 100px;
    margin-top: 50px;
    margin-bottom: 30px;
}
/* Center website */
.main {
    max-width: 100%;
    margin-top: 100px;
  }
h1 {
    font-family: 'high_alpineregular' !important;
    font-size: 25px;
    word-break: break-all;
    text-align: center;
  }
h2 {
    font-family: 'Noto Sans Mono', monospace !important;
    font-weight: 100;
    font-size: 22px;
    word-break: break-all;
    text-align: center;
  }
  h3, h4 {
    font-family: 'Noto Sans Mono', monospace !important;
    font-weight: 200;
    font-size: 15px;
    word-break: break-all;
    text-align: center;
  }
p {
    font-family: 'belltopo_sansregular' !important;
    font-size: 13px;
    text-align: justify;
    line-height: 3vh;
  }
#about {
    max-width: 50%;
    margin: 0 auto;
    margin-top: 25px;
    margin-bottom: 25px;
    padding-top: 25;
    padding-bottom: 25;
    /*letter-spacing: 50px;*/
    }
p.about {
  line-height: 30px;
}
.row {
    display: flex;
    flex-wrap: wrap;
    /*margin: 10px;*/
    align-items: stretch;
  }
/* Clear floats after rows */ 
.row:after {
    content: "";
    display: table;
    clear: both;
}
  /* Add padding BETWEEN each column */
  .row,
  .row > .column {
    padding: 8px;
  }
  /* Create three equal columns that floats next to each other */
  .column {
    flex: 1 0 33.33%;
    padding: 1px;
    display: none; /* Hide all elements by default */
    /* Set equal heights for columns */
    flex-direction: column; /* Stack content vertically within columns */
  }
  .content-iframe {
    position: relative;
    padding-bottom: 50%;
    overflow: hidden;
  }
  .content-iframe iframe {
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0; 
    width: 100%;
    height: 100%;
  }
  /* Content */
  .content {
    background-color: white;
    padding: 10px;
  }
  /* The "show" class is added to the filtered elements */
  .show {
    display: block;
  }
/* Style the buttons */
#myBtnContainer {
    margin-top: 40px;
    margin-bottom: 50px;
    position: absolute;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}
.btn {
    max-width: 100%;
    font-family: 'belltopo_sansregular'; 
    font-size: 15px;
    color: #969696;
    border: none !important;
    outline: none !important;
    background: linear-gradient(180deg,white 90%, #2862FC 10%) !important;
    cursor: pointer;
  }
  .btn:hover {
    font-size: 17px;
    background-color: #ffffff;
    color: #252525;
  }
  .btn.active {
    background-color: #ffffff;
    color: #252525;
  }
  span.highlight {
    color: white;
    background: #757577;
    padding: 2px 5px 2px 5px;
  }
  a.link {
    color: #333;
    padding: 30;
    border: none;
    background: linear-gradient(180deg,white 95%, #000000 5%);
    cursor: pointer;
    text-decoration: none;
  }
  a.link:visited {
    color: #333;
  }
  a.link:hover {
    padding: 30;
    color: white;
    background: #000000;
    cursor: pointer;
    text-decoration: none;
  }
  a.mail {
    color: #333;
    padding: 40;
    cursor: pointer;
    text-decoration: none;
  }
  a.mail:visited {
    color: #333;
  }
  a.mail:hover {
    padding: 40;
    color: white;
    background: #000000;
    cursor: pointer;
    text-decoration: none;
  }
 img {
    -webkit-touch-callout: none;
 } 
 img:hover {
    -ms-transform: scale(1.15); /* IE 9 */
    -webkit-transform: scale(1.15); /* Safari 3-8 */
    transform:  scale(1.15);
    -webkit-transition: all .5s ease-in-out;
    -moz-transition: all .5s ease-in-out;
    -o-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
 }
  /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
  @media screen and (min-width: 610px) and (max-width: 1200px) {
    .main {
      max-width: 100%;
      margin-top: 75px;
    }
    header {
      font-size: 40pt;
    }
    #about {
      max-width: 100%;
      margin-top: 10px;
      margin-bottom: 10px;
      padding-top: 10;
      }
    p.about {
      line-height: 35px;
    }
    .column {
      flex-basis: 100%;
      }
    #myBtnContainer {
      max-width: 100%;
      margin-top: 30px;
      margin-bottom: 40px;
      position: relative;
      left: 50%;
      }
    main.btn {
      font-size: 10px;
      line-height: 15px;
    }
    img:hover {
      -ms-transform: scale(1.05); /* IE 9 */
      -webkit-transform: scale(1.05); /* Safari 3-8 */
      transform:  scale(1.05);
      -webkit-transition: all .5s ease-in-out;
      -moz-transition: all .5s ease-in-out;
      -o-transition: all .5s ease-in-out;
      transition: all .5s ease-in-out;
      }
  }
@media screen and (min-width: 300px) and (max-width: 600px) {
    .main {
      max-width: 100%;
      margin-top: 100px;
      padding-top: 100px;
    }
    header {
      font-size: 40pt;
    }
    #about {
      max-width: 100%;
      margin-top: 10px;
      margin-bottom: 40px;
      }
    p.about {
      line-height: 30px;
      padding-bottom: 50px;
      }
    a.link {
      color: #333;
      padding: 30;
      border: none;
      background: linear-gradient(180deg,white 97%, #000000 3%);
      cursor: pointer;
      text-decoration: none;
      }
    .row {
      top: 25%;
      }
    .column {
      flex-basis: 100%;
      }
    #myBtnContainer {
      display: block;
      margin-top: 20px;
      margin-bottom: 25px;
      padding: 0 auto;
      max-width: 100%;
      position: relative;
      left: 50%;
      }
    .btn {
      margin-top: 5px;
      margin-bottom: 5px;
      display: block;
      font-size: 12px;
      line-height: 15px;
      background: linear-gradient(180deg,white 95%, #2862FC 5%) !important;
    }
    img:hover {
      -ms-transform: scale(1.05); /* IE 9 */
      -webkit-transform: scale(1.05); /* Safari 3-8 */
      transform:  scale(1.05);
      -webkit-transition: all .5s ease-in-out;
      -moz-transition: all .5s ease-in-out;
      -o-transition: all .5s ease-in-out;
      transition: all .5s ease-in-out;
      }
  }
</style>
<div oncontextmenu="return false" id="cover-map">
    <iframe loading="lazy" style="border: 0px #ffffff none" src="https://meteor-lumbar-menu.glitch.me" name="myiFrame" width="100%" height="500px" frameborder="1" marginwidth="0px" marginheight="0px" scrolling="no" oncontextmenu="return false;"></iframe>
</div>
<body oncontextmenu="return false;">
    <header>
        <div style="position: absolute; top: 7%; left: 50%; opacity: 0.5;">
            <div div style="position: relative; left: -50%;">
                <div id="page-title" style="font-family: high_alpineregular">Mapping Changing Spatialities</div>
                </div>
              </div>
        <div id="about">
            <p class="about" style="font-size: 17px;">Here is a selection of maps and other data visualisation materials I have worked on both, in <span class="highlight">personal and professional capacity.</span> For more cool stuff, have a look at our organisation's work at <a class="link" href="https://zaxis.ge">Z.axis</a>.</p>
        </div>
        <div id="myBtnContainer">
          <button class="btn active" onclick="filterSelection('all')"> Show all</button>
          <button class="btn" onclick="filterSelection('urban')"> Urban Planning & Spatial Analysis</button>
          <button class="btn" onclick="filterSelection('relief')"> [Shaded/3D] Relief</button>
          <button class="btn" onclick="filterSelection('interactive')"> Interactive</button>
        </div>   
    </header>
    <!-- MAIN (Center website) -->
    <div class="main">
    <div class="row">
      <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/სამცხე-ჯავახეთი_plan_oblique_label.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Samtskhe - Javakheti, Georgia</h4>
            <p style="text-align: center;">Retro-style plan oblique</p>
          </div>
        </div>
        <div class="column interactive">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/tbilisi-1984-2022-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Tbilisi Evolution from the 80s</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/portfolio/ka-tbilisi-evolution">here<a></p>
            <p style="text-align: center;">In collaboration with <i>Tbilisi as an Urban Assemblage</i> <a class="link" href="https://urbanassemblage.iliauni.edu.ge/interactive-map/">project</a>.</p>
          </div>
        </div>
    </div>
    <div class="row">
        <div class="column relief">
        <div class="content">
          <img src="https://gkankia.xyz/img/relief/day 4-svaneti mountains-pano-01.png" alt="" style="width:100%" oncontextmenu="return false;">
          <h4>Svaneti Mountains</h4>
          <p style="text-align: center;">The panorama of the Enguri river gorge in Svaneti, Georgia.</p>
        </div>
      </div>
    </div>
    <div class="row">
        <div class="column interactive">
          <div class="content">
            <iframe loading="lazy" style="border: 0px #ffffff none" src="https://everlasting-branched-ray.glitch.me/" name="myiFrame" width="100%" height="300px" frameborder="1" marginwidth="0px" marginheight="0px" scrolling="no"></iframe>
            <h4>Counting Urban Protest Crowds</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/resources-ka/counting-crowds">here</a></p><p style="text-align: center;"><b>RFE/RL Tbilisi</b> office did a <a class="link" href="https://www.radiotavisupleba.ge/a/31936837.html">documentary</a> on this.</p>
        </div>
      </div>
    </div>
    <div class="row">
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/day 21-Kontur population east geo - new-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>3D Population Map</h4>
            <p>A rather new perspective of looking at Georgia's demographics, with Russian-occupied Tskhinvali included.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/delivery_services-01.svg" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Tbilisi Food Delivery</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/blog-ka-visual/food-geography-post-pandemic-city">here</a></p>
          </div>
        </div>
        <div class="column relief">
            <div class="content">
              <img src="https://gkankia.xyz/img/relief/day 28-puerto_rico_trench.png" alt="" style="width:100%" oncontextmenu="return false;">
              <h4>Puerto Rico Trench</h4>
              <p>This 3D diorama will be featured in a children's book <a class="link" href="https://www.karenromanoyoung.com/books">DIVING FOR DEEP SEA DRAGONS</a> by Karen Romano Young sometime in 2024.</p>
            </div>
          </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/street_slopes_tbs_en-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Tbilisi Street Slopes</h4>
            <p>Topography is not a big issue for cycling in Tbilisi. <b>Euronews Georgia</b> <a class="link" href="https://euronewsgeorgia.com/2021/02/08/tbilisis-meria-mobilobis-ocwlian-strategiaze-mushaobs/">reported</a> on this.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/map_1_georgians in russia-01-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>How Many Georgians Are There in Russia?</h4>
            <p style="text-align: center;">Not 1 000 000! That's for sure!</p>
          </div>
        </div>
        <!--<div class="column interactive">
          <div class="content">
            <iframe loading="lazy" style="border: 0px #ffffff none" src="https://meteor-lumbar-menu.glitch.me" name="myiFrame" width="100%" height="293px" frameborder="1" marginwidth="0px" marginheight="0px" scrolling="no"></iframe>
            <h4>Mkinvartsveri 3D</h4>
            <p>Mount Mkinvartsveri at 5054 M AMSL (a.k.a Mount Kazbek)</p>
          </div>
        </div>-->
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/khada_future mobility_en-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Khada Valley Development Plan</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://gkankia.xyz/portfolio/khada/">here</a></p>
            <p style="text-align: center;">In collaboration with BAU DESIGN through an ADB-funded project.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/access_to_business_metro-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Subway Access to Business Oportunities</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/blog-ka-visual/urban-mobility-tbilisi">here</a></p>
          </div>
        </div>
        <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/kvemo_kartli-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Kvemo Kartli Region, Georgia</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://gkankia.xyz/personal/regions-georgia/">here</a></p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/swimming_pool.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Swimming Pools in Tbilisi</h4>
            <p>The uneven spatial distribution of private swimming pools in Tbilisi.</p>
          </div>
        </div>
        <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/shaded-1-eastern_georgia_with_clouds_v1.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Old maps in 3D</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://gkankia.xyz/personal/old-topos/">here</a></p>        
          </div>
        </div>
        <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/caucasus_glowing-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Glowing South Caucasus</h4>
            <p>This map is a result of trial and error loop while getting my hands on Blender.</p>
          </div>
        </div>
      <div class="row">
        <div class="column urban">
        <div class="content">
          <img src="https://gkankia.xyz/img/ua_sp/animation_energy_use.mp4" alt="" style="width:100%" oncontextmenu="return false;">
          <h4>Energy Use in South Caucasus</h4>
          <p style="text-align: center;">The panorama of the Enguri river gorge in Svaneti, Georgia.</p>
        </div>
      </div>
    </div>
      <div class="row">
        <div class="column interactive">
          <div class="content">
            <div class="content-iframe"><br>
            <iframe loading="lazy" style="border: 0px #ffffff none" src="https://abiding-capable-elderberry.glitch.me/" name="myiFrame" width="100%" frameborder="1" marginwidth="0px" marginheight="0px" scrolling="no"></iframe></div>
          <div class="content">
            <h4>Tracking Black Sea Pollution</h4>
            <p style="text-align: center;">The interactive visual below tracks the nitrate pollution in the Black Sea from March, 2019 up until April, 2022.
            Higher levels of nitrate pollution poses a threat to marine life and the biodiversity.</p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/districts_urban_layout-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Urban Morphology Analysis</h4>
            <p>It is striking to see how these adjacent, historic neighbourhoods in Tbilisi have two completely different urban layout.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/walkability_analysis.jpg" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Urban Walkability Analysis</h4>
            <p>An experimental research on urban walkability conditions in Tbilisi, between 2016-2017. I was privileged to present our analysis at WALK 21 conference in Bogotá (Colombia), in October, 2018. Read more about it <a class="link" href="https://gkankia.xyz/talk/walk-21/">here</a>.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/restaurants_tbilisi-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Urban Food Geography</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/blog-ka-visual/food-geography-post-pandemic-city">here</a></p>
          </div>
        </div>
        <div class="column interactive">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/soviet_georgia_3d-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Soviet Topographic Map of Georgia</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/portfolio/en-sovietgeorgia">here</a></p>        
          </div>
        </div>
        <div class="column interactive">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/georgia population lines-01.jpg" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Georgia Population Joyplot</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://gkankia.xyz/personal/population-lines/">here</a></p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/detentions along SO abl upd_may_2023.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Illegal Detentions Along the ABL</h4>
            <p>This map highlights the arrests, or rather kidnappings of local residents from their own land plots along the Tskhinvali region administrative boundary line by Russian occupation forces and South Ossetia's KGB guards.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/tram_en-01.jpg" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Tbilisi Tram Newtork in 1960s</h4>
            <p>Regardless of how faulty the whole Soviet system might have been, their approach to urban transit planning did make a lot of sense.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/tskaltubo.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Tskaltubo Resort Masterplan</h4>
            <p>Urban accessibility analysis for the Tskaltubo masterplan project team. Read more about the project <a class="link" href="https://zaxis.ge/portfolio/ka-tskaltubo-masterplan">here</a>.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/bakhmaro_voronoi.jpg" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Bakhmaro Resort Masterplan</h4>
            <p>A resort town planning project - my first full-time planning project. Read more about it <a class="link" href="https://gkankia.xyz/portfolio/bakhmaro/">here</a>.</p>
          </div>
        </div>
        <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/day 13-ararat-render-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Mount Ağrı [Ararat], Türkiye</h4>
            <p>Shaded relief map of Mount Ağrı [Arm. Ararat], located in the Eastern part of the country, bordering Armenia.</p>
          </div>
        </div>
        <div class="column interactive">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/map-4-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>3D Population Map of Georgia</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://equatorial-smoggy-stork.glitch.me/">here</a></p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/day 14-georgia fire map_final-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Georgia Fire Prevalence</h4>
            <p>In addition to the spatial distribution of wildfires, industrial areas are also detected as emitting most of the smokes into the atmosphere.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/oni_sp.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Oni Municipality Spatial Plan</h4>
            <p>This project was about developing a spatial plan for a mountainous region of Georgia, Oni municipality. See more about it <a class="link" href="https://gkankia.xyz/portfolio/racha_oni/">here</a>.</p>
          </div>
        </div>
        <div class="column relief">
          <div class="content">
            <img src="https://gkankia.xyz/img/relief/day 16-Egrisi range-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Egrisi Mountain Range</h4>
            <p>A rather abstract visual of a portion of Egrisi mountain range in North-Western Georgia.</p>
          </div>
        </div>
        <div class="column interactive">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/tbilisi_covid_vaccination-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Covid Vaccination Points in Tbilisi</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/map/covid-tbilisi">here</a></p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/day 24-fantasy lego internet speed.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Internet Speed in Tbilisi</h4>
            <p>This lego-style map shows how fast the fixed broadband internet connection is across Tbilisi.</p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/interactive/a-decade-of-growth-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Documenting Tbilisi's Urban Sprawl</h4>
            <p style="text-align: center;">See the full project <a class="link" href="https://zaxis.ge/map/tbilisi-sprawl">here</a></p>
          </div>
        </div>
        <div class="column urban">
          <div class="content">
            <img src="https://gkankia.xyz/img/ua_sp/Top 3 cities-01.png" alt="" style="width:100%" oncontextmenu="return false;">
            <h4>Top 3 Urban Areas in Georgia</h4>
            <p style="text-align: center;">The spatial distribution of demographics.</p>
          </div>
        </div>
      </div>
    </div>
    <script>        
filterSelection("all")
function filterSelection(c) {
  var x, i;
  x = document.getElementsByClassName("column");
  if (c == "all") c = "";
  for (i = 0; i < x.length; i++) {
    w3RemoveClass(x[i], "show");
    if (x[i].className.indexOf(c) > -1) w3AddClass(x[i], "show");
  }
}
function w3AddClass(element, name) {
  var i, arr1, arr2;
  arr1 = element.className.split(" ");
  arr2 = name.split(" ");
  for (i = 0; i < arr2.length; i++) {
    if (arr1.indexOf(arr2[i]) == -1) {element.className += " " + arr2[i];}
  }
}
function w3RemoveClass(element, name) {
  var i, arr1, arr2;
  arr1 = element.className.split(" ");
  arr2 = name.split(" ");
  for (i = 0; i < arr2.length; i++) {
    while (arr1.indexOf(arr2[i]) > -1) {
      arr1.splice(arr1.indexOf(arr2[i]), 1);     
    }
  }
  element.className = arr1.join(" ");
}
var btnContainer = document.getElementById("myBtnContainer");
var btns = btnContainer.getElementsByClassName("btn");
for (var i = 0; i < btns.length; i++) {
  btns[i].addEventListener("click", function(){
    var current = document.getElementsByClassName("active");
    current[0].className = current[0].className.replace(" active", "");
    this.className += " active";
  });
}
document.addEventListener("contextmenu", function(event) {
  event.preventDefault();
});
window.addEventListener('load', adjustIframeHeights);
window.addEventListener('resize', adjustIframeHeights);
function adjustIframeHeights() {
  var columns = document.querySelectorAll('.column');
  var tallestColumnHeight = 0;
  columns.forEach(function(column) {
    var iframeWrapper = column.querySelector('.content-iframe');
    iframeWrapper.style.height = 'auto'; // Reset height to recalculate
    var columnHeight = column.offsetHeight;
    if (columnHeight > tallestColumnHeight) {
      tallestColumnHeight = columnHeight;
    }
  });
  columns.forEach(function(column) {
    var iframeWrapper = column.querySelector('.content-iframe');
    iframeWrapper.style.height = tallestColumnHeight + 'px';
  });
}
    </script>
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js">
</script>  <script type="text/javascript" charset="utf-8">
$(function() { $('body').hide().show(); });
</script>
</body>
</html>