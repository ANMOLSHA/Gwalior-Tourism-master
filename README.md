<!DOCTYPE html>
<html>
<head>
	<title></title>
  <meta charset="UTF8">
  <meta name="viewport" content="width=devices-width,initial-scale=1.0">
  <meta http-equip="X-UA-Compaitable" content="ie=edge">
<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<link rel="stylesheet" type="text/css" href="GwlTourism.css">
</head>
<body>
<div class="header">
  <div class="progress-container">
    <div class="progress-bar" id="myBar"></div>
  </div>  
</div>
<script>
window.onscroll = function() {myFunction()};

function myFunction() {
  var winScroll = document.body.scrollTop || document.documentElement.scrollTop;
  var height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
  var scrolled = (winScroll / height) * 100;
  document.getElementById("myBar").style.width = scrolled + "%";
}

</script>  
<div class="Top">
 <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top" style=" background-color: #192332 !important; border-top: 10px solid #54c4c1;">
  <a class="navbar-brand" href="#"><img src="travel-logo-png-1.png" style="height: 100px; margin-left: -40px;"><b style="color: #fff;">GWALIOR TOURISM</b></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon" style="background-color: inherit;
    border-radius: 9px;border: 3px solid #416f9f;"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#"><b style="border: 2px solid dodgerblue; padding: 7px;">Home</b><span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="ptv.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><b>
          Places To Visit</b>
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="ptv.html">Gwalior Fort</a>
          <a class="dropdown-item" href="ptv.html">Jai-Vilas palace</a>
          <a class="dropdown-item" href="ptv.html">Gujari Mahal [State Archaeological Museum]</a>
          <a class="dropdown-item" href="ptv.html">Man Mandir palace</a>
          <a class="dropdown-item" href="ptv.html">Tomb of Tansen</a>
          <a class="dropdown-item" href="ptv.html">Teli Ka Mandir</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="ptv.html">And Many More....</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="hotel.html"><b>Hotels</b></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="resturant.html"><b>Restaurant</b></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="htr.html"><b>How To Reach</b></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="contact.html"><b>Contact Us</b></a>
      </li>
    </ul>
    <nav class="navbar navbar-light bg-light"  style=" background-color: #5d5d5d00!important;">
  <form class="form-inline">
    <a href="signlog.html"><button class="btn btn-outline-success" type="button">Sign Up</button><button class="btn btn-sm btn-outline-secondary" type="button">Login</button></a>
    <!-- Button trigger modal -->
  </form>
  </div>
 </nav>

</div>
<br>
<br>
<br>
<br>
<br>
<br>
<div class="carousel slide" data-ride="carousel" data-interval="3000" id="bar" data-pause="false">
	<div class="carousel-inner">
		<div class="carousel-item active">
			<img src="b1.jpg">
			<div class="carousel-caption">
				<center>
				<h3><b>Gwalior-Fort</b></h3>
				</center>
			</div>
		</div>
		<div class="carousel-item">
			<img src="b2.png">
      <div class="carousel-caption">
        <center>
        <h3><b>Jai-Vilas Palace</b></h3>
        </center>
      </div>
		</div>
		<div class="carousel-item">
			<img src="b3.jpeg">
      <div class="carousel-caption">
        <center>
        <h3><b>Gwalior-Fort-Front</b></h3>
        </center>
      </div>
		</div>
		<div class="carousel-item">
			<img src="b4.jpg">
      <div class="carousel-caption">
        <center>
        <h3><b>Gwalior-zoo</b></h3>
        </center>
      </div>
		</div>
		<div class="carousel-item">
			<img src="b5.png">
      <div class="carousel-caption">
        <center>
        <h3></h3>
        </center>
      </div>
		</div>
    <div class="carousel-item">
      <img src="b6.jpg">
      <div class="carousel-caption">
        <center>
        <h3><b>Sun-Temple</b></h3>
        </center>
      </div>
    </div>
	</div>
        <a href="#bar" class="carousel-control-next" data-slide="next"><span class="carousel-control-next-icon"></span></a>
        <a href="#bar" class="carousel-control-prev" data-slide="prev"><span class="carousel-control-prev-icon"></span></a>
        <ul class="carousel-indicators">
        	<li data-target="#bar" data-slide-to="0" class="active"></li>
        	<li data-target="#bar" data-slide-to="1"></li>
        	<li data-target="#bar" data-slide-to="2"></li>
        	<li data-target="#bar" data-slide-to="3"></li>
        	<li data-target="#bar" data-slide-to="4"></li>
          <li data-target="#bar" data-slide-to="5"></li>
    </div>
</div>
<br>
<div class="container-fluid">
  <div class="container">
    <center>
    <h2 style="color: black"><b class="s">WELCOME TO <span class="l" style="color: dodgerblue;">GWALIOR</span></h2>
      </center>
      <br>
      <div class="row">
        <div class="col-md-7">
          <p class="text-justify banner-content">
             Gwalior is best known for its imposing hilltop fort, which was famously described as ‘the pearl amongst fortresses in India’. Historically, the city has been the cradle of a number of dynasties that ruled it over the years. Their influence is clearly seen in the many regal structures that dominate the cityscape. In a sense, Gwalior continues to retain a medieval majesty.

             Gwalior holds an unparalleled reputation in Sangeet, and has retained Indian traditions and the wealth of music intact over the years. The Gwalior Gharana is one of the oldest Khayal Gharanas and the one to which most classical Indian musicians can trace the origin of their style. Legendary musicians like Tansen and Baiju Bawara belonged to Gwalior.

             Gwalior also has a rich history in sports, with the wizard of Hockey, Dhyan Chand, belonging to the city.
          </p>
        </div>
        <div class="col-md-5 text-center">
           <img class="pixel" src="pixel.jpg" style="height: 300px; width: 300px; box-shadow: 0px 8px 8px 0px;">
        </div>
      </div>
  </div>
</div>
    <br><br>
<div class="container-fluid" style="background-color: #607d8b61">
  <center>
    <br>
    <h2 style="color: #000"><b class="s">The <span class="l" style="color: #096ac8;">Fort </span><span class="l" style="color: black;">City </span><span class="l" style="color: #096ac8;">Gwalior</span></h2>
      </center>
      <br>
        <div class="container">
          <div class="row">
          <div class="col-md-7 col-sm-7 col-lg-7">
          <div class="wrapper">
            <div class="videowrapper">
               <iframe src="https://www.youtube.com/embed/nFVROO-L9mE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
          </div>
        </div>
        <div class="col-md-5 col-sm-5 col-lg-5">
          <br>
        <p  class="text-justify banner-content">Gwalior is a city in the central Indian state of Madhya Pradesh. It's known for its palaces and temples, including the Sas Bahu Ka Mandir intricately carved Hindu temple. Ancient Gwalior Fort occupies a sandstone plateau overlooking the city and is accessed via a winding road lined with sacred Jain statues. Within the fort’s high walls is the 15th-century Gujari Mahal Palace, now an archaeological museum.<br>
        Area: 780 km²<br>Weather: 15°C,Wind NE at 10 km/h,70% Humidity<br>Population: 11.6 lakhs (2011)<br>Avg. winter temperature: 6.6°C (43.9°F)<br>Avg. summer temperature: 40.5°C (104.9°F)<br>
        </p>
        </div>
        </div>
      <br><br>    
    </div> 
  </div> 
</div>
<div class="container-fluid">
  <center>
    <br><br>
    <h2 style="color: #000"><b class="s">"Tourism <span class="l" style="color: #096ac8;">Capital </span><span class="l" style="color: black;">Of </span><span class="l" style="color: #096ac8;">Madhya Pradesh"</span>
    </h2>
    </center>
    <br><br>
   <div class="container">
    <div class="card-deck">
  <div class="card">
     <a href="ptv.html"><img src="g2.jpg" class="card-img-top" alt="Places to visit" style="border-radius: 200px; box-shadow: 0px 0px 20px 3px;"></a>
    <div class="card-body">
      <h5 class="card-title">Places To Visit</h5>
      <p class="card-text">Gwalior is a city famous for valour and love for art. Gwalior has forts, temples and many other monuments that remind Hindus of their brave and proud heritage.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">Last updated 3 mins ago</small>
    </div>
  </div>
  <div class="card">
    <a href="hotel.html"><img src="g.jpg" class="card-img-top" alt="Hotels" style="border-radius: 200px; box-shadow: 0px 0px 20px 3px;"></a>
    <div class="card-body">
      <h5 class="card-title">Hotels</h5>
      <p class="card-text">There are a large number of hotels, available at decent prices. The hotels listed with online offer a wide range of services to make your trip hassle-free, and you can make your booking before you reach the venue.</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">Last updated 3 mins ago</small>
    </div>
  </div>
  <div class="card">
     <a href="food.html"><img src="g3.jpg" class="card-img-top" alt="Food And Restaurant" style="border-radius: 200px; box-shadow: 0px 0px 20px 3px;"></a>
    <div class="card-body">
      <h5 class="card-title">Food And Restaurant</h5>
      <p class="card-text">Visiting Gwalior is not just about history but about food too.Food of Gwalior is known for its elaborate breakfast consisting of kachoris, Samosas, Poha and bedai Among the local Madhya Pradesh cuisine</p>
    </div>
    <div class="card-footer">
      <small class="text-muted">Last updated 3 mins ago</small>
    </div>
  </div>
</div>
        </div>
</div>
<br>
<br>
<div class="map">
  <center>
   <h2 style="color: #000"><b class="s">"Explore "<span class="l" style="color: #096ac8;">Gwalior</span>
    </h2>
    </center>
    <br>
    <br>
<iframe  width="100%" height="500" frameborder="0" style="border:0;"src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d114542.8186404311!2d78.12068716826933!3d26.214138801485987!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3976c5d1792291fb%3A0xff4fb56d65bc3adf!2sGwalior%2C%20Madhya%20Pradesh%2C%20India!5e0!3m2!1sen!2sus!4v1578249490863!5m2!1sen!2sus" allowfullscreen=""></iframe>
</div>
<!-- Footer -->
<footer class="page-footer font-small blue-grey lighten-5" style="background-color: darkslategray;">
  <div style="background-color: #21d192;">
    <div class="container">

      <!-- Grid row-->
      <div class="row py-4 d-flex align-items-center">

        <!-- Grid column -->
        <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
          <h6 class="mb-0">Get connected with us on social networks!</h6>
        </div>
        <!-- Grid column -->

        <!-- Grid column -->
        <div class="col-md-6 col-lg-7 text-center text-md-right" style="color: black;">

          <!-- Facebook -->
          <a class="ic" href="https://www.facebook.com/people/Anmol-Sharma/100004621953711">
           <i class="fa fa-facebook-official" aria-hidden="true"></i>
          </a>
          <!-- Twitter -->
          <a class="ic" href="https://twitter.com/AnmolSh31767158">
            <i class="fa fa-twitter" aria-hidden="true"></i>
          </a>
          <!-- Google +-->
          <a class="ic" href="">
           <i class="fa fa-google-plus" aria-hidden="true"></i>
          </a>
          <!--Linkedin -->
          <a class="ic" href="https://www.whatsapp.com">
            <i class="fa fa-whatsapp" aria-hidden="true"></i>
          </a>
          <!--Instagram-->
          <a class="ic" href="https://www.instagram.com/anmol_1998cool/">
            <i class="fa fa-instagram" aria-hidden="true"></i>
          </a>

        </div>
        <!-- Grid column -->

      </div>
      <!-- Grid row-->

    </div>
  </div>

  <!-- Footer Links -->
  <div class="container text-center text-md-left mt-5">

    <!-- Grid row -->
    <div class="row mt-3 dark-grey-text">

      <!-- Grid column -->
      <div class="col-md-3 col-lg-4 col-xl-3 mb-4" style="color: #fff">

        <!-- Content -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Gwalior Tourism</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>A culturally rich city with all things beautiful, Gwalior has had a glorious history with prominent dynasties ruling the region in the past. With all its forts and palaces and parks and museums, Gwalior is definitely worth a visit! </p>

      </div>
      <!-- Grid column -->
      <hr>

      <!-- Grid column -->
      <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Useful links</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
           <br>
           <a class="dark-grey-text" href="ptv.html"># Places To Visit</a>
           <br>
           <br>
           <a class="dark-grey-text" href="hotel.html"># Hotels</a>
            <br>
            <br>
           <a class="dark-grey-text" href="food.html"># Food & Restaurant</a>
            <br>
            <br>
           <a class="dark-grey-text" href="#!"># How To Reach</a>
        
      </div>
      <!-- Grid column -->
       <hr>

      <!-- Grid column -->
      <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4" style="color: #fff;">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Contact</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>
          <i class="fa fa-home mr-3" ></i> Gwalior, Madhya Pradesh</p>
          <br>
        <p>
        <i class="fa fa-envelope-square"></i>anmol1998cool@gmail.com</p>
        <br>
        <p>
          <i class="fa fa-phone" aria-hidden="true"></i> +91 9131664706</p>

      </div>
      <!-- Grid column -->

    </div>
    <!-- Grid row -->

  </div>
    <!-- Footer Links -->
  <div class="container text-center text-md-left mt-5">

    <!-- Grid row -->
    <div class="row mt-3 dark-grey-text">

      <!-- Grid column -->
      <div class="col-md-3 col-lg-4 col-xl-3 mb-4" style="color: #fff">

        <!-- Content -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Gwalior Tourism</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>A culturally rich city with all things beautiful, Gwalior has had a glorious history with prominent dynasties ruling the region in the past. With all its forts and palaces and parks and museums, Gwalior is definitely worth a visit! </p>

      </div>
      <!-- Grid column -->
      <hr>

      <!-- Grid column -->
      <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Useful links</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
           <br>
           <a class="dark-grey-text" href="ptv.html"># Places To Visit</a>
           <br>
           <br>
           <a class="dark-grey-text" href="hotel.html"># Hotels</a>
            <br>
            <br>
           <a class="dark-grey-text" href="food.html"># Food & Restaurant</a>
            <br>
            <br>
           <a class="dark-grey-text" href="#!"># How To Reach</a>
        
      </div>
      <!-- Grid column -->
       <hr>

      <!-- Grid column -->
      <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4" style="color: #fff;">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold" style="color: #7fffc8">Contact</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>
          <i class="fa fa-home mr-3" ></i> Gwalior, Madhya Pradesh</p>
          <br>
        <p>
        <i class="fa fa-envelope-square"></i>anmol1998cool@gmail.com</p>
        <br>
        <p>
          <i class="fa fa-phone" aria-hidden="true"></i> +91 9131664706</p>

      </div>
      <!-- Grid column -->

    </div>
    <!-- Grid row -->

  </div>
  <!-- Footer Links -->
  <!-- Copyright -->
  <div class="footer-copyright text-center text-black-50 py-3">
    <a style="color: white;">© Tourism @ 2020 :</a>
    <a class="dark-grey-text" href="#">GwlTourism.com</a>
  </div>
  <!-- Copyright -->

</footer>
<!-- Footer -->
</body>
</html>

