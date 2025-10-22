<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ASTYL – Luxury in Every Thread</title>
  <link rel="stylesheet" href="style.css">
  <style>
    /* Basic professional styles */
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      color: #333;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Navbar */
    .navbar {
      background: #111;
      color: #fff;
      padding: 1rem 0;
    }
    .navbar .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 90%;
      margin: auto;
    }
    .logo {
      font-size: 1.5rem;
      font-weight: bold;
      color: #ff6600;
    }
    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }
    .nav-links a:hover {
      color: #ff6600;
    }

    /* Hero */
    .hero {
      background: url('hero-bg.jpg') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }
    .hero h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
    }
    .btn {
      padding: 0.8rem 1.5rem;
      background: #ff6600;
      color: #fff;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #e55a00;
    }

    section {
      padding: 4rem 0;
    }
    .container {
      width: 90%;
      margin: auto;
    }

    /* Members Section */
    .experience-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .experience-card {
      background: #f9f9f9;
      padding: 1.5rem;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .experience-card:hover {
      transform: translateY(-5px);
    }

    /* About Section */
    .about p {
      margin-bottom: 1rem;
      font-size: 1.1rem;
    }

    /* Testimonials */
    blockquote {
      font-style: italic;
      border-left: 4px solid #ff6600;
      padding-left: 1rem;
      margin: 1rem 0;
      color: #555;
    }

    /* Footer */
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 2rem 0;
    }

  </style>
</head>
<body>

  <!-- Header / Navbar -->
  <header class="navbar">
    <div class="container">
      <div class="logo">ASTYL</div>
      <nav>
        <ul class="nav-links">
          <li><a href="about.html">About Us</a></li>
          <li><a href="https://www.instagram.com/astyl.2">Instagram</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>ASTYL</h1>
      <h3>Luxury in Every Thread</h3>
      <a href="https://www.instagram.com/astyl.2" class="btn">Explore Products</a>
    </div>
  </section>

  <!-- Members Section -->
  <section class="experiences">
    <div class="container">
      <h2>Members of ASTYL</h2>
      <div class="experience-grid">
        <div class="experience-card">
          <a href="https://www.instagram.com/the.atul.mishra"><h4>Atul Mishra</h4></a>
          <p>Founder & Designer</p>
        </div>
        <div class="experience-card">
          <a href="https://www.instagram.com/honeybaba8055"><h4>Sidharth Yadav</h4></a>
          <p>Co-Founder & Manager</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="about">
    <div class="container">
      <h2>Why Choose ASTYL T-Shirts?</h2>
      <p>🌿 100% Pure Cotton – Stay cool and comfy all day long.</p>
      <p>🧥 Effortless Style – Classic fit, soft feel, perfect for everyday wear.</p>
      <p>💸 Just ₹300 – Premium quality at an unbeatable price! 😍</p>
      <p>PLUS: Print-on-Demand! Want to add your own design? Get your custom artwork, logo, or text printed on your tee.</p>
      <p>Your style. Your way. 💯</p>
      <a href="https://www.instagram.com/astyl.2" class="btn">🛒 Grab Yours Now – Only at ASTYL</a>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="testimonials">
    <div class="container">
      <h2>What Our Customers Say</h2>
      <blockquote>
        "ASTYL is my favorite t-shirt brand. Comfort given by ASTYL tees is unforgettable. The price is unbeatable for the quality. Thank you, ASTYL!"
      </blockquote>
      <p>– Happy Customer</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 ASTYL. All rights reserved.</p>
      <h4>Website designed by 𝘼𝙩𝙪𝙡 𝙈𝙞𝙨𝙝𝙧𝙖</h4>
    </div>
  </footer>

</body>
</html>
