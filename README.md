<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imaad Robotics</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0b1020;
color:white;
overflow-x:hidden;
}

header{
background:#111827;
padding:20px;
position:sticky;
top:0;
z-index:1000;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
max-width:1200px;
margin:auto;
}

.logo{
font-size:24px;
font-weight:700;
color:#00e5ff;
}

nav ul{
display:flex;
list-style:none;
gap:20px;
}

nav ul li a{
color:white;
text-decoration:none;
}

.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:40px;
}

.hero-content h1{
font-size:60px;
margin-bottom:20px;
}

.hero-content span{
color:#00e5ff;
}

.hero-content p{
max-width:700px;
margin:auto;
color:#cbd5e1;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:14px 30px;
border-radius:12px;
text-decoration:none;
font-weight:600;
margin:10px;
}

.primary{
background:#00e5ff;
color:black;
}

.secondary{
border:2px solid #00e5ff;
color:white;
}

.section{
padding:80px 20px;
max-width:1200px;
margin:auto;
}

.title{
font-size:40px;
text-align:center;
margin-bottom:40px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#111827;
padding:25px;
border-radius:15px;
}

.card h3{
margin-bottom:10px;
color:#00e5ff;
}

.skills{
display:flex;
flex-wrap:wrap;
gap:15px;
justify-content:center;
}

.skill{
background:#111827;
padding:12px 20px;
border-radius:50px;
}

.contact{
max-width:700px;
margin:auto;
}

.contact a{
display:block;
text-align:center;
padding:18px;
margin:15px 0;
border-radius:12px;
font-weight:600;
text-decoration:none;
}

.email{
background:#16a34a;
color:white;
}

.phone{
background:#2563eb;
color:white;
}

.github{
background:#ffffff;
color:black;
}

.youtube{
background:#dc2626;
color:white;
}

footer{
text-align:center;
padding:30px;
background:#111827;
margin-top:50px;
}

.hidden-btn{
position:fixed;
bottom:20px;
right:20px;
width:60px;
height:60px;
border:none;
border-radius:50%;
background:#111827;
color:#00e5ff;
font-size:18px;
cursor:pointer;
}

.lab{
position:fixed;
top:0;
right:-100%;
width:100%;
max-width:400px;
height:100%;
background:#05070d;
padding:30px;
transition:.4s;
overflow:auto;
}

.lab.open{
right:0;
}

.close{
font-size:30px;
cursor:pointer;
float:right;
}

@media(max-width:768px){
.hero-content h1{
font-size:40px;
}
nav ul{
display:none;
}
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">IMAAD DANISH</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero">
<div class="hero-content">
<h1>Hi, I'm Imaad<span>Danish</span></h1>
<p>
Professional Robotics, Artificial Intelligence,
Machine Learning and Automation Solutions by Imaad Danish.
</p>

<a href="#projects" class="btn primary">Explore Projects</a>
<a href="#contact" class="btn secondary">Contact Me</a>
</div>
</section>

<section id="about" class="section">
<h2 class="title">About Me</h2>

<div class="grid">

<div class="card">
<h3>AI Development</h3>
<p>Building smart systems using Artificial Intelligence and Machine Learning.</p>
</div>

<div class="card">
<h3>Robotics</h3>
<p>Designing intelligent robotic systems and automation projects.</p>
</div>

<div class="card">
<h3>Innovation</h3>
<p>Creating future-ready technology solutions for real-world problems.</p>
</div>

</div>
</section>

<section id="projects" class="section">
<h2 class="title">Projects</h2>

<div class="grid">

<div class="card">
<h3>Autonomous Robot</h3>
<p>Robot navigation and obstacle avoidance system.</p>
</div>

<div class="card">
<h3>Computer Vision</h3>
<p>AI-powered object detection and recognition.</p>
</div>

<div class="card">
<h3>Voice Assistant</h3>
<p>JARVIS-inspired intelligent assistant.</p>
</div>

<div class="card">
<h3>Smart Automation</h3>
<p>IoT and cloud-based automation systems.</p>
</div>

</div>
</section>

<section id="skills" class="section">
<h2 class="title">Technology Stack</h2>

<div class="skills">
<div class="skill">Robotics</div>
<div class="skill">AI</div>
<div class="skill">Machine Learning</div>
<div class="skill">Computer Vision</div>
<div class="skill">Python</div>
<div class="skill">C++</div>
<div class="skill">Arduino</div>
<div class="skill">Raspberry Pi</div>
<div class="skill">IoT</div>
</div>
</section>

<section id="contact" class="section">
<h2 class="title">Contact</h2>

<div class="contact">

<a class="email" href="mailto:imaad.danish003@gmail.com">
imaad.danish003@gmail.com
</a>

<a class="phone" href="https://wa.me/919997554431">
+91 9997554431
</a>

<a class="github" href="https://github.com/imaadwork">
GitHub
</a>

<a class="youtube" href="https://youtube.com/@lumorixvfxofficial">
YouTube
</a>

</div>
</section>

<footer>
© 2026 Imaad Danish | NEXT LEVEL PORTFOLIO 
</footer>

<button class="hidden-btn" onclick="openLab()">67</button>

<div class="lab" id="lab">

<div class="close" onclick="closeLab()">×</div>

<h2>Technologia // 67</h2>

<br>

<p>
Welcome to the Hidden Robotics Laboratory.
Advanced experimental systems are under development.
</p>

<br>

<iframe
width="100%"
height="220"
src="https://www.myinstants.com/instant/67-sound-90775/embed/"
style="border:none;">
</iframe>

<br><br>

<iframe
width="100%"
height="220"
src="https://www.myinstants.com/instant/technologia-53863/embed/"
style="border:none;">
</iframe>

</div>

<script>
function openLab(){
document.getElementById("lab").classList.add("open");
}

function closeLab(){
document.getElementById("lab").classList.remove("open");
}
</script>
