# ayush.github.io
@@ -0,0 +1,602 @@
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content=
		"width=device-width, initial-scale=1.0">
		
	<style>
		.upperhead{
		margin-left: -10px;
		margin-top:  -49px;
		margin-bottom: -5;
width:100vw;
height: 37px;
    background-color: black;
		}
.upperhead img{
	margin-left: 1110px;
	width: 200px;
	height: 120px;
	margin-top: -95px;
}
		
		.add h4{
			margin-left: 550px;
			color: whitesmoke;
			margin-top: -30px;
			font-family: arial;
		}


		.navbar {
			width: 110vw;
			height: 100px;
		margin-left: -20px;
		margin-top: -5;



			border-radius: 15px;
			background-color: #363636;

		}

		.navbar img {
			display: block;
			width: 200px;
			height: 60px;
			margin-left : 19px;
			margin-top: -75px;
             

		}
		.navbar marquee{
          color: white;
          margin-top: 10px;
          font-family: arial;
          font-size: 18px;
          background-color: black;
          height: 33px;
		}
		
		.topnav{
            float: center;
            color: black;
            text-align: right;
            margin-left: -30px;
           background-color: #363636;
            width: 100vw;
            height: 40px;
            padding: 30px;
            text-decoration: none; 
            font-size: 21px;
            border-radius: 15px;
            color: white;
		}
		.topnav :hover{
   background-color: none;
   border-radius: 20px;
   
         color: black;
		}

		.bca{
   font-family: rockwell;
		}
		.sqaure{
			width: 100vw;
			height: 250px;
			color: yellow;
			margin-left: 50px;
			background-color:white;
			

		}
	.insqaure{
		    width: 400px;
			height: 250px;
			color: yellow;
			border-radius: 30px;
			background-color: #EDBA16;

	}
	
	.insqaure2{
		  width: 400px;
			height: 250px;
			color: yellow;
			margin-left: 400px;
border-radius: 30px;
			background-color: #F8E3A2;
	}
	.insqaure3{

  width: 400px;
			height: 250px;
			color: yellow;
			margin-left: 400px;
border-radius: 30px;
			background-color: #EDBA16;

	 }

	 .os h2{
margin-top: -230px;
margin-left: 50px;
color: black;
	 }
	 .os ol{
	 	color: black;
	 	margin-left: 50px;
	 	}
	 .dcd h2{
	 	margin-top: -160px;
margin-left: 450px;
text-align: left;
color: black;
	 }

	 .dcd ol {
color: black;
margin-left: 400px;
	 }

	 .web{ 
	 	color: black;
	 
	 	margin-left: 880px;
	 	margin-top: -250px;
	  }

	  .btech{
	  	margin-top: 115px;
	  	font-family: arial;}

	  	.sqaure4{
			width: 100vw;
			height: 250px;
			color: yellow;
			margin-left: 50px;
			background-color:white;
			

		}
	.insqaure5{
		    width: 400px;
			height: 250px;
			color: yellow;
			background-color: #EDBA16;
			border-radius: 30px;
	}
	.insqaure6{
		  width: 400px;
			height: 250px;
			color: yellow;
			margin-left: 400px;
border-radius: 30px;
			background-color: #F8E3A2;
	}
	.insqaure7{

  width: 400px;
			height: 250px;
			color: yellow;
			margin-left: 400px;
border-radius: 30px;
			background-color: #EDBA16;

	 }
.image img{
	margin-top: 28px;
width: 100vw;
height: full;
margin-left: -10px;
}
.py{
color: black;
margin-top: -235px;

}

.slider {
  width: 400px;
  text-align: center;
  overflow: hidden;
}

.slides {
  display: flex;
  
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  
  
  
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
  
  /*
  scroll-snap-points-x: repeat(300px);
  scroll-snap-type: mandatory;
  */
}
.slides::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}
.slides::-webkit-scrollbar-thumb {
  background: black;
  border-radius: 10px;
}
.slides::-webkit-scrollbar-track {
  background: transparent;
}
.slides > div {
  scroll-snap-align: start;
  flex-shrink: 0;
  width: 400px;
  height: 300px;
  margin-left:  0px;
  border-radius: 50px;
  background: #EDBA16;
  transform-origin: center center;
  transform: scale(1);
  transition: transform 0.5s;
  position: relative;
  
  
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 100px;
}
.slides > div:target {
/*   transform: scale(0.8); */
}




.slider > a {
  display: inline-flex;
  width: 1.5rem;
  height: 1.5rem;
  background: skyblue;
  text-decoration: none;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin: 0 0 0.5rem 0;
  position: relative;
}
.slider > a:active {
  top: 1px;
}
.slider > a:focus {
  background: #000;
}


/*to cahnge position*/

.slider  {
color: black;
margin-left: 10px;
margin-top: 60px;
font-family: arial;

}
.slider div{
font-size: 15px;
text-align: left;
line-height: 4.0; }

.bac {
width: 1500px;
height: 350px;
background-color: yellow;
}

/*css of 2nd box*/



.slider2 {
  width: 400px;
  text-align: center;
  overflow: hidden;
}

.slides2 {
  display: flex;
  
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  
  
  
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
  
  /*
  scroll-snap-points-x: repeat(300px);
  scroll-snap-type: mandatory;
  */
}
.slides2::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}
.slides2::-webkit-scrollbar-thumb {
  background: black;
  border-radius: 10px;
}
.slides2::-webkit-scrollbar-track {
  background: transparent;
}
.slides2 > div {
  scroll-snap-align: start;
  flex-shrink: 0;
  width: 400px;
  height: 300px;
  margin-left: 50px;
  border-radius: 50px;
  background: #EDBA16;
  transform-origin: center center;
  transform: scale(1);
  transition: transform 0.5s;
  position: relative;
  
  
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 100px;
}
.slides2 > div:target {
/*   transform: scale(0.8); */
}




.slider2 > a {
  display: inline-flex;
  width: 1.5rem;
  height: 1.5rem;
  background: skyblue;
  text-decoration: none;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin: 0 0 0.5rem 0;
  position: relative;
}
.slider2 > a:active {
  top: 1px;
}
.slider2 > a:focus {
  background: #000;
}



.slider2  {
color: black;
margin-left: 130px;                /*asdasdasdasd*//*asdasdasdasd*//*asdasdasdasd*//*asdasdasdasd*/
margin-top: 100px;
font-family: arial;

}
.slider2 div{
font-size: 15px;
text-align: left;
line-height: 4.0; }

.slid {
	width: 1080px;
margin-top: -440px;
margin-left: 600px;}


.bsc{
margin-top: 150px;
margin-left: 20px;
color: black;
font-size: 32px;
}

.tech {
	margin-top: -120px;
	margin-left: 800px;
	
	color: black; 
font-size: 32px;
}
	</style>



</head>

<body>
	<div class=upperhead> 
<h4>	&ensp;&ensp;call- 989845151</h4>
	<div class="add"><h4>AMITY UNIVERSITY LUCKNOW -226010</h4></div>
	<img src="C:\Users\RODEZWEB\Downloads\icon.png">
	</div>

	<div class="navbar">
		<div class="topnav">
		<a class="topnav" href="#home"> Home</a>
		<a class="topnav" href="#home"> Contact</a>
		<a class="topnav" href="#home"> Our courses</a>
		<a class="topnav" href="#home"> Our gallery</a>
	</div>
		<img src="C:\Users\RODEZWEB\Desktop\logo.png" alt="Logo image">
		<marquee >ADMISSION OPEN!!! JOIN NOW!!! BACHELORS OF COMPUTER APPLICATION AND BTECH(CS)</marquee>
	</div>
			<div class="image"> <img src="C:\Users\RODEZWEB\Desktop\banner1.jpg"></div>

	<br><br>
	<div class="bca">
		<h1> Bachelors of computer application</h1>
		<h2 style="color: blue;"> course code- 10112</h2>
<h2 style="text-align: center;">Semester 1</h2>
	</div>

	<div class="sqaure">

		<div class=insqaure>

			<div class="insqaure2"> 
				<div class="insqaure3"> </div> 
			</div> 

				
		
			</div>

<div class="os"><h2>Operating system</h2>
	<ol><b><li>History of os</li>
 			<li>Introduction to operating system
 				<li>Architecture of os</li>
 				<li>types of os</li>
 				<li>what is an operating system</li>
	     </ol>

</div>
<div class="dcd"><h2>Digital electronics</h2>
<ol><li>number system</li>
		<li>binary conersions</li>
		<li>adders</li>	
		<li>subtractor</li>
		<li>multiplexar</li></ol>
</div>


</div>
	
	<div class="web"> <h2>Web Technologies</h2>
	<ol><li>history of html</li>
			<li>what is html</li>
			<li>what is CSS</li>
			<li>what is javascript</li>
			<li>types of tags in html</li></ol>
		</div>

			<div class="btech">
		<h1> Bachelors of technology(CS)</h1>
		<h2 style="color: blue;"> course code- 101133</h2>
<h2 style="text-align: center;">Semester 1</h2>
	</div>

	<div class="sqaure4">

		<div class=insqaure5>

			<div class="insqaure6"> 
				<div class="insqaure7"> </div> 
			</div> 

			<div class="py">
				<ol><li>what is python</li>
						<li>data types</li>
						<li>variables and constants</li>
						<li>strings</li>
						<li>number system</li>
						<li>graphics programming</li>
						<li>linklist</li>
					</ol>
				</div>

<div>
<div class="bsc">bachelors of science(IT)<br><h3 style="color: blue; font-size: 25px;">course code -104413</h3></div>
				<div class="tech">bachelor of technology(EC)</div>

		</div>		
				
				<div class="slider">
  
  <a href="#slide-1">1</a>
  <a href="#slide-2">2</a>
  <a href="#slide-3">3</a>
  <a href="#slide-4">4</a>
  <a href="#slide-5">5</a>

  <div class="slides">
    <div id="slide-1">
      <ol><li>Aerodynamics and Fluid Mechanics</li>
      	<li>Biomechanics.</li>
      	<li>Combustion and Energy Systems</li>
      	<li>Design and Manufacturing</li>
      </ol>
    </div>
    <div id="slide-2">
      <ol><li>Dynamics and Control</li>
      	<li>Materials and Structures</li>
      	<li>Vibrations, Acoustics </li>
      	<li>Combustion and Energy Systems</li>
      	<li>Biomechanics.</li>
      </ol>

    </div>
    <div id="slide-3">
      3
    </div>
    <div id="slide-4">
      4
    </div>
    <div id="slide-5">
      5
    </div>
  </div>
  
</div>


<!-- 2nd box-->
<div class="slid">
<div class="slider2">
<a href="#slide-6">1</a>
  <a href="#slide-7">2</a>
  <a href="#slide-8">3</a>
  <a href="#slide-9">4</a>
  <a href="#slide-10">5</a>

  <div class="slides2">
    <div id="slide-6">
      <ol><li>Aerodynamics and Fluid Mechanics</li>
      	<li>Biomechanics.</li>
      	<li>Combustion and Energy Systems</li>
      	<li>Design and Manufacturing</li>
      </ol>
    </div>
    <div id="slide-7">
      <ol><li>Dynamics and Control</li>
      	<li>Materials and Structures</li>
      	<li>Vibrations, Acoustics </li>
      	<li>Combustion and Energy Systems</li>
      	<li>Biomechanics.</li>
      </ol>

    </div>
    <div id="slide-8">
      3
    </div>
    <div id="slide-9">
      4
    </div>
    <div id="slide-10">
      5
    </div>
  </div>
</div>
</div>


</body>

</html>
