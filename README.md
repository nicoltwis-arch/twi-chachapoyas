# twi-chachapoyas
Guía Gastronómica de Chachapoyas - Proyecto escolar sobre platos, bebidas y tradiciones culinarias de Amazonas.
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TWI - Guía Gastronómica de Chachapoyas</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
scroll-behavior:smooth;
}

body{
background:#f8f5ef;
color:#333;
}

/* PORTADA */
.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url('https://upload.wikimedia.org/wikipedia/commons/5/55/Kuelap_Fortress.jpg');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero-content h1{
font-size:80px;
letter-spacing:8px;
margin-bottom:10px;
}

.hero-content p{
font-size:22px;
margin-bottom:20px;
}

.btn{
background:#d28b36;
padding:15px 30px;
border-radius:30px;
color:white;
text-decoration:none;
font-weight:bold;
}

section{
padding:80px 10%;
}

h2{
text-align:center;
font-size:40px;
margin-bottom:40px;
color:#5c3a21;
}

.intro{
text-align:center;
max-width:900px;
margin:auto;
font-size:18px;
line-height:1.8;
}

/* TARJETAS */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:20px;
overflow:hidden;
box-shadow:0 5px 20px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.card-content h3{
margin-bottom:10px;
color:#6d4425;
}

/* BLOQUE TURÍSTICO */
.turismo{
background:
linear-gradient(rgba(255,255,255,.9),rgba(255,255,255,.9)),
url('https://upload.wikimedia.org/wikipedia/commons/4/42/Gocta_Waterfall.jpg');
background-size:cover;
background-position:center;
}

/* FOOTER */
footer{
background:#3d2618;
color:white;
text-align:center;
padding:30px;
}
</style>
</head>

<body>

<header class="hero">
<div class="hero-content">
<h1>TWI</h1>
<p>Guía Gastronómica de Chachapoyas</p>
<a href="#platos" class="btn">Descubrir Sabores</a>
</div>
</header>

<section>
<h2>Bienvenidos a Chachapoyas</h2>
<p class="intro">
Chachapoyas, ubicada en la región Amazonas, destaca por su riqueza cultural,
sus impresionantes paisajes y una gastronomía que combina ingredientes andinos
y amazónicos. Esta guía te invita a descubrir sus sabores más representativos.
</p>
</section>

<section id="platos">
<h2>Platos Típicos</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836">
<div class="card-content">
<h3>Tacacho con Cecina</h3>
<p>Plátano verde asado y machacado acompañado de carne de cerdo ahumada.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1544025162-d76694265947">
<div class="card-content">
<h3>Purtumute</h3>
<p>Tradicional guiso preparado con frijoles y maíz.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1547592180-85f173990554">
<div class="card-content">
<h3>Juane</h3>
<p>Preparado tradicional envuelto en hojas de bijao.</p>
</div>
</div>

</div>
</section>

<section>
<h2>Bebidas Tradicionales</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085">
<div class="card-content">
<h3>Café Amazónico</h3>
<p>Uno de los productos más reconocidos de Amazonas.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1513558161293-cdaf765ed2fd">
<div class="card-content">
<h3>Masato</h3>
<p>Bebida tradicional elaborada a base de yuca.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1514362545857-3bc16c4c7d1b">
<div class="card-content">
<h3>Chuchuhuasi</h3>
<p>Bebida típica elaborada con cortezas amazónicas.</p>
</div>
</div>

</div>
</section>

<section>
<h2>Panes y Dulces</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1509440159596-0249088772ff">
<div class="card-content">
<h3>Pan Artesanal</h3>
<p>Preparado en hornos tradicionales de la región.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1517433670267-08bbd4be890f">
<div class="card-content">
<h3>Rosquitas</h3>
<p>Dulce tradicional muy consumido en celebraciones.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1551024506-0bccd828d307">
<div class="card-content">
<h3>Dulces Regionales</h3>
<p>Preparados con recetas heredadas por generaciones.</p>
</div>
</div>

</div>
</section>

<section class="turismo">
<h2>Lugares Emblemáticos</h2>

<div class="grid">

<div class="card">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/55/Kuelap_Fortress.jpg">
<div class="card-content">
<h3>Fortaleza de Kuélap</h3>
<p>Uno de los sitios arqueológicos más importantes del Perú.</p>
</div>
</div>

<div class="card">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/42/Gocta_Waterfall.jpg">
<div class="card-content">
<h3>Catarata de Gocta</h3>
<p>Una de las cataratas más altas del mundo.</p>
</div>
</div>

<div class="card">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/8c/Karajia.jpg">
<div class="card-content">
<h3>Sarcófagos de Karajía</h3>
<p>Monumentos funerarios de la cultura Chachapoyas.</p>
</div>
</div>

</div>
</section>

<footer>
<h3>TWI</h3>
<p>Sabores que cuentan historias</p>
<br>
<p>Guía Gastronómica de Chachapoyas - Amazonas, Perú</p>
</footer>

</body>
</html>
