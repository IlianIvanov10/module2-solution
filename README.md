Please note that few things, that I've been using for this project, were taught to me in university and it is easier for this way. Thank you!

<!DOCTYPE html>
<html>
<head>
	<title></title>
	 <link rel="stylesheet" href="style.css">
	 <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
	<h1>Our Menu</h1>
    <div class="menu">	
    	<div class="menu2">
			<div class="container col-lg-4 col-md-3 col-sm-4">
				<div class="chicken">
						Chicken
				</div>
				<p>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
				</p>
			</div>
			<div class="container col-lg-4 col-md-3 col-sm-4">
				<div class="beef">
						Beef
				</div>
				<p>
					Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
				</p>
			</div>
		</div>
		<div class="container col-lg-4 col-md-6 col-sm-4">			
			<div class="sushi">
				Sushi
			</div>
			<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
			cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
			proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
		</div>
	</div>
</body>
</html>
.container{
	margin: 15px; 
	padding: 10px;
	border: 1px solid black;
	background-color: #80ff80;
	float: center;
	position: relative;
}

.chicken{
	text-align: center;
	height: 8%;
	width: 130px;
	background-color: #ffff4d;
	border: 1px solid black;
	position: absolute;
	left: 54.3%;
	bottom: 91.5%;
}
.beef{
	text-align: center;
	height: 8%;
	width: 130px;
	background-color: #ff3333;
	border: 1px solid black;
	position: absolute;
	left: 54.3%;
	bottom: 91.5%;
}
.sushi{
	text-align: center;
	height: 8%;
	width: 130px;
	background-color: #6699ff;
	border: 1px solid black;
	position: absolute;
	left: 54.3%;
	bottom: 91.5%;
}

@media (min-width: 992px) {
.menu{
	display:flex;
	flex-direction: row;
}
.menu2{
	display: flex;
	flex-direction: row;
}
  .col-lg-1 {
    width: 33.33%;
  }
  .col-lg-2 {
    width: 66.66%;
  }
  .col-lg-3 {
    width: 99.99%;
  }
}
@media (min-width: 768px) and (max-width: 991.99px) {
  .menu2{
	display:flex;
	flex-direction: row;
}
  .col-md-1 {
    width: 33.33%;
  }
  .col-md-2 {
    width: 66.66%;
  }
  .col-md-3 {
    width: 99.99%;
  }
}

@media (max-width: 767.99px) {
	.col-sm-1, .col-sm-2, .col-sm-3{
		float: left;
		margin: 15px auto;
	}
  .col-sm-1 {
    width: 33.33%;
  }
  .col-sm-2 {
    width: 66.66%;
  }
  .col-sm-3 {
    width: 99.99%;
  }
}
h1{
	text-align: center;
}
