<!DOCTYPE HTML>
<html >
<head>
	<meta charset="UTF-8">
	<meta name= "viewport" content= "width=device-width, initial-scale=1">
	<title>MODULE 2 Assignment</title>
	<style>
	*{
		box-sizing:border-box;
		margin:0;
		padding:0;
	}
	/*************Tablet view*************/
			@media(min-width:768px) and (max-width:991px){
			.one,.two,.three{float:left;
					border:1px solid black;}	
			.one{width:40%;}
			.two{width:40%;}
			.three{width:92%;}
}
/******Desktop View*******/
		@media(min-width:992px){
		.one,.two,.three{float:left;
				border:1px solid black;}	
		
		.one,.two,.three{width:26%;}
		}
/******mobile View*******/
		@media(max-width:767px){
			.one,.two,.three{float:left;
			border:1px solid black;}	
.one,.two,.three{width:94%;}
			
}
body{font-family:arial;
background-color:#FFE2B7;}
	section{
		color:#000000;
		background-color:#808080;
		border: 2px solid black;
		padding:5px;
		margin:30px;
		font-size:50%;
	}
	h2,h3,h4{
		text-align: right;
		font-size: 300%;
		border:1px solid black;}
	h1 {
		text-align:center;
		font-size:350%;
	}
	p{
		font-size:200%;
	}
	h2{background-color:#FA8072;}
	h3{background-color:#FF0000;}
	h4{background-color:#FFD700;}
	</style>
	

	</head>
<body>
		<h1>Our Menu</h1>
	
<section class="one"> 
	<h2>Chicken</h2>
	<p>In this chapter, you learned the basic concepts of classes, objects, methods and instance
variables—these will be used in most Java applications you create. In particular, you
learned how to declare instance variables of a class to maintain data for each object of the
class, and how to declare methods that operate on that data. You learned how to call a
method to tell it to perform its task and how to pass information to methods as arguments.

	</p>
</section>
<section class="two">
	<h3>Beef</h3>
	<p>You learned the difference between a local variable of a method and an instance variable
of a class and that only instance variables are initialized automatically. You also learned
how to use a class’s constructor to specify the initial values for an object’s instance variables.
Throughout the chapter, you saw how the UML can be used to create class diagrams
that model the constructors, methods and attributes of classes. 
	</p>
</section>
<section class="three">
	<h4>Sushi</h4>
	<p>Finally, you learned about
floating-point numbers—how to store them with variables of primitive type double, how
to input them with a Scanner object and how to format them with printf and format
specifier  for display purposes. In the next chapter we begin our introduction to control
statements, which specify the order in which a program’s actions are performed. You will
use these in your methods to specify how they should perform their tasks.
	</p>
</section>
</body>
</html>
