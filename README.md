# 7vD-web<!DOCTYPE html>
<html>
<head>
	<meta charset ="utf-8">
	<meta name="view poirt" content="width=device-width,initial-scale=1.0">
	<title> 7vD  </title>
	<link rel="stylesheet" href="./Css/styles.css">
	<link rel="stylesheet" href="./Css/styles2.css">
</head>
<body>
<!--Custom JavaScript file-->
	<script src="./js/java.js"></script>
	
	<!----------------Custom Navigation -------------------->
 <nav class="nav">
	<div class="nav-menu flex-row">
		<div class="nav-brand">
			<a href="#" class="text-gray">7vD</a>
		</div>
	</div>
		
		
	
 
 </nav>
	
	
	
	<!-------------x-----Custom Navigation-------x----------->
	
	<div class="Container">
		<div Class="nav-Wrapper">
			<div class="left-side">
				<div class="nav-link-wrapper">
					<a href="index.html">HOME</a>
				</div>
				<div class="nav-link-wrapper">
					<a href="about.html">ABOUT</a>
				</div>
			</div>
					<div class="right-side">
					<div class"brand">
				<div> 7vD</div>
				<button class="btn btn--radius-2 btn--blue" type="Mixtape">Mixtape</button>
				</div>	
					</div>
		 
		</div>
		
		
		
		
		<div class="content-wrapper">
				<div class="portfolio-items-wrapper">
							<div class="portfolio-item-wrapper">
								<div class="portfolio-img-backround" style ="background-image:url(C:\Users\Tumelo\Desktop\Webside\Photo)">
								</div>
							</div>
							<div class="img-text-wrapper">
								<div class="logo-wrapper">
									<img src= "Photo/back.jpg"
								</div>
								<div class ="subtitle">I built the Lord'Verb Online website for Mixtape sharing, Bookings and further updates</div>
							</div>
							
				</div>
		</div>
	</div>
	
</body>



</html>


==CSS CODE ==


/* Master Styles */
body {
	font-family: "Laoto", sans-serif;
	margin: 0px;
	
}

.Container {
	
	width: 100%;
	height: 500px;
	position: absolute;
}
/*Nav Styles*/
.nav-Wrapper {
	 display : flex;
	 justify-content: space-between;
	 padding: 38px;
 }
 
.left-side {
	 display : flex;
 }
 
 .nav-Wrapper > .left-side >  div {
	 
	 margin-right: 20px;
	 font-size: 0.9em;

	 text-transform: uppercase;
 }
 
 
.nav-link-wrapper {
	 
	 height: 22px;
	 border-bottom: 1px solid transparent;
	 transition: border-bottom 0.5s;
 }
.nav-link-wrapper a {
	
	color: #8a8a8a;
	text-decoration: none;
	transition: color 0.5s;
	
}

.nav-link-wrapper: hover {
	
	border-bottom: 1px solid black;
	
}

.nav-link-wrapper a: hover {
	color : black;
	
}
/* Portfolio Styles*/

.portfolio-items-wrapper{
	
	display: grid;
	grid-template-columns: 1fr;
}

.portfolio-item-wrapper{
	position: relative;
}

.portfolio-img-background{
	height: 350px;
	width: 100%;
	background-size: cover;
	background-position: cover;
	background-repeat: no-repeat;
}

.image-text-wrapper{
	
	position: absolute;
	top: 0;
	display: flex;
	flex-direction: column;
	justify-content: centre;
	align-items: centre;
	height: 100%;
	text-align: centre;
	padding-left: 100px;
	padding-right: 100px;
}
/*About Page*/

.two-column-wrapper {
	display: grid;
	grid-template-columns: 1fr 1fr;
		
}
.profile-image-wrapper img{
	
	width: 50%;
	
}
.profile-content-wrapper h1 {
	
	
	color: lightseagreen;
}
 
 ===html code ===
 
 <!DOCTYPE html>
<html>
<head>
	<meta charset ="utf-8">
	<meta name="view poirt" content="width=device-width,initial-scale=1.0">
	<title> 7vD  </title>
	<link rel="stylesheet" href="./Css/styles2.css">
</head>
<body>
<!--Custom JavaScript file-->
	<script src="./js/java.js"></script>
	
	<!----------------Custom Navigation -------------------->
 <nav class="nav">
	<div class="nav-menu flex-row">
		<div class="nav-brand">
			<a href="#" class="text-gray">7vD</a>
		</div>
		<div class="toggle-collpase">
			<div class="toggle-icons">
				<i class="fas fa-bars"></i>
			</div>
		</div>
		<div>
			<ul class="nav-items">
				<li class="nav-link">
					<a href="#">Home</a>
				</li>
				<li class="nav-link">
					<a href="#">Mixtapes</a>
				</li>
				<li class="nav-link">
					<a href="#">About</a>
				</li>
				<li class="nav-link">
					<a href="#">Contact Us</a>
				</li>
			</ul>
		</div class="social text-gray">
			<a href="#">F</a>
			<a href="#">T</a>
			<a href="#">I</a>
		</div>	 
		</div>
		</div>
		
	</div>
		
 </nav>

	<!-------------x-----Custom Navigation-------x----------->
	
	
	
	
</body>


</html>
 
 
 
 
 
 
 
