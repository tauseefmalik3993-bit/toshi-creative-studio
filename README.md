<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Toshi Creative Studio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#000;
color:#fff;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(0,0,0,.8);
backdrop-filter:blur(10px);
z-index:1000;
}

.logo{
font-size:28px;
font-weight:bold;
color:#FFD700;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:20px;
font-size:16px;
}

nav a:hover{
color:#FFD700;
}

.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.8)),
url("hero.jpg") center/cover;
}

.hero h1{
font-size:55px;
color:#FFD700;
margin-bottom:20px;
}

.hero p{
font-size:22px;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:15px 35px;
background:#FFD700;
color:#000;
text-decoration:none;
font-weight:bold;
border-radius:40px;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
}

section{
padding:80px 8%;
}

.title{
font-size:38px;
color:#FFD700;
text-align:center;
margin-bottom:40px;
}
</style>

</head>

<body>

<header>

<div class="logo">
TS Studio
</div>

<nav>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<div>

<h1>TOSHI CREATIVE STUDIO</h1>

<p>Capture • Create • Inspire</p>

<a href="#contact" class="btn">
Hire Me
</a>

</div>

</section>
