<!DOCTYPE html>
<html>
<head>
	<title>Dove</title>

	<style>
	body{
		background-image: url(https://images.pexels.com/photos/3073694/pexels-photo-3073694.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260);
		background-size: 95%;
		background-position: cover;
	}
	header:before{	
			content:" ";
			position: absolute;
			top:0;
			left:0;
			width: 100%;
			height: 100%;
			z-index: -1;
			opacity: 0.5;
			text-align: center;

		}
		.navigation{
			align-items: : center;
			font-family: 'Bree Serif', Serif;
			font-size: 20px;
			display: center;
		}
		li{

			list-style: none;
			padding: 6px 8px;
		}
		section{
			height: 444px;
			margin: 3px 230px;
			display: flex;
			
			flex-direction: column;
			align-items: center;
			justify-content: center;
		}
		h1{
			font-size: 3rem;
			text-align: center;
			left: 500px;
			top: 500px;
			

		}
		p{
			text-align: center;
		}

		button{
			font-color: white;
			align-items: center;
			background-color: black;
			color: black;
			margin: 2px 3px;
			pointer-events: visiblePainted white;
			border: white;
		}
                a{
			
			color: white;
		}
		/*section:after{
			content: "This is a content"
		}*/
	</style>		
</head>
<body>

	<section>

		<h1>Welcome to My Bubu!</h1>
	</section>
	<header>
		<nav class="navbar">
			<ul class="navigation">
				<button><li class="item"><a href="Message-1.html">Message-1</a></li></button>
				<button><li class="item"><a href="Message-2.html">Message-2</a></li></button>
				<button><li class="item"><a href="Message-3.html">Message-3</a></li></button>	
				
				</ul>	
			</nav>
		</header>


		


	
</body>
</html>
