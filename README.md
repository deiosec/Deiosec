<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DEIOSEC — Graphic Design</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
background:#050505;
color:#fff;
font-family:Arial,sans-serif;
line-height:1.6;
}
header{
display:flex;
justify-content:space-between;
align-items:center;
padding:25px 7%;
border-bottom:1px solid #222;
}
.logo{font-weight:bold;letter-spacing:4px}
nav a{
color:#aaa;
text-decoration:none;
margin-left:20px;
font-size:12px;
}
nav a:hover{color:#fff}

.hero{
min-height:85vh;
display:flex;
flex-direction:column;
justify-content:center;
padding:0 7%;
}
.hero h1{
font-size:clamp(60px,15vw,150px);
letter-spacing:-5px;
line-height:.9;
}
.hero p{
color:#888;
margin-top:25px;
max-width:450px;
}
.button{
display:inline-block;
margin-top:35px;
border:1px solid #555;
padding:12px 25px;
color:#fff;
text-decoration:none;
width:max-content;
font-size:12px;
letter-spacing:2px;
}
.button:hover{background:#fff;color:#000}

section{
padding:100px 7%;
border-top:1px solid #222;
}
.label{
font-size:11px;
color:#666;
letter-spacing:3px;
margin-bottom:25px;
}
h2{font-size:42px}
.about{
max-width:650px;
color:#aaa;
font-size:18px;
}
.work{
border:1px solid #222;
padding:50px 25px;
margin-top:30px;
color:#555;
text-align:center;
}
footer{
padding:40px 7%;
color:#555;
font-size:11px;
letter-spacing:2px;
}
</style>
</head>

<body>

<header>
<div class="logo">DEIOSEC</div>

<nav>
<a href="#work">WORK</a>
<a href="#about">ABOUT</a>
<a href="#contact">CONTACT</a>
</nav>
</header>

<main>

<div class="hero">
<h1>DEIOSEC</h1>
<p>Graphic Design & Visual Identity.</p>
<a class="button" href="#work">VIEW WORK</a>
</div>

<section id="work">
<div class="label">01 — WORK</div>
<h2>Portfolio</h2>

<div class="work">
COMING SOON
</div>
</section>

<section id="about">
<div class="label">02 — ABOUT</div>
<h2>Design with purpose.</h2>
<p class="about">
DEIOSEC is a creative space focused on graphic design,
visual identity and digital aesthetics.
</p>
</section>

<section id="contact">
<div class="label">03 — CONTACT</div>
<h2>Let's create.</h2>
<a class="button" href="mailto:hello@deiosec.com">CONTACT ME</a>
</section>

</main>

<footer>
© 2026 DEIOSEC — ALL RIGHTS RESERVED
</footer>

</body>
</html>
