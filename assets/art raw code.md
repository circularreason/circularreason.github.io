[add header here]

body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    opacity: 0.7;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url('/images/wither.jpg');
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("/images/peters1.png");
    min-height: 400px;
}

/* Third image (Thanks) */
.bgimg-3 {
    background-image: url("/images/desert1.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

#googleMap {
    width: 100%;
    height: 400px;
    -webkit-filter: grayscale(90%);
    filter: grayscale(90%);
}

/* Turn off parallax scrolling for tablets and mobiles */
@media only screen and (max-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}

</style>

<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <ul class="w3-navbar" id="myNavbar">
    <li><a href="http://keithbuhler.com/fun" class="w3-padding-large">HOME</a></li>
  </ul>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-opacity w3-display-container">
  <div class="w3-display-middle" style="white-space:nowrap;">
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>A philosopher is a thought-artist</em></p>
  <p>I am a devout amateur. I like to draw, paint, and sculpt. I also enjoy exploring new and unusual media like pumpkins, snow, or Silly Putty.</p>

  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-section">
      <p><b>At the Getty in Los Angeles</b></p><br>
      <img src="/images/keithbuhler-getty.jpg" class="w3-circle" alt="Photo of Me">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-section">
      <p>I encourage everyone to present their creations to family and friends, even if that is not "their thing." You don't have to be a professional to be a creator.</p>
    </div>
  </div>
</div>




<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-light-grey w3-wide">PORTFOLIO</span>
  </div>
</div>



<!-- Container (Portfolio Section) -->

<div class="w3-content w3-container w3-padding-64">
  <h3 class="w3-center">PHOTOGRAPHY </h3>
  <p class="w3-center"><em>Here are some of my creations.<br> Click an image to make it large.</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  
  <div class="w3-row-padding w3-center">
    
    <div class="w3-col m3">
      <img src="/images/desert1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="/images/desert2.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

       <div class="w3-col m3">
      <img src="/images/italy.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

  </div>


 

  <div class="w3-row-padding w3-center">
      <div class="w3-col m3">
            <img src="/images/peters1.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/peters.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

  </div>



  <h3 class="w3-center">SCULPTURE </h3>
     <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
        <img src="/images/tiger-box.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    <div class="w3-col m3">
      <img src="/images/gandalf4.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="/images/dante1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>
  </div>



  <h3 class="w3-center">PUMPKINS</h3>
  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/pumpkin-harry.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/pumpkin-jabba.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
      <div class="w3-col m3">
      <img src="/images/pumpkinzilla.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
    </div>





  <h3 class="w3-center">CAKES </h3>
  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/thomas.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/trex.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  </div>


  <h3 class="w3-center">GRAPHIC DESIGN</h3>
  <div class="w3-row-padding w3-center">
      <div class="w3-col m3">
      <img src="/images/gregorylogo.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>



      <div class="w3-col m3">
      <img src="/images/art1.1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

  </div>



  <h3 class="w3-center">PAINTING</h3>
  <div class="w3-row-padding w3-center">


      <div class="w3-col m3">
      <img src="/images/art2.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    </div>


  <h3 class="w3-center">DRAWINGS AND SKETCHES</h3>
  <div class="w3-row-padding w3-center">
    
    <div class="w3-col m3">
      <img src="/images/wither.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

  <div class="w3-row-padding w3-center">

     <div class="w3-col m3">
      <img src="/images/art4.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art5.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art7.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
 
  
  </div>


  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/art8.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art9.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
        <div class="w3-col m3">
      <img src="/images/art19.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    </div>

  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/art10.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art12.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
      <div class="w3-col m3">
      <img src="/images/art13.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    </div>

  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/art14.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art15.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
      <div class="w3-col m3">
      <img src="/images/art16.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    </div>


  <div class="w3-row-padding w3-center">

    <div class="w3-col m3">
      <img src="/images/art17-1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    <div class="w3-col m3">
      <img src="/images/art17-2.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    <div class="w3-col m3">
      <img src="/images/art17-4.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

  </div>


  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/art11sketch-man-sitting-front-1.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
    </div>

      <div class="w3-col m3">
        <img src="/images/art11sketch-man-sitting-front-2.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>


      <div class="w3-col m3">
        <img src="/images/art11sketch-man-sitting-front-3.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>


     <div class="w3-col m3">
      <img src="/images/art11sketch-man-sitting-front-4.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
    </div>


  <div class="w3-row-padding w3-center">

      <div class="w3-col m3">
      <img src="/images/art20.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

      <div class="w3-col m3">
      <img src="/images/art21.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>
  
      <div class="w3-col m3">
      <img src="/images/art22.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
      </div>

    </div>

    </div>



<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-closebtn w3-hover-red w3-text-white w3-xxxlarge w3-container w3-display-topright">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" style="max-width:100%">
  </div>
</div>

<br>


<iframe width="560" height="315" src="https://www.youtube.com/embed/SMr6C2n5l2k" frameborder="0" allowfullscreen></iframe>


<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sPBSyyay428" frameborder="0" allowfullscreen></iframe>

<br>


<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-light-grey w3-wide">THANKS FOR VISITING</span>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-dark-grey w3-padding-48 w3-hover-black">
</footer>
 
<!-- Add Google Maps -->
<script src="http://maps.googleapis.com/maps/api/js"></script>
<script>
var myCenter = new google.maps.LatLng(41.878114, -87.629798);

function initialize() {
var mapProp = {
  center:myCenter,
  zoom:12,
  scrollwheel:false,
  draggable:false,
  mapTypeId:google.maps.MapTypeId.ROADMAP
  };

var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);

var marker = new google.maps.Marker({
  position:myCenter,
  });

marker.setMap(map);
}

google.maps.event.addDomListener(window, 'load', initialize);

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-navbar" + " w3-card-2" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card-2 w3-animate-top w3-white", "");
    }
}
</script>

</body>
</html>

