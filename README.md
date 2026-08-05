# golden-creation-enterprise
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
font-size:30px;
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
background:linear-gradient(rgba(255,212,0,.92),rgba(245,130,32,.90));
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
padding:80px 8%;
}

.hero-text{
flex:1;
min-width:300px;
}

.hero-text h1{
font-size:55px;
color:#fff;
margin-bottom:20px;
}

.hero-text p{
font-size:20px;
line-height:1.8;
color:#fff;
margin-bottom:30px;
}

.hero img{
width:100%;
max-width:450px;
border-radius:20px;
border:8px solid white;
}

.btn{
display:inline-block;
padding:15px 35px;
background:white;
color:#F58220;
text-decoration:none;
border-radius:40px;
font-weight:bold;
margin:10px;
}

.btn:hover{
background:#222;
color:#FFD400;
}

section{
padding:80px 8%;
background:white;
}

.title{
text-align:center;
font-size:40px;
color:#F58220;
margin-bottom:40px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:20px;
}

.card{
background:#FFF8E5;
padding:25px;
border-radius:15px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,.15);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.order{
background:#FFD400;
}

form{
max-width:700px;
margin:auto;
background:white;
padding:30px;
border-radius:20px;
}

input,select,textarea{
width:100%;
padding:15px;
margin:12px 0;
border:2px solid #F58220;
border-radius:10px;
}

button{
width:100%;
padding:15px;
background:#F58220;
color:white;
border:none;
border-radius:10px;
font-size:18px;
cursor:pointer;
}

button:hover{
background:black;
}

footer{
background:#F58220;
color:white;
padding:30px;
text-align:center;
}

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

@media(max-width:768px){

header{
flex-direction:column;
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
<a href="#products">Products</a>
<a href="#order">Order</a>
<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Golden Creation Enterprise</h1>

<p>

Orange Money<br>
MTN Mobile Money<br>
SIM Registration<br>
Money Exchange<br>
Phone Accessories

</p>

<a href="#services" class="btn">Explore Services</a>

<a href="#order" class="btn">Order Now</a>

</div>

<div>

<img src="images/shop.jpg" alt="Shop">

</div>

</section>

<section id="about">

<h2 class="title">About Us</h2>

<p style="text-align:center;font-size:18px;line-height:2;">

Golden Creation Enterprise is located at

1st Street,

Opposite Stella Maris Polytechnic,

Monrovia, Liberia.

We provide Orange Money,

MTN Mobile Money,

Money Exchange,

SIM Registration,

Phone Charging,

AirPods,

Power Banks,

Earphones,

Chargers,

and many other Phone Accessories.

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

<div class="card">Scratch Cards</div>

<div class="card">Chargers</div>

<div class="card">Phone Accessories</div>

</div>

</section>

<section id="products">

<h2 class="title">Featured Products</h2>

<div class="grid">

<div class="card">🔋 Power Banks</div>

<div class="card">🎧 AirPods</div>

<div class="card">🎵 Earphones</div>

<div class="card">🔌 Chargers</div>

<div class="card">📱 Phone Cases</div>

<div class="card">💾 Memory Cards</div>

</div>

</section>

<section class="order" id="order">

<h2 class="title">Place Your Order</h2>

<form>

<input type="text" placeholder="Full Name">

<input type="tel" placeholder="Phone Number">

<input type="text" placeholder="Address">

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

<textarea placeholder="Write your order"></textarea>

<button>

Place Order

</button>

</form>

</section>

<section id="contact">

<h2 class="title">

Contact Us

</h2>

<p style="text-align:center;font-size:20px;line-height:2;">

📍 1st Street Opposite Stella Maris Polytechnic

<br>

📞 0889574257

<br>

📞 0772065382

</p>

</section>

<footer>

<h2>

Golden Creation Enterprise

</h2>

<p>

© 2026 All Rights Reserved

</p>

</footer>

<a class="whatsapp"
href="https://wa.me/231889574257?text=Hello%20Golden%20Creation%20Enterprise,%20I%20would%20like%20to%20place%20an%20order.">

WhatsApp

</a>

</body>
</html>
