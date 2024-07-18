# thesquad
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Byte Squad</title>
<style>
body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: #121212; color: #e0e0e0; }
header { padding: 20px; background: #1a1a1a; color: white; text-align: center; }
nav { display: flex; justify-content: center; background: #2a2a2a; padding: 10px; position: sticky; top: 0; z-index: 1000; }
nav a { margin: 0 15px; color: white; text-decoration: none; font-weight: bold; transition: color 0.3s; }
nav a:hover { color: #f39c12; }
section { padding: 50px 20px; }
footer { text-align: center; padding: 20px; background: #1a1a1a; color: white; position: sticky; bottom: 0; width: 100%; }
.container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
h2 { color: #f39c12; margin-top: 50px; }
.card { background: #202020; border-radius: 15px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5); margin: 20px 0; padding: 20px; transition: transform 0.3s; }
.card:hover { transform: translateY(-10px); }
button { background: #f39c12; color: black; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; transition: background 0.3s; }
button:hover { background: #e67e22; }
.fade-in { animation: fadeIn 2s; }
@keyframes fadeIn {
from { opacity: 0; }
to { opacity: 1; }
}
</style>
</head>
<body>
<header>
<h1>The Byte Squad</h1>
</header>

<nav>
<a href="#home">Home</a>
<a href="#terms">Terms & Conditions</a>
<a href="#privacy">Privacy Policy</a>
<a href="#apps">Our Apps</a>
<a href="#contact">Contact Us</a>
</nav>

<div class="container">
<section id="home" class="fade-in">
<h2>About Us</h2>
<div class="card">
<p>The Byte Squad is dedicated to delivering cutting-edge tech solutions. Our team of experts is constantly working on innovative apps to solve real-world problems.</p>
</div>
</section>

<section id="terms" class="fade-in">
<h2>Terms & Conditions</h2>
<div class="card">
<p>Your terms and conditions content goes here. Detailed information about user agreements, legal responsibilities, and more.</p>
</div>
</section>

<section id="privacy" class="fade-in">
<h2>Privacy Policy</h2>
<div class="card">
<p>Your privacy policy content goes here. Information about data collection, usage, and user rights.</p>
</div>
</section>

<section id="apps" class="fade-in">
<h2>Our Apps</h2>
<div class="card">
<p>Your apps information goes here. Include descriptions, features, and any available download links.</p>
</div>
</section>

<section id="contact" class="fade-in">
<h2>Contact Us</h2>
<div class="card">
<p>If you have any questions, feel free to reach out through our contact form.</p>
<button>Contact Form</button>
</div>
</section>
</div>

<footer>
<p>© 2024 The Byte Squad. All rights reserved.</p>
</footer>
</body>
</html>
