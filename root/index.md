<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial-scale=1">
	<link rel="stylesheet" type="text/css" href="bootstrap.min.css">
	<script src="jquery-3.4.1.min.js"></script>
	<script src="bootstrap.min.js"></script>
	<script src="MainPage.js"></script>
	<script src="C:\MyCDrive\Suhanee\SuhuLearn\Angular JS\angular.min.js"></script>
	<script src="home.js"></script>
	<link rel="stylesheet" type="text/css" href="HomePage.css">

</head>


<body>
	<div class="container-fluid">

		<!----Navigation Bars------------------------------------------------------>
		<div class="container">
			<nav class="navbar navbar-expand-md nav_bg fixed-top">
				<a class="navbar-brand logo" href="#home"><b>The Coffee <br> Day</b></a>
				<!---------------Nav button-------------->
				<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#colNavBar">
					<span class="navbar-toggler-icon" style="font-size:35px;padding: 3px;">&#9776</span>
				</button>
				<!--------------------------------------->

				<!---------------Nav Bar----------------->
				<div class="collapse navbar-collapse" id="colNavBar">
					<ul class="navbar-nav ">
						<li class="nav-item">
							<a class="nav-link" href="#home" id="nav1">Home</a>
						</li>

						<li class="nav-item">
							<a class="nav-link" href="#menu" id="nav2">Menu</a>
						</li>

						<li class="nav-item">
							<a class="nav-link" href="#reservation" id="nav3">Reservation</a>
						</li>

						<li class="nav-item" id="nav4">
							<a class="nav-link" href="#about">About Us</a>
						</li>

						<li class="nav-item" id="nav5">
							<a class="nav-link" href="#contact">Contact us</a>
						</li>
					</ul>
				</div>
			</nav>
		</div>
		<!------------------------------------------------------------------------->

		<div class="row">

			<!-------------------Home-------------------------------->
			<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12" id="home" style="padding-top: 80px">
				<div class="header">
					<div class="container">
						<p class=" text-center header_text "><b>The Coffee Day</b></p>
						<p class=" text-center text"><b>Enjoy our delecious food, drinks and services</b> </p>
						<div class="text-center">
							<a href="#reservation"><button class="menu_btn" type="button">Make Reservation</button></a>
						</div>
					</div>
				</div>
			</div>

			<!---------------------------------------------------------->

			<!------------------Menu------------------------------------->
			<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 " id="menu" style="padding-top: 100px">
				<div class="container-fluid menu_bg">

					<div class="row">

						<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12">
							<table class="table table-borderless">
								<tr style="border-bottom: 5px dotted lavender">

									<td class="menu-option_btn text-center" id="btn1" style="background-color: pink">
										<img class="logo-img" src="drinkIcon.png">
										Drink

									</td>
									<td class="menu-option_btn text-center" id="btn2">
										<img class="logo-img" src="snacks.png">
										Eat
									</td>
								</tr>
							</table>
						</div>
					</div>

					<!------------------Menu Items------------------------------->
					<div class="container">
						<div class="row" id="drink">
							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container" style="padding-left:0px;padding-top: 10px">
									<img src="coffee.png" class="img-fluid">
								</div>
								<span class="menu_text text-center"><b>Black Coffee</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container">
									<img src="coco.png" class="img-fluid" height="130px" width="130px"
										style="margin-left: 20px">
								</div>
								<span class="menu_text text-center"><b>Coco Cola</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container">
									<img src="tea.png" class="img-fluid" height="200px" width="200px"
										style="margin-top:40px">
								</div>
								<span class="menu_text text-center"><b>Green Tea</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 ">
								<div class="container">
									<table class="table table-borderless">
										<tr>
											<td class="text-center"><button class="seemore">See More</button></td>
										</tr>
									</table>
								</div>
							</div>

						</div>
					</div>
					<!---------------------------------------------------------->
					<div class="container">
						<div class="row" id="eat">
							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container" style="padding-left:10px;padding-top:40px">
									<img src="Pizza.png" class="img-fluid">
								</div>
								<span class="menu_text text-center"><b>Veg Pizza</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container">
									<img src="hotdog.png" class="img-fluid" height="130px" width="130px"
										style="margin-left: 20px;margin-top: 30px">
								</div>
								<span class="menu_text text-center"><b>Hotdog</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-4 col-lg-4 col-xl-4 menu_pnl">
								<div class="menu-1 container">
									<img src="Burger.png" class="img-fluid" height="200px" width="200px"
										style="margin-top:40px">
								</div>
								<span class="menu_text text-center"><b>Burger</b></span>
							</div>

							<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 ">
								<div class="container">
									<table class="table table-borderless">
										<tr>
											<td class="text-center"><button class="seemore">See More</button></td>
										</tr>
									</table>
								</div>
							</div>

						</div>
					</div>

				</div>
			</div>
			<!--------------------------------------------------------->
		</div>
	</div>
	<!-------------------------Reservation-------------------------->

	<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 form_bg" id="reservation"
		style="padding-bottom: 100px;padding-top: 100px">

		<div class="container" style="padding: 0px">


			<div class="container text-center">
				<span class="FormHeading">Reserve a table and ask for special services</span>
			</div>

			<div class="container" style="padding-left:10px;margin-left: 2px">

				<div class="row">

					<div class="col-xs-12 col-sm-12 col-md-8 col-lg-8 col-xl-9 mt-5" ng-app="myApp"
						ng-controller="myCtrl">
						<form action="auth/reservation" method="POST" name="myForm">

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="name">Name:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="text" id="name" name="name" ng-model="name" ng-required="true"
										ng-pattern="pat_name" ng-blur="check();">

									<!-- <div class="alert" ng-show="bool_name">
									s<pan>Name is required</span>
								</div> -->


									<!-- <div class="alert" ng-show="myForm.name.$error.pattern">
									<span>Name is incorrect</span>
								</div> -->


								</div>

							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="phonenumber">PhoneNumber:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="text" name="phonenumber" id="phonenumber" ng-model="phonenumber"
										ng-required="true" ng-pattern="pat_phone" ng-blur="check2();">

									<!-- <div class="alert" ng-show="bool_phone">
									<span>Phone Number is required</span>
								</div> -->


									<!-- <div class="alert" ng-show="myForm.phonenumber.$error.pattern">
									<span>Phone Number is incorrect</span>
								</div> -->

								</div>
							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="email">Email:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="email" name="email" id="email" ng-model="email" ng-required="true"
										ng-blur="check3();">

									<!-- <div class="alert" ng-show="bool_email">
									<span>Email is required</span>
								</div> -->


									<!-- <div class="alert" ng-show="myForm.email.$error.email">
									<span>Email is incorrect</span>
								</div> -->

								</div>
							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="date">Date:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="text" name="date" id="date" ng-model="date" ng-required="true"
										ng-pattern="pat_date" placeholder="mm/dd/yy" ng-blur="check4();">

									<!-- <div class="alert" ng-show="bool_date">
									<span>{{msg_date}}</span>
								</div> -->



								</div>

							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="time">Time:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="text" placeholder="HH:MMam/pm" name="time" id="time" ng-model="time"
										ng-required="true" ng-pattern="pat_time" ng-blur="check5();">

									<!-- <div class="alert" ng-show="bool_time">
									<span>{{msg_time}}</span>
								</div>

								<div class="alert" ng-show="myForm.time.$error.pattern">
									<span>Time is invalid</span>
								</div> -->


								</div>

							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="people">How many people?:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<input type="text" name="people" id="people" ng-model="people" ng-required="true"
										ng-pattern="pat_people" ng-blur="check6();">

									<!-- <div class="alert" ng-show="bool_people">
									<span>Number of people is required</span>
								</div>

								
								<div class="alert" ng-show="myForm.people.$error.pattern">
									<span>Number of people is incorrect</span>
								</div> -->

								</div>

							</div>

							<div class="form-group form-inline row">

								<div class="col-md-3 col-lg-3 col-xl-3">
									<label for="comment">Any special requirements?:</label>
								</div>

								<div class="col-md-9 col-lg-9 col-xl-9">
									<textarea type="textarea" name="comment" id="comment" ng-model="comment"
										ng-required="true"></textarea>
								</div>

							</div>

							<div class="text-center">
								<button class="submit_" type="button">Submit</button>
							</div>





						</form>

					</div>

				</div>

			</div>

		</div>


	</div>


	</div>



	<!--------------About------------------------------------------->
	<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 about" id="about"
		style="padding-top: 100px;padding-bottom: 30px">
		<div class="container">
			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 "
					style="padding: 30px;background-color: hotpink">
					<span class="AboutHeading">About us</span>
					<p class="AboutContent">
						The Coffee Day was founded in Ahmedabad
						by Mr. Smith. We serve fresh-made-to-order
						basket, delicious snacks and drinks that are made with fresh vegitables. We are providing
						special custom serving services on your special occasions.
					</p>
				</div>
			</div>

			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 about-box1">
					<div class="container about-box2">
						<p class="about-content" style="color: lavenderblush">
							<span style="color:black"><b>Opening hours:</b></span>
							Everyday from 6am to 5pm
						</p>

						<p class="about-content" style="color:lavenderblush ">
							<span style="color:black"><b>Address:</b></span>
							15 Ad street, Opp NR complex,
							Ahmedabad, Gujarat.
						</p>
					</div>
				</div>

			</div>
		</div>
	</div>
	<!--------------------------Contact us--------------------------->

	<div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 con-bg" id="contact"
		style="padding-top:100px;padding-bottom: 70px">

		<div class="container text-center">

			<span class="Con-Heading">Contact Us</span>
			<br><br>

			<p style="font-size:25px;font-family: Century Gothic">Let's get in touch.</p>
			<br>

			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 text-left">
					<div class="Con-box">

						<div class="container Con-Content">
							<img src="location.png" height="40px" width="30px">
							<span>15 Ad street, Opp NR complex,
								Ahmedabad, Gujarat.</span>
						</div>
						<br>

						<div class="container Con-Content">
							<img src="call.png" height="40px" width="40px">
							<span>+91 9983652882</span>
						</div>
						<br>

						<div class="container Con-Content">
							<img class="float-left" src="mail.png" height="35px" width="35px">
							<span class="text-break">theCoffeeDay@gmail.com</span>
						</div>

					</div>
				</div>




				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 col-xl-6 text-left">
					<div class="Con-box">

						<div class="container Con-Content">
							<span><b>Find Us on:</b></span>
						</div>
						<br>


						<div class="container Con-Content">
							<img src="facebook.png" height="40px" width="40px">
							<span>Facebook</span>
						</div>
						<br>

						<div class="container Con-Content">
							<img src="insta.png" height="40px" width="40px">
							<span>Instagram</span>
						</div>
						<br>


					</div>
				</div>
			</div>
		</div>

	</div>


	<!------------------------------------------------------------->

	</div>
</body>

</html>
