
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ay na shoes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    nav {
      background-color: #222;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .intro, .about, .contact {
      text-align: center;
      padding: 2rem 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 2rem;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin-top: 10px;
    }
    .product button {
      margin-top: 10px;
      padding: 10px 15px;
      border: none;
      background-color: #111;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    .product button:hover {
      background-color: #333;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ay na shoes</h1>
    <p>Nashoes — Find Your Perfect Pair</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#shoes">Shoes</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="intro" id="home">
    <h2>Welcome to Ay na shoes</h2>
    <p>From streetwear to sport-ready, we've got the perfect shoes for you.</p>
  </section>

  <section class="products" id="shoes">
    <div class="product">
      <img src="IMG_20250720_022306_858.jpg" alt="Casual Sneaker 1">
      <h3>Casual Sneaker</h3>
      <p>₱1,599</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="IMG_20250720_022304_021.jpg" alt="Running Shoe 1">
      <h3>Running Shoe</h3>
      <p>₱2,299</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="IMG_20250720_022506_553.jpg" alt="Formal Leather 1">
      <h3>Formal Leather Shoe</h3>
      <p>₱2,899</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="IMG_20250720_203915_600.jpg" alt="Mens Nike Initiator">
      <h3>Mens Nike Initiator</h3>
      <p>₱2,499</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Canvas+Shoe+1" alt="Men's Nike Low Retro">
      <h3>Men's Nike Low Retro</h3>
      <p>₱1,299</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Boot+1" alt="Nike Precision 6">
      <h3>Nike Precision 6</h3>
      <p>₱3,199</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Slip-on+1" alt="Nike Ja 1">
      <h3>Nike Ja 1</h3>
      <p>₱999</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Limited+Edition" alt="Limited Edition">
      <h3>Limited Edition</h3>
      <p>₱3,499</p>
      <button>Add to Cart</button>
    </div>
  </section>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p>Ay na shoes was built for sneakerheads and comfort seekers. We combine style, comfort, and value in every pair.</p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@aynashoes.com<br>Instagram: @aynashoes.ph</p>
  </section>

  <footer>
    &copy; 2025 Ay na Shoes. All rights reserved.
  </footer>

</body>
</html>
