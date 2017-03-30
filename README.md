# web-app

<!DOCTYPE html>
<html>
<head>
<!-- pulls css styling from a file called css-->
<link rel="stylesheet"  href="css.css"/>

	<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- allows the use of bootstrap-->
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<!-- allows the use of jquery--> 
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<!-- allows the use of javascript-->
   <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
 <!-- jquery style used for carousel items-->
 <!-- also defines the width and margin of the carousel-->
   <style>
   .carousel-inner > .item > img,
   .carousel-inner > .item > a > img {
       width: 50%;
       margin: auto;
   }
   </style>
</head>

<!-- pulls from a section in the css file labeled body-->
<body class = "body">

<!-- contains the header for the page and also pulls from a css secton called div2-->
 <div class = "div2">	
<!-- contains the site logo and its heading for the entire page--> 
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
  
  <!-- containf writing which welcomes persons to the page-->
  <div class = "div1" ><b> Do you need simple easy tutorials on steel pan notes?<br/>
Then this is the site for you, here at Pandemonium we offer free videos on the notes of high pitched tenor pans and 6 bass pans as well.<br/>
View our exciting animations and immerse yourself in the classy, graceful sounds of our national instrument.<br/>
Click on the type of pan you would like to learn about underneath to get started </b> <br/> <br/>  <br/> 
						
	</div>
 <br/> <br/>  <br/> 
 
 <!-- used to naviget to another page in the site-->
 <button class = "button"><a href = "TenorPan.html"> Go to Tenor Pan </button>
 
 <hr>
 
 <footer> 
 
 <!-- states the copyrights of the page-->
 <p class = "footer"> © 2017 PANdemonium. All Rights Reserved. Designed by Sookdeo Technology Services Limited </p>
 
 </footer>

</body>
</html>


<!-- tenor page -->
<!DOCTYPE html>
<html>
<head>
<!-- pulls css styling from a file called css-->
<link rel="stylesheet"  href="css.css"/>

 <meta name="viewport" content="width=device-width, initial-scale=1">
 <!-- allows the use of bootstrap-->
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
   <!-- allows the use of jquery-->
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
   <!-- allows the use of javascript-->
   <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  

  <!-- javascript which creates a function -->
  <!-- the function changes the id of the video selected -->
<script language="javascript" type="text/javascript"> 
function changevid(buttonlink){ 
document.getElementById('change').src = buttonlink;
}
</script>
</head>

<!-- pulls from a section in the css file labeled body-->
<body class = "body">

<!-- contains the header for the page and also pulls from a css secton called div2-->
 <div class = "div2">	  
 <!-- contains the site logo and its heading for the entire page--> 
 <p class = "p"> <img src="pan logo.jpg " alt="Photo of hibiscus" width ="150px" align = "center"> PANdemonium </p>
 </div>
 
<!-- each button clicked calles the function and changes the video displayed-->
<!-- styling is also taken from the section called notebuttons in the css file-->
 <div class = "notebuttons">
 <button class = "each" onClick="changevid('C4.ogv')">C4</button>
<button class = "each" onClick="changevid('G4.ogv')">G4</button>
<button class = "each" onClick="changevid('D4.ogv')">D4</button>
<button class = "each" onClick="changevid('A4.ogv')">A4</button>
<button class = "each"onClick="changevid('E4.ogv')">E4</button>
<button class = "each" onClick="changevid('B4.ogv')">B4</button>
<button class = "each" onClick="changevid('F#4.ogv')">F#4</button>
<button class = "each" onClick="changevid('C#4.ogv')">C#4</button>
<button class = "each" onClick="changevid('G#4.ogv')">G#4</button>
<button class = "each" onClick="changevid('Eb4.ogv')">Eb4</button>
<button class = "each" onClick="changevid('Bb4.ogv')">Bb4</button>
<button class = "each" onClick="changevid('F4.ogv')">F4</button>
<button class = "each" onClick="changevid('F#5.ogv')">F#5</button>
<button class = "each" onClick="changevid('B5.ogv')">B5</button>
<button class = "each" onClick="changevid('E5.ogv')">E5</button>
<button class = "each" onClick="changevid('A5.ogv')">A5</button>
<button class = "each" onClick="changevid('D5.ogv')">D5</button>
<button class = "each" onClick="changevid('G5.ogv')">G5</button>
<button class = "each" onClick="changevid('C5.ogv')">C5</button>
<button class = "each" onClick="changevid('F5.ogv')">F5</button>
<button class = "each" onClick="changevid('Bb5.ogv')">Bb5</button>
<button class = "each" onClick="changevid('Eb5.ogv')">Eb5</button>
<button class = "each" onClick="changevid('G#5.ogv')">G#5</button>
<button class = "each" onClick="changevid('C#5.ogv')">C#5</button>
<button class = "each" onClick="changevid('C#6.ogv')">C#6</button>
<button class = "each" onClick="changevid('E6.ogv')">E6</button>
<button class = "each" onClick="changevid('D6.ogv')">D6</button>
<button class = "each" onClick="changevid('C6.ogv')">C6</button>
<button class = "each" onClick="changevid('Eb6.ogv')">Eb6</button>
<button class = "each" onClick="changevid('anthem.ogv')">National Anthem</button>
</div>  



<!-- this plays the videos on screen and pulls them from the source indicaated-->
<video controls id = "change" width = "500" height = "500" align = "center">
  <source src="C4.ogv" id="change" type="video/mp4"></source>
  <source src="D4.ogv" id="change" type="video/mp4"></source>
  <source src="G4.ogv" id="change" type="video/mp4"></source>
  <source src="A4.ogv" id="change" type="video/mp4"></source>
  <source src="E4.ogv" id="change" type="video/mp4"></source>
  <source src="B4.ogv" id="change" type="video/mp4"></source>
  <source src="F#4.ogv" id="change" type="video/mp4"></source>
  <source src="C#4.ogv" id="change" type="video/mp4"></source>
  <source src="G#4.ogv" id="change" type="video/mp4"></source>
  <source src="Eb4.ogv" id="change" type="video/mp4"></source>
  <source src="Bb4.ogv" id="change" type="video/mp4"></source>
  <source src="F4.ogv" id="change" type="video/mp4"></source>
  <source src="F#5.ogv" id="change" type="video/mp4"></source>
  <source src="B5.ogv" id="change" type="video/mp4"></source>
  <source src="E5.ogv" id="change" type="video/mp4"></source>
  <source src="A5.ogv" id="change" type="video/mp4"></source>
  <source src="D5.ogv" id="change" type="video/mp4"></source>
  <source src="G5.ogv" id="change" type="video/mp4"></source>
  <source src="C5.ogv" id="change" type="video/mp4"></source>
  <source src="F5.ogv" id="change" type="video/mp4"></source>
  <source src="Bb.ogv" id="change" type="video/mp4"></source>
  <source src="Eb5.ogv" id="change" type="video/mp4"></source>  
  <source src="G#5.ogv" id="change" type="video/mp4"></source>
  <source src="C#5.ogv" id="change" type="video/mp4"></source>
  <source src="C#6.ogv" id="change" type="video/mp4"></source>
  <source src="E6.ogv" id="change" type="video/mp4"></source>
  <source src="D6.ogv" id="change" type="video/mp4"></source>
  <source src="C6.ogv" id="change" type="video/mp4"></source>
  <source src="Eb6.ogv" id="change" type="video/mp4"></source>
  <source src="anthem.ogv" id="change" type="video/mp4"></source>
</video>




  <hr>
 
 <footer> 
  <!-- states the copyrights of the page-->
 <p class = "footer"> © 2017 PANdemonium. All Rights Reserved. Designed by Sookdeo Technology Services Limited </p>
 
 </footer>

</body>
</html>

<!-- css for entire site-->

/* this defines the body of the entire website*/
/* it also adds a background to the entire page*/
.body {
  margin: 0;
  padding: 0;
  background-image: url("background.jpg");
  background-position: center center;
}

/* this styles the header to the website*/
.div2{
	font-family: Monotype corsiva;
	text-align:center;
	font-size: 90px;
	background-color : white;
	height : 40%;
	color : LightSeaGreen;
	margin-bottom : 3%;
}

/* this styles the tenor botton which is seen at the bottom of the page*/
.button{
	display : inline-block ;
	background-color : LightSeaGreen ;
	font-size : 50px ;
	margin-left : 38%;
	margin-top : 5px;
	margin-bottom : 3%;
}

/* this styles the paragraph in the middle of the page which has the welcome greeting to the guests*/
.div1 {
	display : inline-block ;
    background-color: white;
    padding: 1%;
    margin-left: 10%;
	margin-top : 2%;
	margin-bottom : 2%;
	font-family : pristina;
	border : 1px LightSeaGreen;
	font-size : 25px;
	color : LightSeaGreen;
	text-align : center;
}

/* styles the footer of the page*/
.footer {
text-align : center;
color: LightSeaGreen;
font-size : 15px;
}

/* styles the div which the note buttons are contained in on the second page of the website*/
.notebuttons {
margin-top : 1%;
margin-left : 4%;
display : inline-block;
color: LightSeaGreen;
width : 30%;
height : 15%;
padding-top : 0;
font-size : 30px;
}

/* styles each individual note button on the second page of the site*/
.each {
margin-top : 1%;
margin-bottom : 1%;
margin-left : 1%;
margin-right : 1%;
}