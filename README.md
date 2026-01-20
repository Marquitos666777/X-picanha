<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>X-Picanha | Pastelaria</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

body{
    background:#111;
    color:#fff;
}

header{
    background:#000;
    padding:20px 10%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:fixed;
    width:100%;
    top:0;
    z-index:10;
}

header h1{
    color:#ffae00;
}

header a{
    color:#fff;
    text-decoration:none;
    margin-left:25px;
    font-weight:500;
}

.hero{
    height:100vh;
    background:url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092') center/cover;
    display:flex;
    align-items:center;
    padding:0 10%;
}

.hero-text{
    background:rgba(0,0,0,0.75);
    padding:40px;
    border-radius:8px;
    max-width:500px;
}

.hero h2{
    font-size:40px;
    color:#ffae00;
}

.hero p{
    margin:15px 0 25px;
    line-height:1.6;
}

.btn{
    background:#ffae00;
    color:#000;
    padding:14px 22px;
    border-radius:5px;
    text-decoration:none;
    font-weight:bold;
}

section{
    padding:90px 10%;
}

.title{
    font-size:30px;
    margin-bottom:40px;
    color:#ffae00;
}

.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1b1b1b;
    border-radius:8px;
    overflow:hidden;
    transition:0.3s;
}

.card:hover{
    transform:scale(1.03);
}

.card img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.card h3{
    color:#ffae00;
}

.about{
    background:#000;
    line-height:1.8;
}

.hours{
    background:#1b1b1b;
}

.location iframe{
    width:100%;
    border-radius:8px;
}

footer{
    background:#000;
    text-align:center;
    padding:25px;
    font-size:14px;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25d366;
    color:#fff;
    padding:15px 18px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}

</style>
</head>

<body>

<header>
<h1>X-Picanha</h1>
<nav>
<a href="#menu">Cardápio</a>
<a href="#about">Sobre</a>
<a href="#hours">Horário</a>
<a href="#location">Localização</a>
</nav>
</header>

<div class="hero">
<div class="hero-text">
<h2>O melhor lanche da Vila Verde</h2>
<p>Picanha suculenta, pastéis crocantes e sabores inesquecíveis. Qualidade, rapidez e muito sabor em cada pedido!</p>
<a class="btn" href="https://wa.me/55SEUNUMERO">Pedir no WhatsApp</a>
</div>
</div>

<section id="menu">
<h2 class="title">Nosso Cardápio</h2>
<div class="menu">

<div class="card">
<img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
<div class="card-content">
<h3>X-Picanha Especial</h3>
<p>Pão brioche, picanha grelhada, queijo, salada e molho especial.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1604908176997-431cd0f0c30f">
<div class="card-content">
<h3>Pastel de Carne</h3>
<p>Massa crocante recheada com carne temperada e suculenta.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1625944525533-473f1d0e27d1">
<div class="card-content">
<h3>Pastel de Queijo</h3>
<p>Queijo derretido com massa sequinha e crocante.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1594212699903-ec8a3eca50f5">
<div class="card-content">
<h3>X-Salada</h3>
<p>Hambúrguer artesanal, queijo, alface, tomate e maionese da casa.</p>
</div>
</div>

</div>
</section>

<section id="about" class="about">
<h2 class="title">Sobre Nós</h2>
<p>A X-Picanha / Pastelaria nasceu para trazer sabor de verdade para Vila Verde, Curitiba. Trabalhamos com ingredientes selecionados, carnes frescas e atendimento rápido para garantir sempre a melhor experiência aos nossos clientes.</p>
</section>

<section id="hours" class="hours">
<h2 class="title">Horário de Atendimento</h2>
<p>Segunda a Domingo — 18:00 às 23:30</p>
</section>

<section id="location" class="location">
<h2 class="title">Onde Estamos</h2>
<iframe src="https://www.google.com/maps/embed?pb=!1m18" height="300"></iframe>
</section>

<footer>
© 2026 X-Picanha / Pastelaria — Vila Verde Curitiba
</footer>

<a class="whatsapp" href="https://wa.me/55SEUNUMERO">WhatsApp</a>

</body>
</html>
