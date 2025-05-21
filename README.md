
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Style Verve</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f3f3f3;
    }
    header {
      background-color: #2e8b57;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      background-color: #226644;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 12px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #1a4d2e;
    }
    section {
      padding: 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
    }
    .product {
      background-color: white;
      padding: 10px;
      border: 1px solid #ccc;
    }
    footer {
      background-color: #2e8b57;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Style Verve</h1>
  <p>Your fashion, your style.</p>
</header>

<nav>
<a href="#home">Home</a>
  <a href="#products">Products</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <h2>Welcome to Style Verve</h2>
  <p>Discover stylish T-shirts, pants, shirts and more.</p>
</section>

<section id="products">
  <h2>Our Products</h2>
  <div class="products">
    <div class="product">T-Shirt</div>
    <div class="product">Pant</div>
    <div class="product">Shirt</div>
    <div class="product">More Coming Soon</div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>Email: info@styleverve.com</p>
  <p>Phone: +880123456789</p>
</section>

<footer>
  <p>&copy; 2025 Style Verve. All rights reserved.
