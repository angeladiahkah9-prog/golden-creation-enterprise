<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Golden Creation Enterprise</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#FFD400;
color:#222;
}

header{
background:#F58220;
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
}

.logo{
font-size:28px;
font-weight:bold;
color:#fff;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:20px;
font-weight:bold;
}

.hero{
background:linear-gradient(rgba(255,212,0,.9),rgba(245,130,32,.9));
display:flex;
flex-wrap:wrap;
align-items:center;
justify-content:space-between;
padding:60px 8%;
}

.hero-text{
flex:1;
min-width:300px;
}

.hero-text h1{
font-size:55px;
color:#fff;
}

.hero-text p{
margin:20px 0;
color:#fff;
line-height:1.8;
}

.btn{
display:inline-block;
padding:15px 30px;
background:#fff;
color:#F58220;
text-decoration:none;
border-radius:30px;
font-weight:bold;
margin:10px;
}

.btn:hover{
background:#222;
color:#FFD400;
}

.hero img{
width:100%;
max-width:450px;
border-radius:20px;
border:6px solid #fff;
}

section{
padding:70px 8%;
background:#fff;
}

.title{
text-align:center;
font-size:36px;
color:#F58220;
margin-bottom:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:#FFF8E5;
padding:20px;
border-radius:15px;
text-align:center;
border-top:5px solid #F58220;
box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.order{
background:#FFD400;
}

form{
max-width:700px;
margin:auto;
background:#fff;
padding:25px;
border-radius:15px;
}

input,select,textarea{
width:100%;
padding:14px;
margin:10px 0;
border:2px solid #F58220;
border-radius:10px;
}

button{
width:100%;
padding:15px;
background:#F58220;
color:#fff;
border:none;
border-radius:10px;
font-size:18px;
cursor:pointer;
}

button:hover{
background:#222;
}

footer{
background:#F58220;
color:#fff;
text-align:center;
padding:25px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:#fff;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

@media(max-width:768px){

header{
flex-direction:column;
}

nav{
margin-top:10px;
}

.hero{
flex-direction:column;
text-align:center;
}

.hero-text h1{
font-size:38px;
}

}

</style>

</head>

<body>

<header>

<div class="logo">
Golden Creation Enterprise
</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#order">Order</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Golden Creation Enterprise</h1>

<p>
Orange Money • MTN Mobile Money • SIM Registration • Money Exchange • Phone Accessories
</p>

<a href="#services" class="btn">Our Services</a>

<a href="#order" class="btn">Order Now</a>

</div>

<div>

<img src="images/shop.jpg" alt="Shop">

</div>

</section>

<section id="about">

<h2 class="title">About Us</h2>

<p style="text-align:center;font-size:18px;">
Located at 1st Street, Opposite Stella Maris Polytechnic, Monrovia, Liberia.
We provide trusted Mobile Money, SIM Registration, Money Exchange and quality Phone Accessories.
</p>

</section>

<section id="services">

<h2 class="title">Our Services</h2>

<div class="grid">

<div class="card">Orange Money</div>

<div class="card">MTN Mobile Money</div>

<div class="card">SIM Registration</div>

<div class="card">SIM Retrieval</div>

<div class="card">Money Exchange</div>

<div class="card">Phone Charging</div>

<div class="card">Power Banks</div>

<div class="card">AirPods</div>

<div class="card">Earphones</div>

<div class="card">Phone Chargers</div>

<div class="card">Scratch Cards</div>

<div class="card">Phone Accessories</div>

</div>

</section>

<section class="order" id="order">

<h2 class="title">Place Your Order</h2>

<form>

<input type="text" placeholder="Full Name">

<input type="tel" placeholder="Phone Number">

<input type="text" placeholder="Delivery Address">

<select>

<option>Select Product or Service</option>

<option>Orange Money</option>

<option>MTN Mobile Money</option>

<option>Money Exchange</option>

<option>SIM Registration</option>

<option>Power Bank</option>

<option>AirPods</option>

<option>Earphones</option>

<option>Phone Accessories</option>

</select>

<input type="number" placeholder="Quantity">

<textarea placeholder="Additional Information"></textarea>

<button type="submit">

Place Order

</button>

</form>

</section>

<section id="contact">

<h2 class="title">Contact Us</h2>

<p style="text-align:center;font-size:18px;">

📍 1st Street, Opposite Stella Maris Polytechnic, Monrovia, Liberia

<br><br>

📞 0889574257

<br>

📞 0772065382

</p>

</section>

<footer>

<h2>Golden Creation Enterprise</h2>

<p>© 2026 All Rights Reserved</p>

</footer>

<a class="whatsapp" href="https://wa.me/231889574257?text=Hello%20Golden%20Creation%20Enterprise,%20I%20would%20like%20to%20place%20an%20order.">

WhatsApp

</a>

</body>
</html>