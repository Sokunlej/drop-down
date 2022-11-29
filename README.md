# drop-down html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
	<link rel="stylesheet" type="text/css" href="style.css">
	<title>Dropdown Menu</title>
</head>
<body>
	<div class="menu_bar">
		<h1 class="">BLOB <span> MATHS.</span></h1>

		<ul>
			<li> <a href="#"> HOME </li>
			<li> <a href="#"> CAREERS</li>
			<li> <a href="#"> COURSES <i class="fas fa-caret-down"></i>
				<div class="dropdown_menu">
					<ul>
						<li><a href="#"> MATHEMATICS</li>
						<li><a href="#"> ENGLISH</li>
						<li><a href="#"> SCIENCES</li>
						<li><a href="#"> ARTS </li>
					</ul>
				</div>
			</li>
			<li> <a href="#"> CONTACT</li>
			
		</ul>

</body>
</html>
  
  
 css
  .menu_bar{
	
	height: 80px;
	display: flex;
	align-items: center;
	background-color: blue;
	justify-content: space-between;
}
.menu_bar ul{
	list-style: none;
	display: flex;
}
.menu_bar ul li {
	padding: 10px 30px;
	position: relative;
}
.menu_bar ul li a: hover{
	color: var( --color- primary);
}
.dropdown_menu{
	display: block;
	position: absolute;
	left: 0;
	top: 100%;
	background-color: blue;
}
.dropdown_menu ul{
	display: block;
	margin: 10px;
}
.dropdown_menu ul li{
	width: 150px;
	padding: 10px;
}
