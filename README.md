# Chinni
Welcome to Chinni Digital
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chinni Digital Studio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #002244;
    }
    header {
      background-color: #0055aa;
      color: white;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 24px;
      font-weight: bold;
    }
    .login {
      background-color: white;
      color: #0055aa;
      padding: 6px 12px;
      border-radius: 5px;
      cursor: pointer;
    }
    .banner {
      background-color: #e6f0ff;
      text-align: center;
      padding: 30px 10px;
    }
    .banner h1 {
      margin: 0;
      font-size: 32px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      margin: 0;
    }
    footer {
      background-color: #0055aa;
      color: white;
      text-align: center;
      padding: 15px 10px;
      margin-top: 30px;
    }
    .contact a {
      color: #ffffff;
      text-decoration: underline;
    }
    /* Modal */
    .modal {
      display: none;
      position: fixed;
      z-index: 999;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: rgba(0, 0, 0, 0.5);
    }
    .modal-content {
      background-color: #fff;
      margin: 15% auto;
      padding: 20px;
      border-radius: 8px;
      width: 90%;
      max-width: 400px;
    }
    .modal-content h2 {
      margin-top: 0;
    }
    .modal-content input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .modal-content button {
      background-color: #0055aa;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      cursor: pointer;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Chinni Digital Studio</div>
    <div class="login" onclick="openModal()">Login</div>
  </header>  <section class="banner">
    <h1>Flat 50% Off on All Photo Frames!</h1>
    <p>Explore Wooden, Acrylic, Collage & Custom Designs</p>
  </section>  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/220x180.png?text=Wooden+Frame" alt="Wooden Frame">
      <h3>Wooden Frame</h3>
      <p>₹599 <del>₹999</del></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/220x180.png?text=Acrylic+Frame" alt="Acrylic Frame">
      <h3>Acrylic Gloss Frame</h3>
      <p>₹899 <del>₹1,499</del></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/220x180.png?text=Collage+Set" alt="Collage Set">
      <h3>Collage Wall Set</h3>
      <p>₹1,299 <del>₹1,999</del></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/220x180.png?text=Custom+Frame" alt="Custom Frame">
      <h3>Custom Name Frame</h3>
      <p>₹1,499 <del>₹1,899</del></p>
    </div>
  </section>  <footer>
    <p>Contact: 9121174999 | 9440150947</p>
    <p>
      <a href="https://wa.me/9440150947">Chat on WhatsApp</a> |
      <a href="https://youtube.com/@126chinnidigitalstudio?feature=shared">YouTube</a> |
      <a href="https://photos.app.goo.gl/orPRzpunQnbackYb8">Gallery</a> |
      <a href="https://maps.app.goo.gl/m1PJustoXnhbGnxB6">Map</a>
    </p>
    <p>&copy; 2025 Chinni Digital Studio</p>
  </footer>  <!-- Login Modal -->  <div id="loginModal" class="modal">
    <div class="modal-content">
      <h2>Login</h2>
      <input type="text" placeholder="Enter Mobile Number">
      <input type="password" placeholder="Enter Password">
      <button onclick="closeModal()">Login</button>
    </div>
  </div>  <script>
    function openModal() {
      document.getElementById('loginModal').style.display = 'block';
    }
    function closeModal() {
      document.getElementById('loginModal').style.display = 'none';
      alert('Login Successful! Welcome to Chinni Digital Studio.');
    }
    window.onclick = function(event) {
      const modal = document.getElementById('loginModal');
      if (event.target == modal) {
        modal.style.display = 'none';
      }
    }
  </script></body>
</html>
