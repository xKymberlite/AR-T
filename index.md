<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/maptalks/dist/maptalks.css">
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/maptalks/dist/maptalks.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


<link rel="icon" href="img\titlelogo.png" type="image/icon type">

<title>ART</title>

<!-- CSS -->
<style>
.fa {
  padding: 20px;
  font-size: 30px;
  width: 80px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}


.fa-youtube {
  background: #bb0000;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}

.fa-pinterest {
  background: #cb2027;
  color: white;
}

.fa-reddit {
  background: #ff5700;
  color: white;
}

#mapid {
  height: 180px;
}

hr.solid {
  border-top: 3px solid #B4D3B2;
}
body {
  font-family: Garamond, serif;
}
</style>

</head>

<!-- BEGINNING OF CODE -->
<body style="background-color: #FFFFFF;">
  <nav class="navbar navbar-expand-lg navbar-light navbar-transparent" style="background-color:#B4D3B2">
        <div>
          <a class="navbar-brand" href="index.html">
            <div><img src="img\ART2.png" alt="logo" style="width:100px"></div>
          </a>
        </div>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="index.html"><p style="font-size:25pt; color:#84b780">HOME </p><span class="sr-only">(current)</span></a>
            </li>
          </ul>
        </div>
      </nav>
      <div><br><br><br><br><br></div>
      <div class="container" style:"margin:auto;">
        <div class="row">
          <div class="col-lg">
            <div style="font-size:25pt; text-align: center;">Hey! Welcome to AR Travel! <img src="img\travel.jpg" alt="earth"style="width:10%"><br><br></div>
            <div style="font-size:18pt"> Here, you can discover safely and in the comforts of your home! Scroll down to learn how to do this. Explore cities with AR (3D models) and videos! You can also explore 3D animals with AR in the world by bringing them into your home!</div>
          </div>
          <div class="col-lg" style="text-align: center;">
            <img src="img\cuterearth.gif" alt="earth">
          </div>
        </div>
      </div>
      <div><br><br><br><br><br></div>
<hr class="solid">
      <div><br><br><br><br><br></div>
      <div class="container" style:"margin:auto;">
        <div class="row">

          <div class="col-lg">
            <img src="img\AR-T_Steps.png" alte="instructions" style="display: block; margin-left: auto; margin-right: auto; width: 100%;">
          </div>
        </div>
        <div class = "row">
          <div class="col-lg">
            <div style="font-size:30pt; text-align: center;">How it works <br><br></div>
            <div style="font-size:20pt">Step 1: Click on a pin point. A paw pin point allows you to explore an animal while a red pin point allows you to explore a famous structure in a city!</div>
            <div style="font-size:20pt">Step 2: Click on the QR code</div>
            <div style="font-size:20pt">Step 3: Scan the QR code! To see the full view of some of the structure, make sure you zoom out! (you can trying scanning this one as well!)</div>

          </div>
        </div>
      </div>
    <div>
      <div><br><br><br><br><br></div>
<hr class="solid">
      <div><br><br><br><br><br></div>
<!-- MAP -->
<div class="container" style:"margin:auto">
  <iframe src="https://www.google.com/maps/d/u/0/embed?mid=1VMS1DEHeJ-_P3NbVa3d80H5xhNRaiTCa" style = "width: 1000px; height: 500px;margin:0 auto;display:block;" ></iframe>
</div>
<script>

</script>

    <!-- MAP VERSION ONE
      <div class="container" style="width:800px;height:600px;margin:auto;" id="map"></div>
      <script type="text/javascript">
        // create map in div 'map'
        var map = new maptalks.Map('map', {
          center: [0, 0],
          zoom: 2,
          baseLayer: new maptalks.TileLayer('base', {
            'urlTemplate' : 'http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png',
            'subdomains'  : ['a','b','c','d'],
            'attribution'  : '&copy; <a href="http://www.osm.org/copyright">OSM</a> contributors, '+
            '&copy; <a href="https://carto.com/attributions">CARTO</a>'
          })
        });
      </script>
    -->
    <div><br><br><br><br><br></div>
<hr class="solid">
    <div><br><br><br><br><br></div>
<!--sharing platforms -->
  <div class="container" style:"margin:auto;">
    <p>Share this on    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-share-fill" viewBox="0 0 16 16">
  <path d="M11 2.5a2.5 2.5 0 1 1 .603 1.628l-6.718 3.12a2.499 2.499 0 0 1 0 1.504l6.718 3.12a2.5 2.5 0 1 1-.488.876l-6.718-3.12a2.5 2.5 0 1 1 0-3.256l6.718-3.12A2.5 2.5 0 0 1 11 2.5z"/>
</svg></p>
    <div class="row" style:"margin:auto;">
      <div class="col-sm">
  <a href="https://www.facebook.com/" class="fa fa-facebook"></a>
</div>
<div class="col-sm">
<a href="https://www.twitter.com/" class="fa fa-twitter"></a>
</div>
<div class="col-sm">
<a href="https://www.instagram.com/" class="fa fa-instagram"></a>
</div>
<div class="col-sm">
<a href="https://www.youtube.com/" class="fa fa-youtube"></a>
</div>
<div class="col-sm">
<a href="https://www.pinterest.com/" class="fa fa-pinterest"></a>
</div>
<div class="col-sm">
<a href="https://www.reddit.com/" class="fa fa-reddit"></a>
</div></div>
<br><br><br><br><br>
<!-- cite echoar-->
<a href="https://www.echoar.xyz/">Made With EchoAR®</a>
<br>
<a href="https://www.google.com/maps">Made With Google Maps®</a>







<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
    integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous">
</script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
    integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous">
</script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
    integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous">
</script>
  </body>

</html>
