# 22patelo1-cyber.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Astrixia.ai</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
body {
  margin:0;
  font-family: 'Inter', sans-serif;
  background:#fff;
  color:#111;
}

header {
  position:fixed;
  top:0;
  width:100%;
  background:white;
  display:flex;
  justify-content:space-between;
  padding:20px 60px;
  border-bottom:1px solid #eee;
  z-index:1000;
}

nav a {
  margin-left:20px;
  color:#111;
  text-decoration:none;
  font-weight:400;
}

section {
  padding:120px 60px;
}

.hero {
  text-align:center;
  padding-top:160px;
}

h1 {
  font-size:48px;
  font-weight:400;
}

button {
  padding:12px 28px;
  background:#111;
  color:white;
  border:none;
  cursor:pointer;
  margin-top:20px;
}

.card {
  border:1px solid #eee;
  padding:30px;
  margin:20px 0;
}

.popup {
  position:fixed;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background:rgba(0,0,0,.6);
  display:none;
  justify-content:center;
  align-items:center;
}

.popup-content {
  background:white;
  padding:30px;
  width:90%;
  max-width:600px;
}

footer {
  text-align:center;
  padding:40px;
  border-top:1px solid #eee;
}

@media(max-width:768px){
  header {flex-direction:column; text-align:center;}
  section {padding:100px 20px;}
}
</style>
</head>

<body>

<header>
  <strong>ASTRIXIA.AI</strong>
  <nav>
    <a href="#home">Home</a>
    <a href="#store">Store</a>
    <a href="#pricing">Pricing</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<!-- HOME -->
<section id="home" class="hero">
  <h1>AI Lead Generation for Real Estate Agents</h1>
  <p>Minimal. Automated. Scalable.</p>
  <button onclick="openPopup()">Book a Call</button>
</section>

<!-- STORE -->
<section id="store">
  <h1>Store</h1>

  <div class="card">
    <h3>AI Lead Generation System</h3>
    <p>Automated funnel that generates qualified leads for real estate agents.</p>
    <button onclick="openPopup()">Book a Call</button>
  </div>

  <div class="card">
    <h3>Custom AI Sales Assistant</h3>
    <p>We build a custom AI assistant to handle inquiries and convert prospects.</p>
    <button onclick="openPopup()">Book a Call</button>
  </div>
</section>

<!-- PRICING -->
<section id="pricing">
  <h1>Pricing</h1>

  <div class="card">
    <h3>Starter</h3>
    <p>$499 / month</p>
  </div>

  <div class="card">
    <h3>Pro</h3>
    <p>$999 / month</p>
  </div>

  <div class="card">
    <h3>Enterprise</h3>
    <p>Custom Pricing</p>
    <button onclick="openPopup()">Book a Call</button>
  </div>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials">
  <h1>Testimonials</h1>

  <div class="card">
    <p>"Astrixia doubled my leads in 30 days."</p>
    <strong>- John D.</strong>
  </div>

  <div class="card">
    <p>"Best AI lead system we've used."</p>
    <strong>- Sarah M.</strong>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <h1>About Astrixia</h1>
  <p>Astrixia builds AI-powered lead generation systems for real estate professionals.</p>
</section>

<!-- CONTACT -->
<section id="contact">
  <h1>Contact</h1>
  <p>Email: hello@astrixia.ai</p>
  <button onclick="openPopup()">Book a Call</button>
</section>

<!-- POPUP -->
<div id="popup" class="popup">
  <div class="popup-content">
    <h2>Book a Call</h2>
    <iframe src="YOUR_GOOGLE_CALENDAR_LINK" width="100%" height="500"></iframe>
    <button onclick="closePopup()">Close</button>
  </div>
</div>

<footer>
  © 2026 Astrixia.ai
</footer>

<script>
function openPopup(){
  document.getElementById("popup").style.display="flex";
}
function closePopup(){
  document.getElementById("popup").style.display="none";
}
</script>

</body>
</html>
