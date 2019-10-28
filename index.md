<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Theme Made By www.w3schools.com - No Copyright -->
  <!-- Theme modified by Firuza Aibar - No Copyright -->
  <title>Firuza's Site</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      font: 400 15px Lato, sans-serif;
      line-height: 1.8;
      color: #818181;
  }
  h2 {
      font-size: 24px;
      text-transform: uppercase;
      color: #303030;
      font-weight: 600;
      margin-bottom: 30px;
  }
  h4 {
      font-size: 19px;
      line-height: 1.375em;
      color: #303030;
      font-weight: 400;
      margin-bottom: 30px;
  }  
  .jumbotron {
      background-color: #f4511e;
      color: #fff;
      padding: 100px 25px;
      font-family: Montserrat, sans-serif;
  }
  .container-fluid {
      padding: 60px 50px;
  }
  .bg-grey {
      background-color: #f6f6f6;
  }

  .bg-orange {
      background-color: #f4511e;
      color: #fff;
  }
  .bg-cream {
      background-color: #FFF5EE;
  }

  .bg-1 { 
      background-color: #1abc9c; /* Green */
      color: #ffffff;
  }
  .logo-small {
      color: #f4511e;
      font-size: 50px;
  }
  .logo {
      color: #f4511e;
      font-size: 200px;
  }
  .thumbnail {
      padding: 0 0 15px 0;
      border: none;
      border-radius: 0;
      background-color: #f4511e;
  }
  .thumbnail img {
      width: 100%;
      height: 100%;
      margin-bottom: 10px;
  }
  .carousel-control.right, .carousel-control.left {
      background-image: none;
      color: #f4511e;
  }
  .carousel-indicators li {
      border-color: #f4511e;
  }
  .carousel-indicators li.active {
      background-color: #f4511e;
  }
  .item h4 {
      font-size: 19px;
      line-height: 1.375em;
      font-weight: 400;
      font-style: italic;
      margin: 70px 0;
  }
  .item span {
      font-style: normal;
  }
  .panel {
      border: 1px solid #f4511e; 
      border-radius:0 !important;
      transition: box-shadow 0.5s;
  }
  .panel:hover {
      box-shadow: 5px 0px 40px rgba(0,0,0, .2);
  }
  .panel-footer .btn:hover {
      border: 1px solid #f4511e;
      background-color: #fff !important;
      color: #f4511e;
  }
  .panel-heading {
      color: #fff !important;
      background-color: #f4511e !important;
      padding: 25px;
      border-bottom: 1px solid transparent;
      border-top-left-radius: 0px;
      border-top-right-radius: 0px;
      border-bottom-left-radius: 0px;
      border-bottom-right-radius: 0px;
  }
  .panel-footer {
      background-color: white !important;
  }
  .panel-footer h3 {
      font-size: 32px;
  }
  .panel-footer h4 {
      color: #aaa;
      font-size: 14px;
  }
  .panel-footer .btn {
      margin: 15px 0;
      background-color: #f4511e;
      color: #fff;
  }
  .navbar {
      margin-bottom: 0;
      background-color: #f4511e;
      z-index: 9999;
      border: 0;
      font-size: 12px !important;
      line-height: 1.42857143 !important;
      letter-spacing: 4px;
      border-radius: 0;
      font-family: Montserrat, sans-serif;
  }
  .navbar li a, .navbar .navbar-brand {
      color: #fff !important;
  }
  .navbar-nav li a:hover, .navbar-nav li.active a {
      color: #f4511e !important;
      background-color: #fff !important;
  }
  .navbar-default .navbar-toggle {
      border-color: transparent;
      color: #fff !important;
  }
  footer .glyphicon {
      font-size: 20px;
      margin-bottom: 20px;
      color: #f4511e;
  }
  .slideanim {visibility:hidden;}
  .slide {
      animation-name: slide;
      -webkit-animation-name: slide;
      animation-duration: 1s;
      -webkit-animation-duration: 1s;
      visibility: visible;
  }
  @keyframes slide {
    0% {
      opacity: 0;
      transform: translateY(70%);
    } 
    100% {
      opacity: 1;
      transform: translateY(0%);
    }
  }
  @-webkit-keyframes slide {
    0% {
      opacity: 0;
      -webkit-transform: translateY(70%);
    } 
    100% {
      opacity: 1;
      -webkit-transform: translateY(0%);
    }
  }
  @media screen and (max-width: 768px) {
    .col-sm-4 {
      text-align: center;
      margin: 25px 0;
    }
    .btn-lg {
        width: 100%;
        margin-bottom: 35px;
    }
  }
  @media screen and (max-width: 480px) {
    .logo {
        font-size: 150px;
    }
  }
  </style>
</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#academics">ACADEMICS</a></li>
        <li><a href="#work">WORK</a></li>
        <li><a href="#interests">INTERESTS</a></li>
        <li><a href="#books">BOOKS</a></li>
        <li><a href="#contact">CONTACT</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container-fluid text-center bg-cream">
  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="images/home1.jpg" alt="" style="width:100%;">
        <div class="carousel-caption">
          <p>"Description begins in the writer's imagination, but should finish in the reader's. - by Stephen King"</p>
        </div>

      </div>
      <div class="item">
        <img src="images/home2.jpg" alt="" style="width:100%;" caption="heelo">
        <div class="carousel-caption">
          <p>"If you would not be forgotten as soon as you are dead, either write something worth reading or do things worth writing. - by Benjamin Franklin"</p>
        </div>
      </div>
      <div class="item">
        <img src="images/home3.jpg" alt="" style="width:100%;">
        <div class="carousel-caption">
          <p>"Description begins in the writer's imagination, but should finish in the reader's. - by Stephen King"</p>
        </div>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>


<!-- Container (About Section) -->
<!-- First Container -->
<div id="about" class="container-fluid bg-1 text-center">
  <h3 class="margin">Who Am I?</h3>
  <img src="images/Firuza2.png" class="img-responsive img-circle margin" style="display:inline;" alt="My Photo" width="250"> <br />
I, Firuza Yezdi Aibara, am working as a Project Manager, Computer Science and Engineering Department, at The Indian Institute of Technology Bombay, IIT Bombay, Powai, Mumbai since 2011. I obtained my Masters in Information Technology, M.Sc (IT), from The D. G. Ruparel College, Mumbai, affiliated to The University of Mumbai.
</div>

<!--ACADEMICS-->
<div id="academics" class="container-fluid bg-cream">
  <div class="row">
    <div class="col-sm-7">
      <h2>Academics</h2><br>
      <h4>Masters in Information Technology <br /> from The D. G. Ruparel College, <br /> affiliated to The University of Mumbai <br /> in 2010</h4>
      <h4>Bachelors in Information Technology <br />  from The D. G. Ruparel College, <br />  affiliated to The University of Mumbai <br />  in 2008</h4>
    </div>
    <div class="col-sm-5">
       <img src="images/grad2.png" width="300">
    </div>
  </div>
</div>

<!--WORK-->
<div id="work" class="container-fluid jumbotron">
      <h2>Work</h2><br>
	<ul>
      	  <li> Working as a Project Manager in the Department of Computer Science and Engineering. </li>
      	  <li> Course / Content Design (CS101x - Computer Programming and CS213x - Data Structures and Algorithms) 
	  <ul>
		<li>http://www.iitbombayx.in/ </li>
		<li>https://www.edx.org/</li>
	  </ul>
	  </li>
      	  <li> Creation of different types of randomized multiple choice questions and programming assignments for the course </li>
      	  <li> Our Wiki: http://www.it.iitb.ac.in/frg/wiki/index.php/Fundamental_Research_Group </li>
      	  <li> Our Github Repo: https://github.com/fresearchgroup </li>
	  <li> My Android App (Foodies Adda): https://github.com/firuza/Foodies-Adda </li>
	</ul>
</div>

<div id="interests" class="container-fluid text-center bg-cream">
<h2>My Interests</h2>
  <div class="row slideanim">
    <div class="col-sm-3">
      <span class="glyphicon glyphicon-edit logo-small"></span>
      <h4>Learning a New Language</h4>
	<p>Languages Known: 
	English, Gujarati, Hindi, and Marathi 
	Currently learning Italian and Spanish</p>
    </div>

    <div class="col-sm-3">
      <span class="glyphicon glyphicon-music logo-small"></span>
	<h4>Music</h4>
	<p>Like listening to old Hindi music and 
	Spanish music (Los Bukis and a few others 
	like La Bamba, Lambada, Las Ketchup, etc). Playing guitar.</p>
    </div>

    <div class="col-sm-3">
      <span class="glyphicon glyphicon-camera logo-small"></span>
	<h4>Photography</h4>
	<p>Am a novice photographer, but love to click pictures, espcially of nature</p>
    </div>

    <div class="col-sm-3">
      <span class="glyphicon glyphicon-wrench logo-small"></span>
	<h4>Other Interests</h4>
	<p>Writing articles on various topics, Playing Tennis, Designing Web pages, Trying something new with LaTeX and Beamer</p>
    </div>
  </div>
</div>

<div id="books" class="container-fluid text-center bg-orange">
  <h2>Books</h2><br>
  <h4>I have authored</h4>
  <div class="row text-center slideanim">
    <div class="col-sm-6">
      <div class="thumbnail">
        <img src="images/A_Short_Introduction_to_LaTeX.png" alt="A_Short_Introduction_to_LaTeX" style="width:30%">
        <p><strong>A Short Introduction to LaTeX</strong></p>
        <p>LaTeX is a document preparation system. The book introduces the different concepts of LaTeX and guides them through their way in creating beautiful documents with less effort. <u><a href="https://www.amazon.in/Short-Introduction-Latex-Book-Beginners/dp/1543162649/ref=pd_rhf_gw_p_img_7?_encoding=UTF8&psc=1&refRID=Z9DH2HA27XT1TGPHHADP">Click here to view on Amazon</a></u>. Its Free for kindle unlimited users.</p>
      </div>
    </div>
    <div class="col-sm-6">
      <div class="thumbnail">
        <img src="images/Cheatsheet_for_LaTeX.png" alt="Cheatsheet_for_LaTeX"  style="width:30%">
        <p><strong>Cheatsheet for LaTeX</strong></p>
        <p>This book is a quick reference guide for LaTeX users and lists only the commands and its purpose. It is ideal for an existing LaTeX user or who has just started exploring it. <u><a href="https://www.amazon.in/Cheatsheet-LaTeX-quick-reference-commands-ebook/dp/B07P7RB9XT/ref=pd_rhf_gw_p_img_8?_encoding=UTF8&psc=1&refRID=Z9DH2HA27XT1TGPHHADP">Click here to view on Amazon</a></u>. Its Free for kindle unlimited users.</p>
      </div>
    </div>
  </div><br>

  <div class="row text-center slideanim">
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/html5.jpg" alt="HTML5"  style="width:30%">
        <p><strong> HTML5 for Beginners</strong></p>
        <p>A Reference Book, whose 1st Edition was published in March 2008. The 2nd Edition of the book was printed in February 2010. The 3rd edition of the book, now entitled "HTML5 for Beginners", was published in March 2012.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/PPA.png" alt="PPA" style="width:30%">
        <p><strong>Programming Basics and Principles</strong></p>
        <p>A Text book for 1st Year Degree College, Pune and Nashik University for BCA Students.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/CCPC.jpg" alt="CCPC"  style="width:30%">
        <p><strong>Computer Concepts and Programming in C</strong></p>
        <p>A Text book for 1st Year Engineering Students, Uttar Pradesh Technical University.</p>
      </div>
    </div>
  </div><br>

  <div class="row text-center slideanim">
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/VBA.jpg" alt="HTML5"  style="width:30%">
        <p><strong>Visual Basic Applications and Programming </strong></p>
        <p>Text book for 3rd Year Engineering Students, Gujarat Technical University, Semester V.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/DUC.jpg" alt="PPA" style="width:30%">
        <p><strong>Data Structures using C </strong></p>
        <p>A Text book for 2nd Year Degree College, Pune and Nashik University for BCA, Bachelor of Computer Applications Students.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src="images/VB.jpg" alt="CCPC"  style="width:30%">
        <p><strong>Visual Basic </strong></p>
        <p>A Text book for 3rd Year Degree College, Mumbai University for B.Sc.-IT (Information Technology), Semester - V.</p>
      </div>
    </div>
  </div><br>
</div>


<!-- Container (Contact Section) -->
<div id="contact" class="container-fluid bg-cream">
  <h2 class="text-center">CONTACT ME</h2>
  <div class="row">
    <div class="col-sm-2">
    </div>
    
    <div class="col-sm-5 slideanim">
	<h4>Address</h4>
      <p><span class="glyphicon glyphicon-map-marker"></span> 
	SIC - 402, 4th Floor, <br />
	Fundamental Research Lab, <br />
	Kanwal Rekhi Building, <br />
	Department of Computer Science and Engineering, <br />
	IIT Bombay, <br />
	Mumbai - 400 076
	</p>
    </div>
    <div class="col-sm-5 slideanim">
	<h4>Contact</h4>
      <p><span class="glyphicon glyphicon-phone"></span> Office 1: +91 22 2576 4914</p>
      <p><span class="glyphicon glyphicon-phone"></span> Office 2: +91 22 2576 7747</p>
	<br />
      <p><span class="glyphicon glyphicon-envelope"></span> Email: firuza@cse.iitb.ac.in</p>

    </div>
  </div>
</div>

<footer class="container-fluid text-center">
  <a href="#myPage" title="To Top">
    <span class="glyphicon glyphicon-chevron-up"></span>
  </a>
  <p>Bootstrap Theme Powered By <a href="https://www.w3schools.com" title="Visit w3schools">www.w3schools.com</a></p>
</footer>

<script type='text/javascript' src='//platform-api.sharethis.com/js/sharethis.js#property=5a9677b35d0b9500130f33ad&product=sticky-share-buttons' async='async'></script>

<script>
$(document).ready(function(){
  // Add smooth scrolling to all links in navbar + footer link
  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {
      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
  
  $(window).scroll(function() {
    $(".slideanim").each(function(){
      var pos = $(this).offset().top;

      var winTop = $(window).scrollTop();
        if (pos < winTop + 600) {
          $(this).addClass("slide");
        }
    });
  });
})
</script>


</body>
</html>

