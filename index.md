<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="utf-8">
  <title>418 I'm a teapot</title>
  <meta name="description" content="The HTML5 Herald">
  <meta name="author" content="SitePoint">
  <!-- Latest compiled and minified CSS -->
  <link rel="stylesheet" href="main.css">
  <!-- jQuery library -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <!-- Latest compiled JavaScript -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
<link rel="icon" type="image/png" sizes="16x16" href="kettle.png">  
</head>
<body>


	<header>
		<h1>Home</h1>
	</header>
	<nav>
		<p><a href="index.html">Home</a></p>
		<p><a href="inloggad.html">Inloggad</a></p>
    <p><a href="contact.html">Kontakt</a></p>
    
  </nav>
 

<div class="mainContainer animated flipInX" id="mainFrame">
	<div class="innerContainer">
    	<form>
        	<input id="submitField" type="text" class="inputBox" placeholder="Användarnamn" autofocus="autofocus" /> 
        	<input id="submitField" type="text" class="inputBox" placeholder="Lösenord" autofocus="autofocus" /> 
			<input type="reset" value="" id="deleteButton"/>
        </form>
        <span class="submitButton"> Logga in </span>
    </div>
</div>
