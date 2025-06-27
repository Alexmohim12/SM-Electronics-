<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SM Electronics</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
    }
    header {
      background-color: #1e1e1e;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #333;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .hero {
      background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      text-shadow: 1px 1px 4px black;
    }
    .content {
      padding: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .footer {
      background: #1e1e1e;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>SM Electronics</h1>
    <p>Your Trusted Electronics Shop</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    Welcome to SM Electronics
  </section>

  <section class="content" id="products">
    <h2>Our Products</h2>
    <div class="product">Smartphone - Model X100</div>
    <div class="product">LED TV - 42 inch HD</div>
    <div class="product">Bluetooth Speakers - Crystal Sound</div>
    <!-- Add more product blocks as needed -->
  </section>

  <section class="content" id="about">
    <h2>About Us</h2>
    <p>SM Electronics is a top-rated shop offering quality gadgets, electronics, and accessories at unbeatable prices. Our mission is to provide the best customer service and top-notch electronics to our valued customers.</p>
  </section>

  <section class="content" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@smelectronics.com</p>
    <p>Phone: +880 1234-567890</p>
    <p>Location: Dhaka, Bangladesh</p>
  </section>

  <div class="footer">
    &copy; 2025 SM Electronics. All rights reserved.
  </div>
</body>
</html>
