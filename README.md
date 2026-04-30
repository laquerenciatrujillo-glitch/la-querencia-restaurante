<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>La Querencia | Restaurante Campestre & Experiencia Ecuestre</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
:root {
    --negro-mate: #121212;
    --negro-card: #1e1e1e;
    --dorado: #C5A059;
    --dorado-brillante: #e3c17e;
    --blanco-hueso: #f5f5f5;
    --gris-texto: #b0b0b0;
}

* { margin: 0; padding: 0; box-sizing: border-box; }

body {
    background-color: var(--negro-mate);
    color: var(--blanco-hueso);
    font-family: 'Poppins', sans-serif;
}

h1, h2, h3 { font-family: 'Playfair Display', serif; color: var(--dorado); }

header {
    position: fixed;
    width: 100%;
    padding: 20px 50px;
    display: flex;
    justify-content: space-between;
    background: rgba(18,18,18,0.9);
    backdrop-filter: blur(10px);
    z-index: 1000;
}

.logo { font-size: 1.8rem; font-weight: bold; }

.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?auto=format&fit=crop&q=80') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
}

.hero h1 { font-size: 4rem; }

.btn-reserva {
    margin-top:20px;
    padding:15px 40px;
    background: var(--dorado);
    color:black;
    border-radius:50px;
    text-decoration:none;
}

section { padding:80px 10%; }

.section-title {
    text-align:center;
    font-size:2.5rem;
    margin-bottom:40px;
}

.card {
    background: var(--negro-card);
    padding:25px;
    border-radius:15px;
    margin-bottom:20px;
}

.menu-item {
    display:flex;
    justify-content:space-between;
    border-bottom:1px solid rgba(255,255,255,0.05);
    padding:10px 0;
}

.price { color: var(--dorado); }

</style>
</head>

<body>

<header>
<div class="logo">LA QUERENCIA</div>
</header>

<section class="hero">
<h1>Tradición y Elegancia</h1>
<p>Caballos de paso, gastronomía criolla y experiencias únicas frente al mar de Moche.</p>
<a href="https://wa.me/51913047602" class="btn-reserva">RESERVAR AHORA</a>
</section>

<!-- QUE SOMOS -->
<section>
<h2 class="section-title">Quiénes Somos</h2>
<div class="card">
<p>
Somos un fundo restaurante en Moche que combina gastronomía, caballos peruanos de paso y experiencias únicas:
cabalgatas, shows de marinera, clases de monta y eventos.
</p>
<br>
<p>Contamos con áreas verdes, juegos, hamacas, estacionamiento y amplios salones.</p>
</div>
</section>

<!-- CARTA REAL -->
<section>
<h2 class="section-title">Carta</h2>

<div class="card">
<h3>Entradas</h3>
<div class="menu-item"><span>Papa a la huancaína</span><span class="price">S/. 15</span></div>
<div class="menu-item"><span>Yuquitas a la huancaína</span><span class="price">S/. 16</span></div>
<div class="menu-item"><span>Causa de pollo / atún</span><span class="price">S/. 20</span></div>
<div class="menu-item"><span>Causa de langostinos</span><span class="price">S/. 28</span></div>
</div>

<div class="card">
<h3>Pescados y Mariscos</h3>
<div class="menu-item"><span>Ceviche pescado</span><span>S/. 38</span></div>
<div class="menu-item"><span>Ceviche mixto</span><span>S/. 42</span></div>
<div class="menu-item"><span>Arroz con mariscos</span><span>S/. 42</span></div>
<div class="menu-item"><span>Chaufa de langostinos</span><span>S/. 48</span></div>
</div>

<div class="card">
<h3>Carnes al cilindro</h3>
<div class="menu-item"><span>Pollo al cilindro</span><span>S/. 29</span></div>
<div class="menu-item"><span>Panceta criolla</span><span>S/. 35</span></div>
<div class="menu-item"><span>Panceta oriental</span><span>S/. 38</span></div>
</div>

<div class="card">
<h3>Criollos</h3>
<div class="menu-item"><span>Cabrito a la norteña</span><span>S/. 42</span></div>
<div class="menu-item"><span>Lomo saltado</span><span>S/. 50</span></div>
<div class="menu-item"><span>Tallarín saltado</span><span>S/. 50</span></div>
</div>

<div class="card">
<h3>Bebidas</h3>
<div class="menu-item"><span>Gaseosa</span><span>S/. 6</span></div>
<div class="menu-item"><span>Cerveza</span><span>S/. 12 - 14</span></div>
<div class="menu-item"><span>Chicha / Maracuyá</span><span>S/. 18 - 20</span></div>
</div>

</section>

<!-- EXPERIENCIAS -->
<section>
<h2 class="section-title">Experiencias</h2>

<div class="card">
<h3>🐎 Cabalgata en la Playa</h3>
<p>Incluye clase + paseo + fotos y videos.</p>
<p>Duración: 70 min</p>
<p>Precio: S/. 80 (1 persona) | S/. 70 (2+)</p>
</div>

<div class="card">
<h3>🎭 Show de Caballos de Paso</h3>
<p>Todos los fines de semana a las 2:30 pm con marinera en vivo.</p>
</div>

<div class="card">
<h3>📸 Sesión de Fotos</h3>
<p>1 caballo: S/. 200 | 2 caballos: S/. 350</p>
</div>

<div class="card">
<h3>🎓 Clases de Monta</h3>
<p>Desde S/. 250 mensuales</p>
</div>

<div class="card">
<h3>🎉 Eventos y Picnics</h3>
<p>Cumpleaños, cenas románticas y eventos corporativos.</p>
</div>

</section>

<!-- CONTACTO -->
<section>
<h2 class="section-title">Contacto</h2>
<div class="card">
<p>📍 Moche - Playa El Acuario</p>
<p>📞 913 047 602</p>
<p>📲 Instagram / TikTok: @laquerenciafundo</p>
</div>
</section>

<a href="https://wa.me/51913047602" class="btn-reserva" style="position:fixed;bottom:20px;right:20px;">
WhatsApp
</a>

</body>
</html>
