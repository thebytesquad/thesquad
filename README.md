<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Byte Squad</title>
<style>
body, html {
margin: 0;
padding: 0;
font-family: Arial, sans-serif;
background-color: #121212;
color: #dcdcdc;
overflow: auto;
}
header {
background-color: #333;
color: white;
padding: 15px;
text-align: center;
}
nav ul {
list-style: none;
padding: 0;
margin: 0;
display: flex;
justify-content: center;
}
nav ul li {
margin: 0 15px;
}
nav ul li a {
color: white;
text-decoration: none;
font-weight: bold;
}
section {
padding: 60px 20px;
text-align: center;
}
#hero {
background-color: #1a1a1a;
animation: fadeIn 1s forwards;
}
#features {
background-color: #2a2a2a;
animation: slideIn 1s forwards;
}
#partnerships, #faq, #terms, #privacy, #contact {
background-color: #333;
color: #dcdcdc;
animation: zoomIn 1s forwards;
}
footer {
background-color: #212121;
color: white;
text-align: center;
padding: 15px;
position: relative;
bottom: 0;
}
#terms, #privacy {
padding: 30px;
text-align: left;
}
@keyframes fadeIn {
from { opacity: 0; }
to { opacity: 1; }
}
@keyframes slideIn {
from { transform: translateX(-100%); }
to { transform: translateX(0); }
}
@keyframes zoomIn {
from { transform: scale(0); }
to { transform: scale(1); }
}
#bio {
padding: 50px 20px;
background-color: #1a1a1a;
animation: fadeIn 2s forwards;
}
</style>
</head>
<body>

<header>
<h1>The Byte Squad</h1>
<nav>
<ul>
<li><a href="#bio">About Us</a></li>
<li><a href="#features">Features</a></li>
<li><a href="#partnerships">Partnerships</a></li>
<li><a href="#faq">FAQ</a></li>
<li><a href="#terms">Terms</a></li>
<li><a href="#privacy">Privacy</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section id="bio">
<h2>About The Byte Squad</h2>
<p>The Byte Squad is a collective of passionate coders dedicated to elevating the coding experience through innovative solutions and engaging community activities. Since our inception, we've strived to create an environment where both novice and experienced programmers can thrive. Our cutting-edge features are designed to simplify complex coding tasks and our numerous partnerships with industry leaders provide unique opportunities for growth and collaboration. At The Byte Squad, we believe that the path to coding excellence is paved with support, education, and a bit of fun. Join our community and take your coding skills to the next level with exclusive access to resources, tutorials, and events. Our commitment is to foster a collaborative atmosphere where each member feels empowered to explore, innovate, and achieve their full potential. Welcome to The Byte Squad – where your coding journey begins. For more information and to join our Discord server, visit The Byte Squad Discord.</p>
</section>

<section id="features">
<h2>Features</h2>
<p>Discover our amazing features designed for coding enthusiasts.</p>
</section>

<section id="partnerships">
<h2>Partnerships</h2>
<p>Collaborate with industry leaders and grow together.</p>
</section>

<section id="faq">
<h2>FAQ</h2>
<p>Find answers to the most frequently asked questions.</p>
</section>

<section id="terms">
<h2>Terms & Conditions</h2>
<p>Understand the rules and guidelines to ensure a seamless experience.</p>
<h3>Refund Policy</h3>
<p>If you're not satisfied with our services, contact us within 30 days for a full refund.</p>
<p>Only valid for purchases made directly through our website.</p>
</section>

<section id="privacy">
<h2>Privacy Policy</h2>
<p>Your privacy is important to us. Read our policy to understand how we handle your data.</p>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>Email: thebytesquadofficial@gmail.com</p>
</section>

<footer>
<p>&copy; 2024 The Byte Squad. All rights reserved. <br> <a href="https://discord.gg/your-server-link">Join our Discord Server</a></p>
</footer>

<script>
document.addEventListener('DOMContentLoaded', () => {
const sections = document.querySelectorAll('section');
sections.forEach(section => {
section.style.opacity = 0;
});
window.addEventListener('scroll', () => {
sections.forEach(section => {
const rect = section.getBoundingClientRect();
if (rect.top >= 0 && rect.bottom <= window.innerHeight) {
section.style.opacity = 1;
section.style.transition = 'opacity 1s';
}
});
});
});
</script>

</body>
</html>
