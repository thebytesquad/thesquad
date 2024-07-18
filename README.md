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
background: url('your-background-image.jpg') no-repeat center center fixed;
background-size: cover;
margin: 0;
padding: 0;
color: #fff;
}
header {
text-align: center;
background-color: rgba(76, 175, 80, 0.9);
color: white;
padding: 20px 0;
position: sticky;
top: 0;
z-index: 1000;
box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
backdrop-filter: blur(10px);
}
.container {
width: 80%;
margin: auto;
overflow: hidden;
}
.section {
background: rgba(255, 255, 255, 0.9);
padding: 20px;
margin-bottom: 20px;
box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
border-radius: 15px;
color: #333;
animation: slideUp 1s ease-out both;
transform: translateY(50px);
opacity: 0;
}
.section h2, .section h3 {
color: #4CAF50;
}
.section p {
line-height: 1.6;
color: #666;
}
.section a {
color: #4CAF50;
text-decoration: none;
font-weight: bold;
}
.card {
border: 1px solid #ddd;
border-radius: 15px;
margin-bottom: 20px;
padding: 20px;
background-color: #fff;
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
.navbar {
display: flex;
justify-content: space-between;
align-items: center;
padding: 10px;
background: rgba(76, 175, 80, 0.9);
position: sticky;
top: 0;
z-index: 1000;
box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
backdrop-filter: blur(10px);
}
.navbar a {
color: #fff;
text-decoration: none;
font-size: 1.1em;
padding: 10px;
}
.hero {
background: rgba(0, 0, 0, 0.5);
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
background: rgba(76, 175, 80, 0.9);
padding: 20px;
text-align: center;
color: #fff;
}
.footer a {
color: #fff;
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
<a href="#terms">Terms</a>
<a href="#privacy">Privacy</a>
<a href="#apps">Apps</a>
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
<h3>1. Introduction</h3>
<p>Welcome to The Byte Squad. These terms and conditions outline the rules and regulations for the use of our website.</p>

<h3>2. Acceptance of Terms</h3>
<p>By accessing our website, you accept these terms and conditions in full. If you disagree with any part of these terms, please do not use our website.</p>

<h3>3. Privacy Policy</h3>
<p>Your privacy is important to us. Please read our <a href="#privacy">Privacy Policy</a> to understand how we collect, use, and protect your information.</p>

<h3>4. Intellectual Property</h3>
<p>All content on this site, including but not limited to text, graphics, logos, and images, is the property of The Byte Squad or its content suppliers and protected by intellectual property laws.</p>

<h3>5. User Responsibilities</h3>
<p>Users agree to use the website only for lawful purposes and in a way that does not infringe the rights of or restrict the use and enjoyment of this site by any third party.</p>

<h3>6. Limitation of Liability</h3>
<p>The Byte Squad will not be liable for any damages arising from the use or inability to use the website or from any content posted on the site.</p>

<h3>7. Refund Policy</h3>
<p>We offer refunds for purchases made through our website within 24 hours of the transaction. To request a refund, please contact our support team with your purchase details.</p>

<h3>8. Changes to Terms</h3>
<p>We reserve the right to revise these terms and conditions at any time. Users are encouraged to review the terms periodically to stay informed of updates.</p>

<h3>9. Governing Law</h3>
<p>These terms and conditions are governed by and construed in accordance with the laws of our jurisdiction. Any disputes relating to these terms will be subject to the exclusive jurisdiction of the courts of our jurisdiction.</p>

<p>By using this website, you agree to these terms and conditions.</p>
</div>
</section>

<section id="privacy" class="section fade-in">
<h2>Privacy Policy</h2>
<div class="card">
<h3>1. Introduction</h3>
<p>We value your privacy and are committed to protecting your personal information. This Privacy Policy outlines how we collect, use, and safeguard your data.</p>

<h3>2. Data Collection</h3>
<p>We collect personal information that you provide to us directly, such as your name, email address, and payment details. We also collect data automatically through cookies and similar technologies.</p>

<h3>3. Use of Data</h3>
<p>We use your personal information to provide, maintain, and improve our services, process transactions, and communicate with you about our offerings.</p>

<h3>4. Data Sharing</h3>
<p>We do not sell your personal information to third parties. We may share your data with trusted partners who assist us in operating our website and conducting our business, provided they agree to keep your data confidential.</p>

<h3>5. Data Security</h3>
<p>We implement various security measures to protect your personal information from unauthorized access, alteration, disclosure, or destruction.</p>

<h3>6. Your Rights</h3>
<p>You have the right to access, update, or delete your personal information. To exercise these rights, please contact our support team.</p>

<h3>7. Changes to this Policy</h3>
<p>We may update this Privacy Policy from time to time. Users are encouraged to review the policy periodically to stay informed of any changes.</p>

<h3>8. Contact Us</h3>
<p>If you have any questions or concerns about our Privacy Policy, please contact us at <strong>thebytesquadofficial@gmail.com</strong>.</p>

<p>By using this website, you agree to the terms of this Privacy Policy.</p>
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
[]
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
<a href="#terms">Terms</a>
<a href="#privacy">Privacy</a>
<a href="#apps">Apps</a>
<a href="#contact">Contact</a>
</div>
<p>&copy; 2024 The Byte Squad. All rights reserved.</p>
</footer>

</body>
</html>
