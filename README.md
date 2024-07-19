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
overflow: hidden;
font-family: Arial, sans-serif;
background-color: #f4f4f4;
color: #333;
}
.intro {
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
background-color: #282c34;
}
.logo-animation {
opacity: 0;
animation: fadeIn 2s forwards, bounce 2s 2s;
}
.logo {
width: 200px;
cursor: pointer;
}
@keyframes fadeIn {
to { opacity: 1; }
}
@keyframes bounce {
0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
40% { transform: translateY(-30px); }
60% { transform: translateY(-15px); }
}
.main-content {
display: none;
opacity: 0;
overflow: auto;
height: 100vh;
}
.show {
display: block;
animation: fadeInMain 1s forwards;
}
@keyframes fadeInMain {
to { opacity: 1; }
}
header {
background-color: #333;
color: white;
padding: 10px;
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
padding: 50px 20px;
text-align: center;
}
#hero {
background-color: #61dafb;
}
#features {
background-color: #f1f1f1;
}
#partnerships, #faq, #terms, #privacy, #contact {
background-color: #e2e2e2;
}
footer {
background-color: #333;
color: white;
text-align: center;
padding: 10px;
position: relative;
bottom: 0;
}
#terms, #privacy {
padding: 20px;
text-align: left;
}
</style>
</head>
<body>

<div id="intro" class="intro">
<div class="logo-animation">
<img src="YOUR_LOGO_LINK_HERE" alt="The Byte Squad Logo" class="logo">
</div>
</div>

<div id="main-content" class="main-content hide">
<header>
<h1>The Byte Squad</h1>
<nav>
<ul>
<li><a href="#hero">Home</a></li>
<li><a href="#features">Features</a></li>
<li><a href="#partnerships">Partnerships</a></li>
<li><a href="#faq">FAQ</a></li>
<li><a href="#terms">Terms</a></li>
<li><a href="#privacy">Privacy</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section id="hero">
<h1>Welcome to The Byte Squad</h1>
<p>Your coding journey starts here.</p>
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
<p>&copy; 2024 The Byte Squad. All rights reserved.</p>
</footer>
</div>

<script>
document.addEventListener('DOMContentLoaded', function () {
const intro = document.getElementById('intro');
const mainContent = document.getElementById('main-content');
document.querySelector('.logo').addEventListener('click', function () {
intro.style.animation = 'fadeOut 1s forwards';
setTimeout(() => {
intro.style.display = 'none';
mainContent.classList.remove('hide');
mainContent.classList.add('show');
}, 1000);
});
});

@keyframes fadeOut {
to { opacity: 0; }
}
</script>

</body>
</html>
