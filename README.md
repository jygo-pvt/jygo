<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Explore premium cosmetics at Jygo Cosmetics, Kathmandu, Nepal. Discover top-quality skincare, makeup, and accessories.">
  <title>Jygo Cosmetics | Your Trusted Beauty Destination</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700&family=Playfair+Display&display=swap">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #ffffff;
      padding: 20px;
      text-align: center;
      border-bottom: 3px solid #f2b8c6;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      color: #111;
    }
    nav {
      background: #ffffff;
      padding: 10px 20px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav ul {
      list-style: none;
      display: flex;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: #111;
      font-weight: 500;
    }
    .search-bar {
      flex-grow: 1;
      margin: 0 20px;
    }
    .search-bar input[type="text"] {
      width: 100%;
      padding: 8px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    .auth-links {
      display: flex;
      align-items: center;
    }
    .auth-links a {
      margin-left: 15px;
      color: #b45f7c;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
    .hero h2 {
      font-size: 3rem;
    }
    .promo-banner {
      background: #ffd1dc;
      text-align: center;
      padding: 15px;
      font-weight: bold;
      color: #b45f7c;
    }
    .products-section {
      padding: 40px 20px;
      background: #ffffff;
    }
    .products-section h3 {
      text-align: center;
      margin-bottom: 30px;
      color: #b45f7c;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s;
    }
    .product-card:hover {
      transform: translateY(-5px);
    }
    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product-details {
      padding: 15px;
    }
    .product-details h4 {
      font-family: 'Playfair Display', serif;
      color: #b45f7c;
      margin-bottom: 10px;
    }
    .add-to-cart-btn {
      background: #ff6f61;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 4px;
      display: block;
      margin-top: 10px;
      text-align: center;
      transition: background 0.3s;
    }
    .add-to-cart-btn:hover {
      background: #ff3e1d;
    }
    .about-section, .contact-section {
      padding: 40px 20px;
      background-color: #fefefe;
    }
    .about-section h3, .contact-section h3 {
      text-align: center;
      margin-bottom: 30px;
      color: #b45f7c;
    }
    .faq-section {
      padding: 40px 20px;
    }
    .faq-section h3 {
      text-align: center;
      margin-bottom: 20px;
    }
    .faq-item {
      margin: 10px 0;
      background: #f9f9f9;
      padding: 15px;
      border-radius: 4px;
    }
    .contact-form {
      max-width: 600px;
      margin: 0 auto;
    }
    .contact-form label {
      display: block;
      margin-top: 10px;
      font-weight: 600;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    .footer {
      background: #111;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    .footer a {
      color: #fce7f3;
      text-decoration: none;
    }
    .social-links {
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    .social-links a {
      color: #ffd1dc;
      margin: 0 10px;
      text-decoration: none;
      font-size: 1.2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jygo Cosmetics</h1>
    <p>Your Trusted Beauty Destination in Kathmandu, Nepal</p>
  </header>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#products">Products</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#faq">FAQs</a></li>
    </ul>
    <div class="search-bar">
      <input type="text" placeholder="Search products...">
    </div>
    <div class="auth-links">
      <a href="#">Sign In</a>
      <a href="#">Sign Up</a>
    </div>
  </nav>

  <div class="promo-banner">
    <p>Special Offer: Get 20% off your first purchase!</p>
  </div>

  <section class="hero">
    <h2>Discover Beauty, Discover You</h2>
  </section>

  <section class="about-section" id="about">
    <h3>About Us</h3>
    <div class="about-content">
      <p>Jygo Cosmetics is your one-stop destination for premium cosmetics and beauty products in Kathmandu, Nepal. We pride ourselves on delivering top-quality skincare, makeup, and accessories sourced from trusted brands worldwide.</p>
      <p>Our mission is to enhance your beauty journey by offering products that cater to every skin type and concern. Discover the world of beauty with us.</p>
    </div>
  </section>

  <section class="products-section" id="products">
    <h3>Our Products</h3>
    <div class="products-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/300" alt="COSRX Low pH Cleanser">
        <div class="product-details">
          <h4>COSRX Low pH Good Morning Gel Cleanser</h4>
          <p>A gentle cleanser for fresh, balanced skin.</p>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/300" alt="Innisfree Cleanser">
        <div class="product-details">
          <h4>Innisfree Green Tea Foam Cleanser</h4>
          <p>Deep cleansing with Jeju green tea extracts.</p>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/300" alt="Skinfood Black Sugar Mask">
        <div class="product-details">
          <h4>Skinfood Black Sugar Mask Wash Off</h4>
          <p>Exfoliates and nourishes dull skin.</p>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/300" alt="Laneige Cream Skin Refiner">
        <div class="product-details">
          <h4>Laneige Cream Skin Refiner</h4>
          <p>Provides deep hydration and strengthens the skin barrier.</p>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/300" alt="Missha First Treatment Essence">
        <div class="product-details">
          <h4>Missha First Treatment Essence</h4>
          <p>Enhances skin’s clarity and texture.</p>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
    </div>
  </section>

  <section class="faq-section" id="faq">
    <h3>Frequently Asked Questions</h3>
    <div class="faq-item">
      <strong>What payment methods do you accept?</strong>
      <p>We accept credit cards, mobile payments, and cash on delivery.</p>
    </div>
    <div class="faq-item">
      <strong>How long does shipping take?</strong>
      <p>Shipping typically takes 3-5 business days within Nepal.</p>
    </div>
  </section>

  <section class="contact-section" id="contact">
    <h3>Contact Us</h3>
    <div class="contact-form">
      <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" style="background: #b45f7c; color: white; padding: 10px 20px; border: none; border-radius: 4px; cursor: pointer;">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="footer">
    <p>Contact us: 9708838007 | <a href="mailto:jygo.pvt@gmail.com">jygo.pvt@gmail.com</a></p>
    <div class="social-links">
      <a href="#">Instagram</a>
      <a href="#">Facebook</a>
      <a href="#">Twitter</a>
    </div>
    <p>&copy; 2025 Jygo Cosmetics. All rights reserved.</p>
  </footer>
</body>
</html>

