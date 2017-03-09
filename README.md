# web-app

<!DOCTYPE html>
<html>


<head>

 <link rel="stylesheet"  href="css.css"/>

 <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<!-- jquery style used for carousel items-->
  <style>
  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
      width: 50%;
      margin: auto;
  }
  </style>

</head>


<body class = "body">
<header>

	<div class = "div2">	  
	<p class = "p"> <img src="pan logo.jpg " alt="Photo of hibiscus" width ="150px" align = "center"> PANdemonium </p>
	</div>
	
  
<!-- a css file is linked to the carousel for styling-->
<div class ="carousel">
<!-- a default container created for the carousel-->
<div class="container">
  <br>
  <!-- bootstrap code to create a carousel-->
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators for carousel -->
    <ol class="carousel-indicators">
	<!-- list created to sequence pictures into the carousel-->
	<!-- list item created to start at the first picture-->
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
	  <!-- list item created to skip to picture 2-->
      <li data-target="#myCarousel" data-slide-to="1"></li>
	  <!-- list item created to skip to picture 3-->
      <li data-target="#myCarousel" data-slide-to="2"></li>
	  <!-- list item created to skip to picture 4-->
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides in the carousel -->
	<!-- code also identifies that the carousel is a list box-->
    <div class="carousel-inner" role="listbox">
	<!-- showing the active picture the user is on-->
      <div class="item active">
	  <!-- frist picture is added-->
	  <!-- height and width figures are also added-->
	  <img src="picture1.jpg"  width="400" height="300">
      </div>
	  <!-- second picture is added-->
	  <!-- height and width figures are also added-->
      <div class="item">
        <img src="picture2.jpg"  width="400" height="300">
      </div>
	  <!-- third picture is added-->
	  <!-- height and width figures are also added-->
      <div class="item">
        <img src="picture3.jpg"  width="400" height="300">
      </div>
		<!-- forth picture is added-->
	  <!-- height and width figures are also added-->
      <div class="item">
        <img src="picture4.jpg"  width="400" height="300"
      </div>
    </div>
	<!-- the left arrow director for the carousel-->
	<!-- made with bootstrap-->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
	<!-- a glyphicon arro is used to represent the direction element-->
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
	  <!-- used to hide the word 'previous' from the rendered page-->
      <span class="sr-only">Previous</span>
    </a>
	<!-- the right arrow director for the carousel-->
	<!-- made with bootstrap-->
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
	<!-- a glyphicon arro is used to represent the direction element-->
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
	  <!-- used to hide the word 'next' from the rendered page-->
      <span class="sr-only">Next</span>
    </a>

  </div>
</div>
</div>

<div class = "div1" > Do you need simple easy tutorials on steel pan notes?<br/>
Then this is the site for you, here at Pandemonium we offer free videos on the notes of high pitched tenor pans and 6 bass pans as well.<br/>
View our exciting animations and immerse yourself in the classy, graceful sounds of our national instrument.<br/>
Click on the type of pan you would like to learn about underneath to get started  <br/> <br/>  <br/> 
</div>
 
 
 <button class = "buttontenor"> <a href="Tenorpan.html"> Tenor </button>
 
 <button class = "buttonbase"> <a href="Basepan.html"> 6 Base Pan </button>
</header>

<hr>

<footer>
<p class = "p1"> ©PANdemonium : TRINIDAD AND TOBAGO</br>
The Fastest way to learn how to play our national instrument
</p>  
</footer>

</body>
</html>