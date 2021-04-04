# NJ
# Code for the Sample Project done in HTML and Bootstrap method.
<!DOCTYPE html>
<html>
	<head> 
		<title> My Wonder Page </title>
		<meta name="Game" content="Gaming Notebook">
		<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
		<link rel="stylesheet" href="style2.css" type="text/css">
		<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato"><!--linking icons-->
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"><!--linking icons-->
	</head>
	
	<body>
		<div align="justify">
		<!--Section 1 Navigation Bar-->
		<!-- Navbar (sit on top) -->
		<div class="w3-top">
			<div class="w3-bar w3-black w3-card">
				<a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
				<a href="#" class="w3-bar-item w3-button w3-padding-large">HOME</a>
				<a href="#" class="w3-bar-item w3-button w3-padding-large w3-hide-small">GUIDE</a>
				<a href="#" class="w3-bar-item w3-button w3-padding-large w3-hide-small">SHOP</a>
				<a href="#" class="w3-bar-item w3-button w3-padding-large w3-hide-small">CONTACT</a>
				<div class="w3-dropdown-hover w3-hide-small">
					<button class="w3-padding-large w3-button" title="More">MORE <i class="fa fa-caret-down"></i></button>     
					<div class="w3-dropdown-content w3-bar-block w3-card-4">
						<a href="#" class="w3-bar-item w3-button">Gaming Merchandise</a>
						<a href="#" class="w3-bar-item w3-button">Gaming Furnitures</a>
						<a href="#" class="w3-bar-item w3-button">Gaming Accessories</a>
					</div>
				</div>
				<a href="" class="w3-padding-large w3-hover-red w3-hide-small w3-right"><i class="fa fa-search"></i></a>
			</div>
		</div>
		
		<!--Section 2-->
		<!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
		<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
			<a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">GUIDE</a>
			<a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">SHOP</a>
			<a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">CONTACT</a>
			<a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">MORE</a>
		</div>
		<br>
		<br>
		<!--Header Section-->
		<div class="w3-content" style="max-width:1000px;margin-top:6px"><!--page content-->
		<div class="w3-bar w3-black w3-card">
			<h1 class="w3-center"><b>NOTEBOOK: A Game Changer</b></h1>
		</div>
		
		
		
		<!-- Automatic Slideshow Images -->
		<div class="mySlides w3-display-container w3-center">
			<img src="https://images-na.ssl-images-amazon.com/images/I/81Nox3hzQaL.jpg" style="width:75%">
			<div class="w3-display-bottommiddle w3-container w3-text-black w3-padding-32 w3-hide-small">
				<h3><b>Asus ROG GL5X</b></h3> 
			</div>
		</div>
		<div class="mySlides w3-display-container w3-center">
			<img src="https://images-na.ssl-images-amazon.com/images/G/01/netgear/2500acerpredator.jpg" style="width:75%">
			<div class="w3-display-bottommiddle w3-container w3-text-black w3-padding-32 w3-hide-small">
				<h3><b>Acer Predator</b></h3>
			</div>
		</div>
		<div class="mySlides w3-display-container w3-center">
			<img src="https://www.pbtech.co.nz/imgprod/N/B/NBKHNB150036.jpg" style="width:75%">
			<div class="w3-display-bottommiddle w3-container w3-text-black w3-padding-32 w3-hide-small">
				<h3><b>HP Pavilion 15-CX</b></h3>    
			</div>
		</div>
		
		
		<!--About Section-->
		<div class="w3-container">
			<p>A laptop, also called a notebook computer or simply a notebook, is a small, portable personal computer with a "clamshell" form factor, having, typically, a thin LCD or LED computer screen mounted on the inside of the upper lid of the "clamshell" and an alphanumeric keyboard on the inside of the lower lid. The "clamshell" is opened up to use the computer. Laptops are folded shut for transportation, and thus are suitable for mobile use. Its name comes from "lap", as it was deemed to be placed for use on a person's lap. Although originally there was a distinction between laptops and notebooks, the former being bigger and heavier than the latter, as of 2014, there is often no longer any difference. Laptops are commonly used in a variety of settings, such as at work, in education, in playing games, Internet surfing, for personal multimedia and general home computer use.</p>
		</div>
		
		<!--History Section-->
		<div class="w3-bar w3-black w3-container">
			<h2 class="w3-center">EVOLUTION OF GAMING NOTEBOOKS</h2>
		</div>
		<div class="w3-container">
			<p>Historically gaming computers had several distinct hardware components that set them apart from a typical PC. The push for better graphics began with color fidelity, from display systems such as CGA eventually graduating to VGA, which was adopted for the mass market. Gaming also led the push for the adoption of sound cards, a component that is now commonly integrated onto motherboards.
			In the 1980s, several non-IBM PC compatible platforms gained a measure of popularity due to advanced graphics and sound capabilities, including the Commodore 64 and Amiga. Video game developers of the time targeted these platforms for their games, though typically they would later port their games to the more common PC and Apple platforms as well. The MSX was also popular in Japan, where it preceded the video game console revolution. Japan also had several other popular gaming computers during the 1980s to early 1990s, including the very popular PC-88 and PC-98 as well as the powerful X68000 and FM Towns.
			By 1993, PC compatibles were the standard for gaming. Computer Gaming World stated in January.</p>
		</div>
		
		<!--Guide section-->
		<div class="w3-bar w3-black w3-container">
			<h2 class="w3-center">HOW TO CHOOSE FOR A GAMING NOTEBOOK</h2>
		</div>
		<div class="w3-container">
			<p>While the desktop remains supreme among many PC gamers, sometimes you just need something a bit more portable. A gaming laptop is a rig on the go, with the power to play games in a size you can take with you.
			But when you’re buying a gaming laptop, you’re not just looking at specs. You’re looking at a whole computer, including a built-in keyboard and display. Here, we explain all of the decisions you’ll have to make when buying a gaming laptop so you can get the best one for your needs and budget.</p>
			<b>Quick Tips:</b>
			<li><b><em>Get a good GPU:</b></em> Most games are GPU-dependent, and you can’t upgrade these in laptops. A good GPU will ensure your laptop plays games at high settings for a few years.</li>
			<li><b><em>Consider upgrading later:</b></em> Many, though not all, gaming laptops let you upgrade your RAM and storage.</li>
			<li><b><em>Pick resolution or speed:</b></em> The fastest 144Hz displays only come at 1920 x 1080 resolution right now, so a 4K screen will be slower.</li>
			<li><b><em>Get a good keyboard:</b></em> You don’t want to play your games on something mushy or stiff.</li>
			<li><b><em>Battery life will probably be bad:</b></em> Very few gaming notebooks get 8 hours or more on a charge, and you need the power supply to get the best performance anyway.</li>
			<br>
		</div>
		<br>
		
		
		<!-- List Section-->
		<div class="w3-bar w3-black w3-container">
			<h2 class="w3-center"> SOME BEASTS </h2>
		</div>
		<div class="w3-container">
			<p> Some of the beasts hanging out at market are as follows</p>
			<li> MSI GS65 Stealth Thin </li>
			<li> Razer Blade 15 </li>
			<li> Acer Predator </li>
			<li> Gigabyte 15.6" AERO 15 </li>
			<li> Asus ROG Series </li>
		</div>
		<br>
		<br>
		
		<!--2nd image section-->
		<div class="w3-display-container w3-center">
			<img src= "https://images.anandtech.com/doci/12608/gigabyte_aero_15_1.jpg" style="width:75%">
		</div>
		
		<!--The Contact Section-->
		<div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
		<h2 class="w3-wide w3-center">CONTACT</h2>
		<p class="w3-opacity w3-center"><i>Interested? Drop an appoin!</i></p>
		<div class="w3-row w3-padding-32">
		<div class="w3-col m6 w3-large w3-margin-bottom">
			<i class="fa fa-map-marker" style="width:30px"></i> Hyderabad, India<br>
			<i class="fa fa-phone" style="width:30px"></i> Phone: +91 9791178716<br>
			<i class="fa fa-envelope" style="width:30px"> </i> Email: nibjyoti@yandex.com<br>
		</div>
		<div class="w3-col m6">
			<form action="/action_page.php" target="_blank">
			<div class="w3-row-padding" style="margin:0 -16px 8px -16px">
				<div class="w3-half">
				<input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
				</div>
				<div class="w3-half">
				<input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
				</div>
			</div>
			<input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
			<button class="w3-button w3-black w3-section w3-right" type="submit">SEND</button>
			</form>
			</div>
		</div>
		</div>
		
		<!-- Footer -->
		<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
			<div class="w3-xlarge w3-section">
			<i class="fa fa-facebook-official w3-hover-opacity"></i>
			<i class="fa fa-instagram w3-hover-opacity"></i>
			<i class="fa fa-snapchat w3-hover-opacity"></i>
			<i class="fa fa-pinterest-p w3-hover-opacity"></i>
			<i class="fa fa-twitter w3-hover-opacity"></i>
			<i class="fa fa-linkedin w3-hover-opacity"></i>
		</footer>
		
		<!--Javascript Part-->
		<script>
		// Automatic Slideshow - change image every 3 seconds
			var myIndex = 0;
			carousel();

			function carousel() {
				var i;
				var x = document.getElementsByClassName("mySlides");
				for (i = 0; i < x.length; i++) {
					x[i].style.display = "none";  
				}
				myIndex++;
				if (myIndex > x.length) {myIndex = 1}    
					x[myIndex-1].style.display = "block";  
				setTimeout(carousel, 3000); //3000 means 3 secs   
			}

			// Used to toggle the menu on small screens when clicking on the menu button
			function myFunction() {
			var x = document.getElementById("navDemo");
			if (x.className.indexOf("w3-show") == -1) {
				x.className += " w3-show";
				} else { 
				x.className = x.className.replace(" w3-show", "");
				}
			}

			// When the user clicks anywhere outside of the modal, close it
			var modal = document.getElementById('ticketModal');
			window.onclick = function(event) {
			if (event.target == modal) {
				modal.style.display = "none";
			}
			var imgArray = [
			'img/slider1.jpg',
			'img/slider2.jpg',
			'img/slider3.jpg'],
			curIndex = 0;
			imgDuration = 3000;

			function slideShow() {
			document.getElementById('slider').src = imgArray[curIndex];
			curIndex++;
			if (curIndex == imgArray.length) { curIndex = 0; }
				setTimeout("slideShow()", imgDuration);
			}
		}
		</script>

		</div>	
	</body>
</html>
