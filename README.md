# Beauty-Cave
< Angelique Williams html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Glow Beauty Studio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fff0f5;
      color: #333;
    }
    header {
      background-color: #ff69b4;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 40px;
    }
    nav {
      background: #ffa3c8;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #eee;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>Glow Beauty Studio</h1>
  <p>Your glow, our passion.</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Us</h2>
  <p>
    Welcome to Glow Beauty Studio – where beauty meets care. We are passionate about making you feel confident and radiant. 
    Whether it's a relaxing facial, professional makeup, or a rejuvenating massage, our goal is to help you shine from the inside out.
  </p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Facials</h3>
      <p>Deep cleansing, hydration, and glow-enhancing facials tailored to your skin.</p>
    </div>
    <div class="card">
      <h3>Makeup</h3>
      <p>Professional makeup for weddings, parties, photoshoots, and more.</p>
    </div>
    <div class="card">
      <h3>Massages</h3>
      <p>Relaxing and therapeutic massages to ease stress and tension.</p>
    </div>
    <div class="card">
      <h3>Waxing & Brows</h3>
      <p>Smooth skin and perfectly shaped brows using gentle techniques.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>
    Email: <strong>glowbeauty@example.com</strong><br>
    Phone: <strong>+27 60 123 4567</strong><br>
    Instagram: <strong>@glowbeautystudio</strong><br>
    Location: Cape Town, South Africa
  </p>
</section>

<footer>
  &copy; 2025 Glow Beauty Studio. All rights reserved.
</footer>

</body>
</html>
