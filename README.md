<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Assignment Solution for module 2</title>
	<link rel="stylesheet" href="bootstrap.min.css">
	<link rel="stylesheet" href="Styles.css">
	<style>
		*
		{
			box-sizing: border-box;
			margin: 0px;
			padding: 0px;
		}
		
	</style>
</head>
<body>
	<h1>Our Menu</h1>
	<section id="p">
	<div class="container-fluid">
		<div class="row">
			<div class="col-md-4">
				<div id="p1">
					<h2 class="Subhead1">Paneer Tikka Masala</h2>
					<p>Paneer tikka is an Indian dish made from chunks of paneer marinated in spices and grilled in a tandoor.It is a vegetarian alternative to chicken tikka and other meat dishes.It is a popular dish that is widely available in India and countries with an Indian diaspora.
					</p>	
				</div>	
			</div>
			
				
			<div class="col-md-4">
				<div id="p2">
					<h2 class="Subhead2">Mushroom Gravy</h2>
					<p>Mushroom gravy is a simple, usually red sauce that can be composed from stock (beef is typical, but chicken may be used), roux (a mixture of equal parts butter and flour to thicken), and mushroom base.It can also be enhanced with mace, to add a delicate nutmeg flavor.
					</p>
				</div>	
			</div>
			<div class="col-md-4">
				<div id="p3">
					<h2 class="Subhead3">Dum Aloo</h2>
					<p>Dum Aloo (also spelled as Dam Aloo) or (Hindi: दम आलू) is a potato based dish from the Kashmir Valley, in the Indian state of Jammu and Kashmir. The potatoes, usually smaller ones, are first deep fried, then cooked slowly at low flame with spices.Dum Aloo is a popular recipe cooked throughout India.
					</p>
				</div>		
			</div>		
		</div>
	</div>	
	</section>
</body>
</html>


CSS file:
.row
{
	margin-bottom: 15px; 
}
		
h1
{
	margin-top: 50px;
	margin-bottom: 150px;
	text-align: center;
	font-style: italic;
	color: black;			
}

p
{
	padding: 10px;
	position: relative;
	width: 100px
	height: 100px;	
	margin: 20px;
	margin-top: 20px;
	display: block;
	color: black;
	font-family: Helvetica;
	font-size: 20px;
}		


.Subhead1
{
	background-color: pink;
	padding: 10px;
	margin-left: 125px;
	width: 350px;	
	border: 5px solid black;
	display: block;
	font-style: italic;
	text-align: right; 
}

.Subhead2
{
	background-color: red;
	padding: 10px;
	margin-left: 175px;
	border: 5px solid black;
	width: 300px;	
	display: block;
	font-style: italic bold;
	text-align: right; 
}

.Subhead3
{
	background-color: orange;
	padding: 10px;
	margin-left: 275px;
	width: 200px;	
	border: 5px solid black;
	display: block;
	font-style: italic ;
	text-align: right; 
}

#p
{
	display: -webkit-box;
	-webkit-box-orient:horizontal;
}

#p1
{
	border: 5px solid black;
	background-color: gray;
}

#p2
{
	border: 5px solid black;
	background-color: gray;
}

#p3
{
	border: 5px solid black;
	background-color: gray;
}

		
