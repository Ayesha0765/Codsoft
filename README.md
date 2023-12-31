<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodSoft Project</title>
    <link rel="stylesheet" href="style.css">
	
	<!--making a simple landing page.-->
	<style>
	<!--Main Frame-->
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
header{
<!--Using transparency rgba-->
    width: 100%;
    height: 100vh;
       background:linear-gradient(to bottom, rgba(0,0,0,0.9),rgba(0,0,0,0.1));
    font-family: 'Poppins',sans-serif;
}
nav{
color: #fff;
    width: 100%;
    height: 150px;
  
    
    display: flex;
    justify-content: space-around;
align-items: center;
}
.logo{
    font-size: 2em;
    letter-spacing: 2px;
}
.menu a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
}

.menu a:hover{
   border: 1px solid white;
   background: transparent;
}
.Sign-In a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
    border-radius: 8px;
    background: red;
}
.Sign-In a:hover{
    border: 1px solid red;
    background: transparent;
}
.h-text{
    position: absolute;
    top: 50%;
    left: 50%;
    max-width: 650px;
    transform: translate(-50%,-50%);
    text-align: center;
    color: #fff;
}
.h-text span{
    letter-spacing: 5px;
}
.h-text h1{
    font-size: 3.5em;
}
.h-text a{
    text-decoration: none;
    background: red;
    padding: 10px 20px;
    color: #fff;
    letter-spacing: 5px;
    transition: 0.3s;
}
.h-text a:hover{
    border: 1px solid red;
    background: transparent;
}




*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.About-us {
  margin: 70px;
    font-family: 'Poppins',sans-serif;
}

.Read-more {
  background-color: blue;
  border: none;
  color: #fff;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition: 0.3s;
}

.Read-more:hover {
  background: purple;
}


.footer {
 position: absolute;
    left: 50%;
    max-width: 650px;
    transform: translate(-50%,-50%);
    text-align: center;
    font-family: 'Poppins',sans-serif;
}


	</style>
	
</head>
<body>
    <header>
<!--The theme of the page is on cooking-->
<nav>
<div class="logo">
Miso
</div>
<div class="menu">
<!--The things on menu-->
    <a href="#">Home</a>
    <a href="#">About us</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>

</div>
<div class="Sign-In">
    <a href="#">Sign In</a>
</div>
</nav>
<section  class="h-text">
    <span>Welcome</span>
    <h1>World of the spices</h1>
    <br>
    <a href="#">Apply Now</a>
	

    </header>
	
	
	
	
	<main>
		<section class="About-us">
<h1>About Us</h1>
<br>
<p>Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.
Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.
Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.
Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.
Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.
Spices In the culinary arts, a spice is any seed, fruit, root, bark, or other plant substance in a form primarily used for flavoring or coloring food. Spices are distinguished from herbs, which are the leaves, flowers, or stems of plants used for flavoring or as a garnish.</p>

<a href="" class="Read-more">Read more</a>
</section>
	</main>
<footer class="footer">
        <p>&copy; 2023 Our Website. All rights reserved.</p>
    </footer>	
</body>

</html>
