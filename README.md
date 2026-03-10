<!DOCTYPE html>
<html lang="am">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ንጋት የዜማ መሳሪያዎች</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{

background:url("background.jpg");
background-size:cover;
background-position:center;
background-attachment:fixed;
color:white;

}

/* dark overlay */

.overlay{
background:rgba(0,0,0,0.65);
min-height:100vh;
}

/* animated gradient */

header{

text-align:center;
padding:70px 20px;

background:linear-gradient(270deg,#ff512f,#dd2476,#24c6dc);
background-size:600% 600%;

animation:gradientMove 10s ease infinite;

}

@keyframes gradientMove{

0%{background-position:0% 50%}
50%{background-position:100% 50%}
100%{background-position:0% 50%}

}

header h1{
font-size:42px;
}

.order{

margin-top:20px;
display:inline-block;
padding:12px 30px;
background:#ffcc00;
color:black;
border-radius:30px;
font-weight:bold;

animation:pulse 2s infinite;

}

@keyframes pulse{

0%{transform:scale(1)}
50%{transform:scale(1.1)}
100%{transform:scale(1)}

}

/* product grid */

.products{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
padding:40px;

}

.card{

background:rgba(255,255,255,0.15);
backdrop-filter:blur(10px);

border-radius:20px;
padding:15px;
text-align:center;

animation:float 4s ease-in-out infinite;

transition:.3s;

}

/* floating animation */

@keyframes float{

0%{transform:translateY(0px)}
50%{transform:translateY(-10px)}
100%{transform:translateY(0px)}

}

.card:hover{

transform:scale(1.08) rotate(1deg);

}

.card img{

width:100%;
height:200px;
object-fit:cover;
border-radius:15px;

}

/* contact */

.contact{

text-align:center;
padding:50px;
background:rgba(0,0,0,0.6);

}

button{

margin-top:20px;
padding:12px 30px;

border:none;
border-radius:30px;

background:#ffcc00;
color:black;

font-size:16px;
cursor:pointer;

transition:.3s;

}

button:hover{

background:white;

}

footer{

text-align:center;
padding:20px;
opacity:.8;

}

</style>
</head>

<body>

<div class="overlay">

<header>

<h1>🌅 ንጋት የዜማ መሳሪያዎች</h1>

<p>Nigat Melody Instruments</p>

<div class="order">#Order_now</div>

</header>


<section class="products">

<div class="card">
<img src="begenna.jpg">
<h3>👉 በገና</h3>
</div>

<div class="card">
<img src="krar.jpg">
<h3>👉 ክራር</h3>
</div>

<div class="card">
<img src="basekrar.jpg">
<h3>👉 ቤዝ ክራር</h3>
</div>

<div class="card">
<img src="masenqo.jpg">
<h3>👉 መሰንቆ</h3>
</div>

<div class="card">
<img src="washint.jpg">
<h3>👉 ዋሽንት</h3>
</div>

<div class="card">
<img src="bag.jpg">
<h3>👉 ቦርሳ</h3>
</div>

</section>


<section class="contact">

<section class="contact">

<h2>📦 Order Now</h2>

<p>🚖 በፍጥነት ይዘዙን ባሉበት ቦታ ያለምንም ተጨማሪ ክፍያ እናደርሳለን</p>

<div class="order-buttons">

<a href="https://t.me/Nigatmelody" target="_blank">
<button class="telegram">📲 Order on Telegram</button>
</a>

<a href="tel:0920300011">
<button class="call">📞 Call Now</button>
</a>

<a href="https://wa.me/251920300011" target="_blank">
<button class="whatsapp">💬 Order on WhatsApp</button>
</a>

</div>

</section>
