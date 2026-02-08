<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Laxmi Phool Bhandar Anjad | Fresh Flowers & Wedding Decoration</title>

<meta name="description" content="Anjad का trusted flower shop - fresh flowers, wedding decoration, bouquet delivery.">
<meta name="keywords" content="Flower Shop Anjad, Bouquet Delivery, Wedding Flowers">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body{margin:0;font-family:Poppins;background:#fafafa;color:#333}
header{
background:url('https://images.unsplash.com/photo-1490750967868-88aa4486c946') center/cover;
height:80vh;color:#fff;text-align:center;
display:flex;flex-direction:column;justify-content:center
}
header h1{font-size:42px;margin:10px}
header p{font-size:18px}

nav{background:#111;padding:14px;text-align:center;position:sticky;top:0}
nav a{color:#fff;margin:0 18px;text-decoration:none;font-weight:500}

section{padding:60px 20px;text-align:center}
.card{
background:#fff;
padding:25px;
margin:15px;
border-radius:14px;
box-shadow:0 6px 18px rgba(0,0,0,.08)
}

.gallery img{
width:280px;border-radius:12px;margin:12px;
transition:.4s
}
.gallery img:hover{transform:scale(1.05)}

footer{background:#111;color:#fff;padding:30px}

.whatsapp{
position:fixed;bottom:25px;right:25px;
background:#25D366;color:#fff;
padding:14px 18px;border-radius:50px;
text-decoration:none;font-weight:bold
}

button{
background:#4CAF50;color:#fff;
border:none;padding:14px 30px;
border-radius:8px;font-size:16px
}

input,textarea{
width:90%;padding:12px;margin:8px;
border-radius:8px;border:1px solid #ccc
}

iframe{width:100%;height:350px;border:0;border-radius:12px}
</style>
</head>

<body>

<header>
<h1>🌸 Laxmi Phool Bhandar</h1>
<p>Fresh Flowers • Wedding Decoration • Home Delivery</p>
<a href="https://wa.me/91XXXXXXXXXX" 
style="background:#25D366;padding:12px 25px;color:#fff;border-radius:8px;text-decoration:none">
Order on WhatsApp
</a>
</header>

<nav>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#order">Order</a>
<a href="#map">Location</a>
<a href="#contact">Contact</a>
</nav>

<section id="about">
<h2>हमारे बारे में</h2>
<p>
Anjad में trusted flower shop — fresh flowers, bouquet,
wedding decoration और event flower setup.
</p>
</section>

<section id="services">
<h2>Services</h2>
<div class="card">💐 Fresh Flower Bouquets</div>
<div class="card">🌸 Wedding Decoration</div>
<div class="card">🚗 Car Decoration</div>
<div class="card">🎉 Event Flower Setup</div>
<div class="card">🙏 Temple Flowers</div>
</section>

<section class="gallery" id="gallery">
<h2>Shop Gallery</h2>
<img src="shop1.jpg">
<img src="shop2.jpg">
<img src="shop3.jpg">
</section>

<section id="order">
<h2>Online Flower Order</h2>

<form onsubmit="sendOrder();return false;">
<input id="name" placeholder="Name" required>
<input id="phone" placeholder="Phone" required>
<textarea id="orderText" placeholder="Flower Order Details"></textarea>
<button>Send Order</button>
</form>
</section>

<section id="map">
<h2>Shop Location</h2>
<iframe src="https://maps.google.com/maps?q=Anjad%20Madhya%20Pradesh&output=embed"></iframe>
</section>

<section id="contact">
<h2>Contact</h2>
<p>📍 Anjad, Madhya Pradesh</p>
<p>📞 +91 XXXXX XXXXX</p>
<p>📧 laxmiphoolbhandar@gmail.com</p>
</section>

<footer>
<p>© 2026 Laxmi Phool Bhandar</p>
<p>Fresh Flowers | Wedding Decoration | Fast Delivery</p>
</footer>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX">WhatsApp</a>

<script>
function sendOrder(){
let name=document.getElementById('name').value;
let phone=document.getElementById('phone').value;
let order=document.getElementById('orderText').value;

let msg=`🌸 Flower Order
Name: ${name}
Phone: ${phone}
Order: ${order}`;

window.open(`https://wa.me/91XXXXXXXXXX?text=${encodeURIComponent(msg)}`);
}
</script>

</body>
</html>
