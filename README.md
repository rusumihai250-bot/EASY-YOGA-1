
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Easy Yoga</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body {
    margin:0;
    font-family:Poppins;
    background:#f4f7f4;
    color:#333;
}

/* NAV */
nav {
    position:fixed;
    width:100%;
    background:#2e7d32;
    padding:15px;
    text-align:center;
    z-index:1000;
}
nav a {
    color:white;
    margin:15px;
    text-decoration:none;
    font-weight:500;
}

/* HEADER */
header {
    height:100vh;
    background:linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
    url('https://images.unsplash.com/photo-1506126613408-eca07ce68773') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

header h1 {
    font-size:60px;
}

header p {
    font-size:22px;
}

/* BUTTON */
.btn {
    padding:15px 30px;
    background:#2e7d32;
    color:white;
    border:none;
    border-radius:30px;
    cursor:pointer;
    transition:0.3s;
}
.btn:hover {
    background:#1b5e20;
    transform:scale(1.05);
}

/* SECTION */
section {
    padding:80px 20px;
    text-align:center;
}

/* CARDS */
.cards {
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}

.card {
    background:white;
    padding:25px;
    width:280px;
    border-radius:20px;
    box-shadow:0 10px 25px rgba(0,0,0,0.1);
    transition:0.3s;
}
.card:hover {
    transform:translateY(-10px);
}

/* GALLERY */
.gallery {
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}
.gallery img {
    width:32%;
    border-radius:15px;
}

/* TESTIMONIALS */
.testimonial {
    max-width:600px;
    margin:20px auto;
    background:white;
    padding:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

/* WHATSAPP FLOAT */
.whatsapp {
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    font-size:20px;
    text-decoration:none;
}

/* CONTACT */
.contact {
    background:#e8f5e9;
}

/* MOBILE */
@media(max-width:768px){
    header h1 {font-size:40px;}
    .gallery img {width:100%;}
}
</style>
</head>

<body>

<nav>
<a href="#">Acasă</a>
<a href="#about">Despre</a>
<a href="#services">Servicii</a>
<a href="#gallery">Galerie</a>
<a href="#reviews">Recenzii</a>
<a href="#contact">Contact</a>
</nav>

<header>
<div>
<h1>EASY YOGA</h1>
<p>Relaxare • Energie • Echilibru</p>
<button class="btn" onclick="window.location.href='https://wa.me/37369404887'">
Rezervă acum
</button>
</div>
</header>

<section id="about">
<h2>Despre noi</h2>
<p>Easy Yoga este spațiul tău pentru liniște, energie și echilibru interior.</p>
</section>

<section id="services">
<h2>Serviciile noastre</h2>
<div class="cards">
<div class="card">
<h3>Yoga</h3>
<p>Clase pentru toate nivelurile</p>
</div>
<div class="card">
<h3>Meditație</h3>
<p>Reducerea stresului</p>
</div>
<div class="card">
<h3>Stretching</h3>
<p>Flexibilitate și sănătate</p>
</div>
</div>
</section>

<section id="gallery">
<h2>Galerie</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1552196563-55cd4e45efb3">
<img src="https://images.unsplash.com/photo-1518611012118-fddc5c9c6a3b">
<img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773">
</div>
</section>

<section id="reviews">
<h2>Recenzii</h2>

<div class="testimonial">
<p>„Un loc incredibil! Mă simt mult mai relaxata.”</p>
<b>— Ana</b>
</div>

<div class="testimonial">
<p>„Atmosferă foarte plăcută și instructori buni.”</p>
<b>— Mihai</b>
</div>

</section>

<section class="contact" id="contact">
<h2>Contact</h2>
<p>📍 Chișinău</p>
<p>📞 +37369404887</p>
<p>Instagram: easy_yoga33</p>

<button class="btn" onclick="window.location.href='https://wa.me/37369404887'">
Scrie pe WhatsApp
</button>
</section>

<footer style="background:#2e7d32;color:white;padding:20px;text-align:center;">
© EASY YOGA
</footer>

<a class="whatsapp" href="https://wa.me/37369404887">💬</a>

</body>
</html>

 
