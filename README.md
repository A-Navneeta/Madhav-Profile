<!DOCTYPE html>
<html><head>
		<title>MY PROFILE</title>

		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<style>
		* {
			margin: 0;
			font-family: Tahoma;
		}
		img {
			max-width: 100%;
		}
		.wrap {
		}
		.img {
			border-radius: 50%;
			width: 100px;
		}
		.row1, .row2, .row6, .row7, .wrap1 {
			background-color: #a1a1a1;
		}
		.row3, .row4, .row5, .row8, .wrap2 {
			background-color: #ccc;
		}
.row1, .row7 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto;
			grid-gap: 20px;
		}
		.row4, .row5 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto auto;
			grid-gap: 20px;
			padding-bottom: 30px;
		}
		.bgwhite {
			background-color: #fff;
		}
		.bgblack {
			background-color: #000;
			color: #fff;
		}
		.alignright {
			text-align: right;
		}
		.aligncenter {
			text-align: center;
		}
		.row1, .pad20 {
			padding: 20px;
		}
		.row2 a {
			background-color: #000;
			color: #fff;
			padding: 10px 15px;
			text-decoration: none;
		}
@media only screen and (max-width:576px) {
			.row1, .row7, .row4, .row5 {
				grid-template-columns: auto;
			}
			.row1 div, .row7 div {
				text-align: center;
			}
			.row7 div ul {
				text-align: left;
			}
		}
		</style>
	</head>
<body>
		<div class="wrap1">
			<div class="row1">
				<div><img src="madhav12.jpg" class="img"></div>
				<div class="alignright pad20">
					<h4>Sai Madhav</h4>
					<p>class 4th<br>
					Gyan Ganga Educational Academy</p>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row2 aligncenter pad20">
				<a href="">Profile</a><a href="">About</a><a href="">Contact</a>
			</div>
		</div>
		<div class="wrap">
			<div class="row3 aligncenter pad20">
				<h2>MY PROFILE</h2>
			</div>
		</div>
<div class="wrap2">
			<div class="row4">
				<div>
					<img src="efec65ea-25b5-4a26-97f6-a9f2be7db1f8.jpg">
					<p> My Certificate</p>
						</div>
			    	<div>
					<img src="ae5afcb2-b26d-4097-84ec-58c9e675a2c5.jpg">
					<p>My Pic</p>
						</div>
				<div>
					<img src="27f4f8df-597b-4d20-bcd2-c1b6f0d6806d.jpg">
					<p>My Guitar</p>
					</div>
			</div>
		</div>
	<div class="wrap">
			<div class="row6 aligncenter pad20">
				<h2>About Me</h2>
			</div>
		</div>
<div class="wrap1">
   <div class="row7">
				<div class="bgwhite pad20">
					<h4 class="aligncenter">Personal Details</h4>
					<ul>
						<li>Name - A. Sai Madhav</li>
						<li>DOB - 20 March 2011</li>
						<li>PHONE - 9407624624</li>
						<li>HOBBY - Guitar, Art and Craft</li>
						<li>Email ID - adabalasaimadhav@gmail.com</li>
					</ul>
				</div>
				<div class="bgblack pad20">
					<h4 class="aligncenter">Education/Nationality</h4>
					<ul>
						<li>Class - 4th</li>
						<li>Section - A</li>
						<li>School - Gyan Ganga Educational Academy</li>
						<li>State - Chhattisgarh</li>
                                                <li>Capital - Raipur</li>
						<li>Country - India</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row8 aligncenter pad20">© Copyright 2020.</div>
		</div>
	
</body></html>
