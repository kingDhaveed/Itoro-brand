<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Itoro Brand - Home</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
    }
a{ 
  text-decoration: none;
}
    body {
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background: #000;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 36px;
      font-style: italic;
    }

    nav {
      background: #e91e63;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('itoro-hero.jpg') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px black;
      text-align: center;
      padding: 20px;
    }

    .hero h2 {
      font-size: 40px;
    }

    .section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .section h2 {
      margin-bottom: 20px;
      font-size: 28px;
      color: #e91e63;
      text-align: center;
    }

    .about p, .contact p {
      line-height: 1.6;
      font-size: 18px;
      text-align: center;
    }

    .cta {
      text-align: center;
      margin-top: 30px;
    }

    .cta a {
      background: #e91e63;
      color: white;
      padding: 15px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-size: 18px;
      display: inline-block;
    }

    .contact-icons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    .contact-icons a img {
      width: 40px;
      height: 40px;
      transition: transform 0.2s ease;
    }

    .contact-icons a img:hover {
      transform: scale(1.1);
    }

    footer {
      background: #222;
      color: #aaa;
      padding: 20px;
      text-align: center;
      font-size: 14px;
    }

    @media(max-width: 600px) {
      .hero h2 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>The Itoro Brand</h1>
  </header>

  <nav>
    <a href="about.html">About</a>
    <a href="order.html">Shop</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Elegance. Culture. Identity.<br>Itoro Designs for the Bold</h2>
  </section>

  <section class="about section">
    <h2>About the Brand</h2>
    <p>
      The Itoro Brand was born out of passion for originality and the elegance of African fashion.
      From humble beginnings, Itoro has grown into a creative force delivering premium designs, 
      especially in cultural fusions, luxury wear, and street fashion.
    </p>
    <div class="cta">
      <a href="about.html">Learn More About Us</a>
    </div>
  </section>

  <section class="section">
    <h2>Explore Our Latest Products</h2>
    <p style="text-align:center;">
      Whether you're into contemporary streetwear or elegant cultural blends,
      our latest collections are crafted just for you.
    </p>
    <div class="cta">
      <a href="order.html">Visit Shop</a>
    </div>
  </section>

  <section id="contact" class="contact section">
    <h2>Contact Us</h2>
    <p>Phone: <a href="tel:+2349054946835">+2348113005007, +234 812 766 2330 </a></p>
    <p>Email: itorobrandofficial@gmail.com</p>
    <p>Follow and message us on social media:</p>
    <div class="contact-icons">
      <a href="https://instagram.com/itorobrandofficial" target="_blank">
        <img src="instagram.jpeg" alt="Instagram">
      </a>
      <a href="https://wa.me/2349054946835" target="_blank">
        <img src="whatsapp.jpeg" alt="WhatsApp">
      </a>
      <a href="https://facebook.com/itorobrandofficial" target="_blank">
        <img src="facebook.jpeg" alt="Facebook">
      </a>
      <a href="https://tiktok.com/@itorobrandofficial" target="_blank">
        <img src="tiktok.png" alt="TikTok">
      </a>
    </div>
  </section>

  <footer>
    &copy; 2025 The Itoro Brand. All rights reserved.
  </footer>

</body>
</html>