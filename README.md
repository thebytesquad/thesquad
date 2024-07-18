<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Byte Squad</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
<style>
body {
  font-family: 'Roboto', sans-serif;
  background: #121212;
  color: #fff;
  margin: 0;
  padding: 0;
}
header {
  text-align: center;
  background-color: #1f1f1f;
  color: white;
  padding: 20px 0;
  position: sticky; 
  top: 0;
  z-index: 1000;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(10px);
}
.navbar {
  display: flex;
  justify-content: center;
  background: #1f1f1f;
  padding: 10px;
  box-shadow: 0 1px 5px rgba(0, 0, 0, 0.2);
}
.navbar a {
  color: #fff;
  text-decoration: none;
  font-size: 1.1em;
  padding: 10px 20px;
  transition: background 0.3s, color 0.3s;
}
.navbar a:hover {
  background: #4CAF50;
  color: #fff;
  border-radius: 5px;
}
.container {
  width: 80%;
  margin: auto;
  overflow: hidden;
}
.section {
  background: #1e1e1e;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
  border-radius: 15px;
  color: #ccc;
  animation: slideUp 1s ease-out both;
  transform: translateY(50px);
  opacity: 0;
}
.section h2, .section h3 {
  color: #4CAF50;
}
.section p {
  line-height: 1.6;
  color: #bbb;
}
.section a {
  color: #4CAF50;
  text-decoration: none;
  font-weight: bold;
}
.card {
  border: 1px solid #333;
  border-radius: 15px;
  margin-bottom: 20px;
  padding: 20px;
  background-color: #2a2a2a;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}
.section .image-card img {
  width: 100%;
  border-radius: 15px;
}
@keyframes slideUp {
  0% {
    transform: translateY(50px);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}
.fade-in {
  opacity: 0;
  animation: fadeIn 1s ease-in-out forwards;
}
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
.hero {
  background: rgba(0, 0, 0, 0.7);
  padding: 100px 20px;
  text-align: center;
  color: #fff;
}
.hero h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}
.hero p {
  font-size: 1.2em;
  line-height: 1.6;
  margin-bottom: 20px;
}
.hero a {
  background: #4CAF50;
  color: #fff;
  padding: 12px 25px;
  border-radius: 25px;
  text-decoration: none;
  font-size: 1.1em;
}
.features {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.feature {
  flex: 0 0 48%;
  margin-bottom: 20px;
}
@media (max-width: 768px) {
  .feature {
    flex: 0 0 100%;
  }
}
.feature img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 10px;
}
.feature h3 {
  margin-top: 0;
}
.footer {
  background: #1f1f1f;
  padding: 20px;
  text-align: center;
  color: #fff;
}
.footer a {
  color: #4CAF50;
  text-decoration: none;
  margin: 0 10px;
  font-size: 1.2em;
}
.footer p {
  margin: 10px 0 0 0;
}
</style>
</head>
<body>

<header>
  <div class="navbar">
    <a href="#about">About</a>
    <a href="#features">Features</a>
    <a href="#terms">Terms</a>
    <a href="#privacy">Privacy</a>
    <a href="#apps">Apps</a>
    <a href="#partnerships">Partnerships</a>
    <a href="#team">Team</a>
    <a href="#faq">FAQ</a>
    <a href="#contact">Contact</a>
  </div>
  <h1>Welcome to The Byte Squad</h1>
  <p>Your go-to hub for digital excellence</p>
</header>

<section class="hero">
  <h1>Join The Future of Tech</h1>
  <p>Discover the latest trends, connect with like-minded tech enthusiasts, and elevate your digital game with The Byte Squad.</p>
  <a href="#about">Learn More</a>
</section>

<div class="container">

<section id="about" class="section fade-in">
  <h2>About The Byte Squad</h2>
  <div class="card">
<p>The Byte Squad is a community of tech enthusiasts and experts dedicated to bringing you the latest in software development, technical support, and digital trends. Join our Discord server to connect with like-minded individuals and get exclusive access to resources and support.</p>
    <a href="your-discord-link" target="_blank">Join Our Discord Server</a>
  </div>
</section>

<section id="features" class="section fade-in">
  <h2>Our Amazing Features</h2>
  <div class="features">
    <div class="feature card">
      <img src="feature1.jpg" alt="Feature 1">
      <h3>Exclusive Tutorials</h3>
      <p>Get access to step-by-step guides and tutorials crafted by industry experts.</p>
    </div>
    <div class="feature card">
      <img src="feature2.jpg" alt="Feature 2">
      <h3>Community Support</h3>
      <p>Join discussions, get help with your projects, and share your knowledge with others.</p>
    </div>
    <div class="feature card">
      <img src="feature3.jpg" alt="Feature 3">
      <h3>Latest Tech News</h3>
      <p>Stay updated with the latest trends and news in the tech world.</p>
    </div>
    <div class="feature card">
      <img src="feature4.jpg" alt="Feature 4">
      <h3>Networking Opportunities</h3>
      <p>Connect with professionals and enthusiasts from around the globe.</p>
    </div>
  </div>
</section>

<section id="terms" class="section fade-in">
  <h2>Terms & Conditions</h2>
  <div class="card">
    <!-- Terms & Conditions content here -->
  </div>
</section>

<section id="privacy" class="section fade-in">
  <h2>Privacy Policy</h2>
  <div class="card">
    <!-- Privacy content here -->
  </div>
</section>

<section id="apps" class="section fade-in">
  <h2>Our Apps</h2>
  <div class="card">
    <h3>Zara</h3>
    <p>Zara is your ultimate culinary companion, making food ordering and dining experiences a breeze with seamless integration and personalized recommendations.</p>

    <h3>Byte Helper</h3>
<p>Byte Helper offers top-notch technical support and solutions to keep your digital life running smoothly, whether it's troubleshooting issues or optimizing performance.</p>
  </div>
</section>

<section id="partnerships" class="section fade-in">
  <h2>Our Partnerships</h2>
  <div class="card">
    <p>We partner with the best in the industry to bring you unparalleled resources, exclusive content, and cutting-edge technology solutions. Explore the partnerships that empower The Byte Squad to excel and innovate.</p>
  </div>
</section>

<section id="team" class="section fade-in">
  <h2>Meet the Team</h2>
  <div class="card">
    <p>Our team consists of passionate individuals with diverse expertise in various fields of technology. Get to know the personalities driving The Byte Squad to new heights.</p>
  </div>
</section>

<section id="contact" class="section fade-in">
  <h2>Contact Us</h2>
  <div class="card">
    <p>If you have any questions, feel free to reach out to us at:</p>
    <p><strong>thebytesquadofficial@gmail.com</strong></p>
  </div>
</section>

<section id="faq" class="section fade-in">
  <h2>Frequently Asked Questions</h2>
  <div class="card">
    <h3>What services do we offer?</h3>
    <p>We offer a range of services including software development, technical support, and digital consultancy.</p>

    <h3>How can I join The Byte Squad?</h3>
    <p>You can join our community by signing up on our website and joining our Discord server.</p>

    <h3>Can I contribute to The Byte Squad?</h3>
    <p>Yes, we welcome contributions from tech enthusiasts and professionals. Get in touch with us to learn more.</p>
  </div>
</section>

</div>

<footer class="footer">
  <div>
    <a href="#about">About</a>
    <a href="#features">Features</a>
    <a href="#terms">Terms</a>
    <a href="#privacy">Privacy</a>
    <a href="#apps">Apps</a>
    <a href="#partnerships">Partnerships</a>
    <a href="#team">Team</a>
    <a href="#faq">FAQ</a>
[]
    <a href="#contact">Contact</a>
  </div>
  <p>&copy; 2024 The Byte Squad. All rights reserved.</p>
</footer>

</body>
</html>
