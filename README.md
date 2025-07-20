
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sole Squad Shoes</title>
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
    <h1>Sole Squad</h1>
    <p>Step in Style — Find Your Perfect Pair</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#shoes">Shoes</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="intro" id="home">
    <h2>Welcome to Sole Squad</h2>
    <p>From streetwear to sport-ready, we've got the perfect shoes for you.</p>
  </section>

  <section class="products" id="shoes">
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Casual+Sneaker+1" alt="Casual Sneaker 1">
      <h3>Casual Sneaker</h3>
      <p>₱1,599</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Running+Shoe+1" alt="Running Shoe 1">
      <h3>Running Shoe</h3>
      <p>₱2,299</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Formal+Leather+1" alt="Formal Leather 1">
      <h3>Formal Leather Shoe</h3>
      <p>₱2,899</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Trainer+1" alt="Trainer 1">
      <h3>Trainer</h3>
      <p>₱2,499</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Canvas+Shoe+1" alt="Canvas Shoe 1">
      <h3>Canvas Shoe</h3>
      <p>₱1,299</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Boot+1" alt="Boot 1">
      <h3>Urban Boot</h3>
      <p>₱3,199</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200?text=Slip-on+1" alt="Slip-on 1">
      <h3>Slip-on Comfort</h3>
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
    <p>Sole Squad was built for sneakerheads and comfort seekers. We combine style, comfort, and value in every pair.</p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@solesquad.com<br>Instagram: @solesquad.ph</p>
  </section>

  <footer>
    &copy; 2025 Sole Squad Shoes. All rights reserved.
  </footer>

</body>
</html>
