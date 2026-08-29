<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>StormWatch | Alertas meteorológicas</title>

<link rel="manifest" href="manifest.json">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{

background:#081523;
color:white;

}

header{

padding:50px 20px;
text-align:center;

}

header img{

width:170px;
border-radius:35px;
box-shadow:0 20px 50px rgba(0,0,0,.45);

}

h1{

font-size:55px;
margin-top:20px;

}

.sub{

font-size:20px;
color:#9db7ca;
margin-top:10px;

}

.download{

display:inline-block;
margin-top:30px;
padding:15px 40px;
background:#ff3d4d;
color:white;
text-decoration:none;
border-radius:40px;
font-size:18px;
transition:.3s;

}

.download:hover{

transform:scale(1.08);

}

section{

max-width:1200px;
margin:auto;
padding:50px 20px;

}

.title{

text-align:center;
font-size:35px;
margin-bottom:50px;

}

.gallery{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:35px;

}

.card{

background:#102235;
padding:20px;
border-radius:30px;
text-align:center;
transition:.4s;

}

.card:hover{

transform:translateY(-10px);

}

.card img{

width:100%;
border-radius:25px;

}

.card h3{

margin-top:20px;

}

.card p{

margin-top:10px;
color:#c4d3df;

}

.features{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:25px;

}

.feature{

background:#102235;
padding:30px;
border-radius:25px;
text-align:center;

}

.feature h2{

margin-bottom:15px;

}

footer{

padding:40px;
text-align:center;
color:#7d96aa;

}

</style>

</head>

<body>

<header>

<img src="icon-512.png">

<h1>StormWatch</h1>

<p class="sub">

Alertas meteorológicas en tiempo real

</p>

<a class="download" href="#">

Instalar aplicación

</a>

</header>

<section>

<h2 class="title">

Galería

</h2>

<div class="gallery">

<div class="card">

<img src="captura1.jpg">

<h3>Icono principal</h3>

<p>Diseño moderno con estilo profesional.</p>

</div>

<div class="card">

<img src="captura2.jpg">

<h3>Vista alternativa</h3>

<p>Presentación elegante de StormWatch.</p>

</div>

<div class="card">

<img src="captura3.jpg">

<h3>Diseño Premium</h3>

<p>Preparado para Google Play y PWA.</p>

</div>

</div>

</section>

<section>

<h2 class="title">

Características

</h2>

<div class="features">

<div class="feature">

<h2>⚡</h2>

<h3>Alertas instantáneas</h3>

<p>Recibe avisos al momento.</p>

</div>

<div class="feature">

<h2>🌩</h2>

<h3>Radar meteorológico</h3>

<p>Tormentas en tiempo real.</p>

</div>

<div class="feature">

<h2>📍</h2>

<h3>Alertas locales</h3>

<p>Información según tu ubicación.</p>

</div>

<div class="feature">

<h2>🌍</h2>

<h3>Multilenguaje</h3>

<p>Español · English · العربية · 中文</p>

</div>

</div>

</section>

<footer>

StormWatch © 2026

</footer>

</body>

</html>
