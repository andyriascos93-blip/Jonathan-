<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jonathan Riascos | Psicología y Bienestar</title>
<meta name="description" content="Comprenderte hoy, transforma tu mañana. Atención virtual.">
<style>
body{margin:0;font-family:Arial,sans-serif;background:#0b0b0b;color:#f8f8f8}
header{padding:20px 8%;display:flex;justify-content:space-between;align-items:center;background:#111;position:sticky;top:0}
.logo{color:#d4af37;font-weight:bold;font-size:24px}
nav a{color:#fff;text-decoration:none;margin-left:20px}
.hero{display:flex;flex-wrap:wrap;align-items:center;padding:60px 8%}
.hero-text{flex:1;min-width:300px}
.hero-img{flex:1;min-width:300px;text-align:center}
.hero-img img{max-width:100%;border-radius:20px}
h1{font-size:56px;line-height:1.1}
.gold{color:#d4af37}
.btn{display:inline-block;background:#d4af37;color:#111;padding:14px 24px;border-radius:10px;text-decoration:none;font-weight:bold}
section{padding:60px 8%}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
.card{background:#151515;padding:20px;border-radius:12px}
form{display:grid;gap:12px;max-width:600px}
input,select{padding:12px;border-radius:8px;border:none}
button{padding:14px;background:#d4af37;border:none;border-radius:8px;font-weight:bold}
footer{padding:30px;text-align:center;background:#111}
</style>
</head>
<body>

<header>
<div class="logo">Jonathan Riascos</div>
<nav>
<a href="#sobre">Sobre mí</a>
<a href="#servicios">Servicios</a>
<a href="#blog">Blog</a>
<a href="#agenda">Agenda</a>
</nav>
</header>

<section class="hero">
<div class="hero-text">
<p class="gold">PSICOLOGÍA • BIENESTAR • CRECIMIENTO PERSONAL</p>
<h1>Comprenderte hoy,<br><span class="gold">transforma tu mañana.</span></h1>
<p>Acompañamiento psicológico virtual para fortalecer tu bienestar emocional.</p>
<a class="btn" href="https://wa.me/573208562662">Agendar consulta</a>
</div>
<div class="hero-img">
<img src="foto-principal.jpg" alt="Jonathan Riascos">
</div>
</section>

<section id="sobre">
<h2>Sobre mí</h2>
<p>Mi propósito es acercar la psicología a las personas mediante herramientas prácticas, lenguaje claro y estrategias basadas en evidencia.</p>
</section>

<section id="servicios">
<h2>Áreas de trabajo</h2>
<div class="cards">
<div class="card">Ansiedad y estrés</div>
<div class="card">Autoestima</div>
<div class="card">Relaciones de pareja</div>
<div class="card">Regulación emocional</div>
<div class="card">Crecimiento personal</div>
<div class="card">Proyecto de vida</div>
</div>
</section>

<section id="blog">
<h2>Artículos destacados</h2>
<div class="cards">
<div class="card">¿Cómo identificar la ansiedad?</div>
<div class="card">La diferencia entre autoestima y amor propio</div>
<div class="card">¿Es posible sanar después de una ruptura?</div>
</div>
</section>

<section id="agenda">
<h2>Agenda tu consulta</h2>
<form id="agendaForm">
<input type="text" id="nombre" placeholder="Nombre completo" required>
<input type="tel" id="telefono" placeholder="WhatsApp" required>
<input type="date" id="fecha" required>
<select id="hora">
<option>09:00 AM</option>
<option>10:00 AM</option>
<option>02:00 PM</option>
<option>04:00 PM</option>
</select>
<button type="submit">Agendar por WhatsApp</button>
</form>
</section>

<footer>
<p>Jonathan Riascos | Atención virtual</p>
<p>WhatsApp: 320 856 2662</p>
</footer>

<script>
document.getElementById('agendaForm').addEventListener('submit', function(e){
e.preventDefault();
let n=document.getElementById('nombre').value;
let t=document.getElementById('telefono').value;
let f=document.getElementById('fecha').value;
let h=document.getElementById('hora').value;
let msg=`Hola Jonathan, deseo agendar una consulta.%0A%0ANombre: ${n}%0AWhatsApp: ${t}%0AFecha: ${f}%0AHora: ${h}`;
window.open('https://wa.me/573208562662?text='+msg,'_blank');
});
</script>

</body>
</html>
