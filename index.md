<html lang="en">
<head>
  <title>Tamamo Fan Website 1</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="icon" type="image/x-icon" href="images/tamamo_header.png">  
  
  <style>
  .fa {font-size: 30px; height: 40px; width: 40px; text-align: center; text-decoration: none;  border-radius: 8px;}
  .fa:hover {opacity: 0.7;}
  .fa-facebook {background: #3B5998; color: white;}
  .fa-twitter {background: #55ACEE; color: white;}
  .fa-youtube {background: #bb0000; color: white;}
  .fa-instagram {background: #125688; color: white;}
  span.share-bluesky {font-size: 30px; height: 40px; width: 40px; text-align: center; border-radius: 8px; background: #1185fe;}
  span.share-bluesky > svg {fill: #fff; width: 30px; height: 30px; margin: 0.3em;}
    
  .header {padding: 80px, text-align: center; background: linear-gradient(#3AA0EA, #8FE5FE); color: white;}
    
  /* Increase the font size of the h1 element */
  .header h1 {font-size: 40px;}
  body {font-family: Arial, Helvetica, sans-serif;}
  
    /* Style the top navigation bar */
  .navbar {
    overflow: hidden; /* Hide overflow */
    background-color: #333; /* Dark background color */
  }
  
  /* Style the navigation bar links */
  .navbar a {
    float: left; /* Make sure that the links stay side-by-side */
    display: block; /* Change the display to block, for responsive reasons (see below) */
    color: white; /* White text color */
    text-align: center; /* Center the text */
    padding: 14px 20px; /* Add some padding */
    text-decoration: none; /* Remove underline */
  }
  
  /* Right-aligned link */
  .navbar a.right {
    float: right; /* Float a link to the right */
  }
  
  /* Change color on hover/mouse-over */
  .navbar a:hover {
    background-color: #ddd; /* Grey background color */
    color: black; /* Black text color */
  }

  .dropdown {
    float: left;
    overflow: hidden;
  }

  .dropdown .dropbtn {
    font-size: 17px;
    border: none;
    outline: none;
    color: white;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
  }

/* Style the dropdown content (hidden by default) */
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }

/* Style the links inside the dropdown */
  .dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    text-align: left;
    display: block;
  }
  /* Show the dropdown menu when the user moves the mouse over the dropdown button */
  .dropdown:hover .dropdown-content {
    display: block;
  }  
  </style>
</head>

<body>

<div class="header">
   <img src="images/tamamo_header.png" alt="Tamamo" width="600" height="600" padding="20">
  <p>A website dedicated to Tamamo.</p>
</div>


<div class="navbar">
  <a class="active" href="#"><i class="fa fa-home"></i></a> 
  <a href="https://en.wikipedia.org/wiki/Tamamo-no-Mae">Sobre <br> Tamamo OG</a>
  <a href="https://typemoon.fandom.com/wiki/Tamamo-no-Mae">Sobre <br> Tamamo Fate</a>
  <div class="dropdown">
    <button class="dropbtn">Temas<br>musicales
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
       <button class="tablink" onclick="openPage('extra', this, 'blue')">An Extra Life with Anyone She Wants</button>
       <button class="tablink" onclick="openPage('extella', this, 'red')">Suiten Nikkou Amaterasu Yano Shizuishi </button>
       <button class="tablink" onclick="openPage('aria', this, 'yellow')">By Your Side</button>
      <div id="extra" class="tabcontent">
        <h3>An Extra Life with Anyone She Wants</h3>
        <p>El tema de Tamamo, original en Fate/Extra.</p>
      </div>
      <div id="extella" class="tabcontent">
        <h3>Suiten Nikkou Amaterasu Yano Shizuishi</h3>
        <p>El tema de Tamamo en Fate/Extella.</p>
      </div>
      <div id="aria" class="tabcontent">
        <h3>By Your Side</h3>
        <p>El tema de Tamamo Aria en Fate/Samurai Remnant.</p>
      </div>
    </div>
  </div>
  <a href="https://fategrandorder.fandom.com/wiki/Tamamo_no_Mae">Tamamo <br> FGO</a>
  <div class="dropdown">
    <button class="dropbtn">Tamamo<br>Nine
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
        <button class="tablinks" onclick="openPage('origen', this, 'black')" id="defaultOpen">Origen</button><br>
        <button class="tablinks" onclick="openPage('casko', this, 'blue')">Tamamo (Caster)</button><br>
        <button class="tablinks" onclick="openPage('cat', this, 'red')">Tamamo Cat</button><br>
        <button class="tablinks" onclick="openPage('aria', this, 'yellow')">Tamamo Aria</button><br>
    </div>
  </div>
</div>

<div id="origen" class="tabcontent">
  <h3>El sorprendente origen del Tamamo Nine.</h3>
  <p>Tras lo que le sucedió a Tamamo, decidió cortarse todas las colas menos una para evitar que una tragedia similar pudiera repetirse.</p><br>
  <p>Sin embargo, de las 8 colas, llenas de su divinidad, crecieron 8 espíritus similares a ella, formándose así el Tamamo Nine.</p>
</div>

<div id="casko" class="tabcontent">
  <h3>Casko</h3>
  <p>La encarnación de la original y la mejor. Sale en Extra, Extra CCC, Extella, Extella Link y FGO. Muy confiable, gran esposa.</p><br>
  <p>Es algo posesiva y sobreprotectora, aunque puede ser algo cruel con el resto.</p>
</div>

<div id="cat" class="tabcontent">
  <h3>Tamamo Cat</h3>
  <p>Una de las colas de Tamamo. Obsesionada con cocinar, bastante loca y algo bocazas, aunque quizá de forma intencional para crear más caos.</p>
</div>

<div id="aria" class="tabcontent">
  <h3>Tamamo Aria</h3>
  <p>Una de las colas de Tamamo. Su cuerpo y su mente son los de una versión mucho más infantil que el resto de las Tamamos.</p><br>
  <p>También es bastante inocente, aunque puede tener una cierta posesividad innata a todas las Tamamos.</p>
</div>

<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>

<a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#" class="fa fa-youtube"></a>
<a href="#" class="fa fa-instagram"></a>
<span class="share-bluesky">
    <a target="_blank" title="Share on Bluesky" href="https://bsky.app/intent/compose?text=Check%20out%20this%20amazing%20content!">
        <svg width="1em" height="1em" fill="#fff" viewBox="0 0 600 600" xmlns="http://www.w3.org/2000/svg">
        <path d="m135.72 44.03c66.496 49.921 138.02 151.14 164.28 205.46 26.262-54.316 97.782-155.54 164.28-205.46 47.98-36.021 125.72-63.892 125.72 24.795 0 17.712-10.155 148.79-16.111 170.07-20.703 73.984-96.144 92.854-163.25 81.433 117.3 19.964 147.14 86.092 82.697 152.22-122.39 125.59-175.91-31.511-189.63-71.766-2.514-7.3797-3.6904-10.832-3.7077-7.8964-0.0174-2.9357-1.1937 0.51669-3.7077 7.8964-13.714 40.255-67.233 197.36-189.63 71.766-64.444-66.128-34.605-132.26 82.697-152.22-67.108 11.421-142.55-7.4491-163.25-81.433-5.9562-21.282-16.111-152.36-16.111-170.07 0-88.687 77.742-60.816 125.72-24.795z"/>
        </svg>
    </a>
</span>
  
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/346345385&color=%23000eff&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/mika-mio" title="Mika Mio" target="_blank" style="color: #cccccc; text-decoration: none;">Mika Mio</a> · <a href="https://soundcloud.com/mika-mio/fate-extella-ost-tamamo-theme" title="Fate EXTELLA OST - Tamamo Theme An Extra Life With Anyone She Wants" target="_blank" style="color: #cccccc; text-decoration: none;">Fate EXTELLA OST - Tamamo Theme An Extra Life With Anyone She Wants</a></div>

<h1>Cessa's Website Trial 2</h1>
<p>A website copied from the internet to learn.</p>

</body>
</html> 
