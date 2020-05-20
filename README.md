<!DOCTYPE html>
<html>
<head>
	<title>Circles</title>
	<style type="text/css">
  .p1{
	text-align: center;
	font-size: 25px;
}
.hr1{
	height: 3px;
	background: black;
}
td>a{
	text-decoration: none;
	color: black;
	font-size: 20px;
}
.circles{
	text-decoration: underline;
}
.menu{
	margin-left: 1000px;
}
.menutable{
	border-spacing: 10px;
}
.hr1{
	height: 3px;
	background: black;
}
.block1{
	background: lightpink;
	height: 150px;
	width: 150px;
	border-radius: 50%;
	border: 2px solid black;
	transition: 1s background, 1s border;
	display: inline-block;
	padding: 5px;
}
.block1:hover{
	background: #cce6ff;
	border: 10px solid black;
}
.block2{
	background-image: linear-gradient(50deg,aqua, #ff0066);
	height: 150px;
	width: 150px;
	border: 2px solid black;
	border-radius: 50%;
	padding: 5px;
	display: inline-block;
	margin-left: 350px;
	transition: 1s border, 1s background, 1s height;
}
.block2:hover{
	border: 10px solid black;
	background: #ccb3ff;
	height: 250px;
}
.block3{
	background: #004d80;
	height: 150px;
	width: 150px;
	border-radius: 50%;
	border: 2px solid black;
	transition: 1s border, 1s background;
	display: inline-block;
	padding: 5px;
	margin-left: 350px;
}
.block3:hover{
	border: 10px solid black;
	background: #ff1aff;
}
.block4{
	background: #ffff80;
	height: 150px;
	width: 150px;
	border-radius: 50%;
	border: 2px solid black;
	transition: 1s border, 1s background;
	display: inline-block;
	padding: 5px;
	margin-left: 250px;
	transition: 1s height, 1s width;
}
.block4:hover{
	height: 250px;
	width: 250px;
}
.block5{
	background: #d5ff80;
	height: 150px;
	width: 150px;
	border-radius: 50%;
	border: 2px solid black;
	transition: 1s border, 1s background;
	display: inline-block;
	padding: 5px;
	margin-left: 350px;
	transition: 1s height, 1s width;
}
.block5:hover{
	height: 250px;
	width: 250px;
}
.block6{
	background: #FFE5CC;
	width: 150px;
	height: 150px;
	border: 2px solid black;
	border-radius: 50%;
	padding: 5px;
	margin-left: 520px;
	transition: 1s border, 1s height;
}
.block6:hover{
	border: 10px solid black;
	height: 250px;
}
.block7{
	height: 150px;
	width: 150px;
	padding: 5px;
	display: inline-block;
	border-radius: 50%;
	margin-left: 250px;
	border: 2px solid black;
	background: #990000;
	transition: 1s height, 1s width;
}
.block7:hover{
	height: 100px;
	width: 100px;
}
.block8{
	height: 150px;
	width: 150px;
	padding: 5px;
	display: inline-block;
	border-radius: 50%;
	border: 2px solid black;
	background: #C3FAFF;
	transition: 1s height, 1s width;
	margin-left: 350px;
}
.block8:hover{
	height: 100px;
	width: 100px;
}
.block9{
	height: 150px;
	width: 150px;
	padding: 5px;
	border-radius: 50%;
	border: 2px solid black;
	background: deeppink;
	transition: 1s border, 1s background;
}
.block9:hover{
	border: 10px solid black;
	background: deepskyblue;
}
.block10{
	display: inline-block;
	height: 150px;
	width: 150px;
	padding: 5px;
	border-radius: 50%;
	border: 2px solid black;
	background-image: linear-gradient(50deg,lightcoral,lightcyan);
	transition: 1s border, 1s height;
	margin-left: 520px;
	position: absolute;
	top: 742px;
}
.block10:hover{
	border: 10px solid black;
	height: 250px;
}
.block11{
	display: inline-block;
	height: 150px;
	width: 150px;
	padding: 5px;
	border-radius: 50%;
	border: 2px solid black;
	transition: 1s border, 1s background;
	background: mediumaquamarine;
	position: absolute;
	top: 742px;
	margin-left: 1060px;
}
.block11:hover{
	border: 10px solid black;
	background: mediumspringgreen;
}
  </style>
</head>
<body>
	<div class="menu">
		<table class="menutable">
			<tr>
				<td><a href="file:///C:/Users/User/Desktop/hovering/circles.html"class="circles">Circles</a></td>
				<td><a href="file:///C:/Users/User/Desktop/hovering/squares.html">Squares</a></td>
				<td><a href="file:///C:/Users/User/Desktop/hovering/lines.html">Lines</a></td>
			</tr>
		</table>
	</div>
	<hr class="hr1">
	<div class="block1"></div>
	<div class="block2"></div>
	<div class="block3"></div>
	<div class="block4"></div>
	<div class="block5"></div>
	<div class="block6"></div>
	<div class="block7"></div>
	<div class="block8"></div>
	<div class="block9"></div>
	<div class="block10"></div>
	<div class="block11"></div>
</body>
</html>
