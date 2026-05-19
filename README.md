# pixelMind
Página principal de PixelMind 
Co digo: 
<!DOCTYPE html> 
<html lang="es"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<title>PIXELMIND</title> 
<style> 
*{ 
margin:0; 
padding:0; 
box-sizing:border-box; 
font-family: Arial, sans-serif; 
} 
body{ 
background:#0d0d0d; 
color:white; 
} 
/* HEADER */ 
header{ 
background: linear-gradient(90deg,#4b0082,#7b2cbf); 
padding:15px; 
text-align:center; 
font-size:24px; 
font-weight:bold; 
} 
/* NAV */ 
nav{ 
background:#111; 
display:flex; 
justify-content:center; 
gap:20px; 
padding:10px; 
} 
nav a{ 
color:white; 
text-decoration:none; 
} 
nav a:hover{ 
color:#7b2cbf; 
} 
/* SECCIONES */ 
section{ 
padding:50px; 
text-align:center; 
} 
/* HERO */ 
.hero{ 
display:flex; 
flex-wrap:wrap; 
justify-content:center; 
align-items:center; 
gap:30px; 
} 
.hero-text{ 
max-width:500px; 
} 
.hero span{ 
color:#7b2cbf; 
} 
.hero img{ 
width:300px; 
border-radius:10px; 
} 
button{ 
margin-top:10px; 
padding:10px 20px; 
border:none; 
border-radius:5px; 
cursor:pointer; 
} 
.btn1{ 
background:#7b2cbf; 
color:white; 
} 
.btn2{ 
background:transparent; 
border:1px solid #7b2cbf; 
color:white; 
} 
/* SERVICIOS */ 
.services{ 
background:#f4f4f4; 
color:black; 
} 
.cards{ 
display:flex; 
flex-wrap:wrap; 
justify-content:center; 
gap:20px; 
margin-top:20px; 
} 
.card{ 
background:white; 
padding:20px; 
border-radius:10px; 
width:250px; 
} 
.card img{ 
width:100%; 
border-radius:10px; 
} 
/* ACERCA */ 
.about{ 
background:#1a1a1a; 
} 
/* CONTACTO */ 
.contact{ 
background:#f4f4f4; 
color:black; 
} 
form{ 
max-width:400px; 
margin:auto; 
display:flex; 
flex-direction:column; 
gap:10px; 
} 
input, textarea{ 
padding:10px; 
border-radius:5px; 
border:1px solid #ccc; 
} 
/* FOOTER */ 
footer{ 
background:linear-gradient(90deg,#000,#4b0082); 
text-align:center; 
padding:15px; 
} 
:root { 
--primary: #7b2cbf; 
--dark-bg: #0d0d0d; 
--card-bg: #1a1a1a; 
} 
/* Navbar Pegajosa (Sticky) */ 
nav { 
position: sticky; 
top: 0; 
z-index: 1000; 
backdrop-filter: blur(10px); /* Efecto borroso moderno */ 
background: rgba(17, 17, 17, 0.9); 
border-bottom: 1px solid #333; 
} 
/* Mejora de Tarjetas */ 
.card { 
background: var(--card-bg); 
color: white; 
border: 1px solid #333; 
transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
} 
.card:hover { 
transform: translateY(-15px); 
border-color: var(--primary); 
box-shadow: 0 10px 30px rgba(123, 44, 191, 0.3); 
} 
/* TABLA MODERNA (An ade este estilo) */ 
.table-container { 
padding: 50px; 
background: white; 
color: black; 
} 
table { 
width: 100%; 
max-width: 800px; 
margin: 20px auto; 
border-collapse: collapse; 
border-radius: 10px; 
overflow: hidden; /* Para que los bordes redondeados funcionen */ 
box-shadow: 0 5px 15px rgba(0,0,0,0.1); 
} 
th { 
background: var(--primary); 
color: white; 
padding: 15px; 
} 
td { 
padding: 12px; 
border-bottom: 1px solid #eee; 
text-align: center; 
} 
tr:hover { 
background-color: #f9f9f9; 
} 
/* SECCIO N MISIO N, VISIO N Y VALORES */ 
.mvv-container { 
display: flex; 
flex-wrap: wrap; 
justify-content: center; 
gap: 20px; 
padding: 20px 50px 50px 50px; 
background: #1a1a1a; /* Mantiene la este tica de la seccio n About */ 
} 
.mvv-item { 
flex: 1; 
min-width: 250px; 
max-width: 350px; 
padding: 25px; 
border-left: 4px solid #7b2cbf; 
background: rgba(255, 255, 255, 0.03); 
border-radius: 0 10px 10px 0; 
} 
.mvv-item h3 { 
color: #7b2cbf; 
margin-bottom: 10px; 
text-transform: uppercase; 
font-size: 18px; 
} 
/* SECCIO N TESTIMONIOS */ 
.testimonials { 
background: #0d0d0d; 
padding: 60px 20px; 
color: white; 
} 
.testimonial-grid { 
display: flex; 
flex-wrap: wrap; 
justify-content: center; 
gap: 25px; 
margin-top: 30px; 
} 
.testimonial-card { 
background: #1a1a1a; 
padding: 30px; 
border-radius: 15px; 
width: 300px; 
box-shadow: 0 10px 20px rgba(0,0,0,0.2); 
border-bottom: 3px solid #7b2cbf; 
} 
.stars { 
color: #ffcc00; /* Color dorado para las estrellas */ 
margin-bottom: 10px; 
font-size: 18px; 
} 
.testimonial-card p { 
font-style: italic; 
font-size: 14px; 
color: #ccc; 
} 
.testimonial-card h4 { 
margin-top: 15px; 
color: white; 
font-size: 16px; 
} 
</style> 
</style> 
</head> 
<body> 
<header>PIXELMIND</header> 
<nav> 
<a href="#inicio">Inicio</a> 
<a href="#acerca">Acerca de</a> 
<a href="#servicios">Servicios</a> 
<a href="#contacto">Contacto</a> 
</nav> 
<!-- INICIO --> 
<section class="hero" id="inicio"> 
<div class="hero-text"> 
<h1>Disen amos ideas, creamos <span>impacto</span></h1> 
<p>Soluciones en disen o gra fico, desarrollo web y marketing digital.</p> 
<button class="btn1">Ver servicios</button> 
<button class="btn2">Portafolio</button> 
</div>




 
<img src="https://picsum.photos/400/300"> 
</section> 
<!-- ACERCA --> 
<section class="about" id="acerca"> 
<h2>Acerca de nosotros</h2> 
<p style="max-width:600px;margin:auto;margin-top:15px;"> 
PIXELMIND es una agencia creativa enfocada en brindar soluciones digitales innovadoras. 
Nos especializamos en disen o gra fico, desarrollo web y marketing digital para ayudar a 
nuestros clientes a crecer en el mundo digital. 
</p> 
</section> 
<div class="mvv-container"> 
<div class="mvv-item"> 
<h3>Misio n</h3> 
<p>Brindar soluciones tecnolo gicas creativas, innovadoras y accesibles que ayuden a clientes y otras empresas a comunicar sus ideas de manera efectiva, mejorar su productividad y 
<br>adaptarse al mundo digital, destacando su identidad y generando valor a trave s del disen o y la tecnologí a. </p> 
</div> 
<div class="mvv-item"> 
<h3>Visio n</h3> 
<p>Ser una empresa lí der en tecnologí a reconocida a nivel nacional gracias a su a mbito tecnolo gico y la capacidad creativa de innovar, crear y desarrollar herramientas digitales, 
<br> estilos y productos que marquen un futuro de buena interaccio n entre las personas y la tecnologí a.</p> 
</div> 
<div class="mvv-item"> 
<h3>Valores</h3> 
<ul style="list-style: none; padding-top: 10px;"> 
<li> Creatividad sin lí mites</li> 
<li> Responsabilidad</li> 
<li> Compromiso total</li> 
<li> Innovacio n constante</li> 
<li> Calidad en cada pixel</li> 
</ul> 
</div> 
</div> 
<!-- SERVICIOS --> 
<section class="services" id="servicios"> 
<h2>Servicios</h2> 
<div class="cards"> 
<div class="card"> 
<img src="lapiz.png"> 
<h3>Disen o Gra fico</h3> 
<p>Ima genes creativas para tu marca.</p> 
</div> 
<div class="card"> 
<img src="computadora.png"> 
<h3>Desarrollo Web</h3> 
<p>Pa ginas modernas y ra pidas.</p> 
</div> 
<div class="card"> 
<img src="marketing.png"> 
<h3>Marketing Digital</h3> 
<p>Haz crecer tu negocio online.</p> 
</div> 
</div> 
</section> 
<!-- CONTACTO --> 
<section class="contact" id="contacto"> 
<h2>Contacto</h2> 
<form> 
<input type="text" placeholder="Nombre" required> 
<input type="email" placeholder="Correo" required> 
<textarea placeholder="Mensaje" rows="4"></textarea> 
<button class="btn1">Enviar</button> 
</form> 
</section> 
<!-- SECCIO N SERVICIOS ACTUALIZADA --> 
<section class="services" id="servicios"> 
<h2>Nuestros Servicios</h2> 
<div class="cards"> 
<div class="card"> 
<img src="lapiz.png"> 
<h3>Disen o Gra fico</h3> 
<p>Identidad visual u nica.</p> 
<a href="#contacto" style="color:#7b2cbf; text-decoration:none; font-size:14px;">Solicitar cotizacio n →</a> 
</div> 
<div class="card"> 
<img src="computadora.png"> 
<h3>Desarrollo Web</h3> 
<p>Sitios optimizados y ra pidos.</p> 
<a href="#contacto" style="color:#7b2cbf; text-decoration:none; font-size:14px;">Verdemos →</a> </div> <div class="card"> <img src="https://picsum.photos/300/200?3"> <h3>Marketing Digital</h3> <p>Estrategias de crecimiento.</p> <a href="#contacto" style="color:#7b2cbf; text-decoration:none; font-size:14px;">Ma s info →</a> </div> </div> <!-- TABLA REQUERIDA --> <div class="table-container"> <h3>Comparativa de Paquetes</h3> <table> <thead> <tr> <th>Servicio</th> <th>Tiempo de Entrega</th> <th>Incluye Soporte</th> </tr> </thead> <tbody> <tr> <td>Disen o de Logo</td> <td>3-5 dí as</td> <td> </td></tr> <tr> <td>Campan a Ads</td> <td>Inmediato</td> <td> </td> </tr> </tbody> </table> </div> </section> Gracias, ahora necesito que le an adas la visio n, misio n y valores de la empresa debajo de la seccio n nosotros, manteniendo la misma este tica, tambie n por debajo de la seccio n de la tabla an ades otra seccio n que diga "testimonios simulados" con puntuacio n, manteniendo la misma este tica del resto de la pagina. Por favor /* SECCIO N MISIO N, VISIO N Y VALORES / .mvv-container { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 20px 50px 50px 50px; background: #1a1a1a; / Mantiene la este tica de la seccio n About */ } .mvv-item { flex: 1; min-width: 250px; max-width: 350px; padding: 25px; border-left: 4px solid #7b2cbf; background: rgba(255, 255, 255, 0.03); border-radius: 0 10px 10px 0; } .mvv-item h3 { color: #7b2cbf; margin-bottom: 10px; text-transform: uppercase; font-size: 18px; } /* SECCIO N TESTIMONIOS */ .testimonials { background: #0d0d0d; padding: 60px 20px; } .testimonial-grid { display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; margin-top: 30px; } .testimonial-card { background: #1a1a1a; padding: 30px; border-radius: 15px; width: 300px; box-shadow: 0 10px 20px rgba(0,0,0,0.2); border-bottom: 3px solid #7b2cbf; } .stars { color: #ffcc00; /* Color dorado para las estrellas */ margin-bottom: 10px; font-size: 18px; } .testimonial-card p { font-style: italic; font-size: 14px; color: #ccc; } .testimonial-card h4 { margin-top: 15px; color: white; font-size: 16px; } <div class="mvv-container"> <div class="mvv-item"> <h3>Misio n</h3> <p>Transformar las ideas de nuestros clientes en experiencias digitales impactantes que impulsen su crecimiento y e xito comercial.</p></div> <div class="mvv-item"> <h3>Visio n</h3> <p>Ser la agencia creativa referente en innovacio n digital, reconocida por nuestra excelencia en disen o y compromiso con los resultados.</p> </div> <div class="mvv-item"> <h3>Valores</h3> <ul style="list-style: none; padding-top: 10px;"> <li> Creatividad sin lí mites</li> <li> Compromiso total</li> <li> Innovacio n constante</li> <li> Calidad en cada pixel</li> </ul> </div> </div>?  </tr> <tr> <td>Landing Page</td> <td>7-10 dí as</td> <td> </td> demos →</a> 
</div> 
<div class="card"> 
<img src="marketing.png"> 
<h3>Marketing Digital</h3> 
<p>Estrategias de crecimiento.</p> 
<a href="#contacto" style="color:#7b2cbf; text-decoration:none; font-size:14px;">Ma s info →</a> 
</div> 
</div> 
<section class="testimonials"> 
<h2>Testimonios simulados</h2> 
<div class="testimonial-grid"> 
<div class="testimonial-card"> 
<div class="stars">★★★★★</div> 
<p>"El equipo de PIXELMIND supero nuestras expectativas. Lograron captar la esencia de nuestra marca desde el primer boceto."</p> 
<h4>— Roberto Me ndez, TechStart</h4> 
</div> 
<div class="testimonial-card"> 
<div class="stars">★★★★★</div> 
<p>"La velocidad de carga de nuestra nueva web es increí ble. El disen o es moderno y muy fa cil de navegar para nuestros clientes."</p> 
<h4>— Elena Torres, Studio Creativo</h4> 
</div> 
<div class="testimonial-card"> 
<div class="stars">★★★★☆</div> 
<p>"Gran atencio n al detalle y un soporte post-entrega excelente. Sin duda seguiremos trabajando con ellos en futuros proyectos."</p> 
<h4>— Carlos Ruiz, Emprendedor</h4> 
</div> 
</div> 
</section> 
<!-- TABLA REQUERIDA --> 
<div class="table-container"> 
<h3>Comparativa de Paquetes</h3> 
<table> 
<thead> 
<tr> 
<th>Servicio</th> 
<th>Tiempo de Entrega</th> 
<th>Incluye Soporte</th> 
</tr> 
</thead> 
<tbody> 
<tr> 
<td>Disen o de Logo</td> 
<td>3-5 dí as</td> 
<td> </td> 
</tr> 
<tr> 
<td>Landing Page</td> 
<td>7-10 dí as</td> 
<td> </td> 
</tr> 
<tr> 
<td>Campan a Ads</td> 
<td>Inmediato</td> 
<td> </td> 
</tr> 
</tbody> 
</table> 
</div> 
</section> 
<footer> 
©️ 2024 PIXELMIND - Todos los derechos reservados 
</footer> 
</body> 
</html>
