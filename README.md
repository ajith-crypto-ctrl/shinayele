# shinayele
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shinayele Studio Sale</title>
  <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
  <header class="navbar">
    <h1>Shinayele</h1>
    <nav><a href="shop.html">Shop</a></nav>
  </header>

  <section class="hero">
    <img src="images/hero-gown.jpg" alt="Shinayele designer gown" />
    <div class="hero-text">
      <h2>Curated Designer Fusion • Up to 70% Off</h2>
      <p>Pop‑up now live – shop the clearance collection</p>
      <a href="shop.html" class="btn">Shop Now</a>
    </div>
  </section>

  <footer>
    © 2025 Shinayele • Follow @shinayele_official
  </footer>
  
  <script src="js/main.js"></script>
</body>
</html>
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shinayele Shop</title>
  <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
  <header class="navbar">
    <h1>Shinayele</h1>
    <nav><a href="index.html">Home</a></nav>
  </header>

  <main>
    <section class="product-grid">
      <div class="product-card">
        <img src="images/product1.jpg" alt="Product 1" />
        <h3>Embroidered Lehenga</h3>
        <p>₹3,000 <span class="original">₹6,000</span></p>
        <button class="add-to-cart">+ Cart</button>
      </div>
      <!-- repeat product-card for each item -->
    </section>
  </main>

  <footer>
    © 2025 Shinayele • Follow @shinayele_official
  </footer>

  <script src="js/main.js"></script>
</body>
</html>
:root {
  --cream: #f7f5f0;
  --taupe: #c1b7aa;
  --charcoal: #333;
  --gold: #d4af37;
}

* { box-sizing: border-box; margin: 0; padding: 0; }
body {
  :contentReference[oaicite:1]{index=1}
  :contentReference[oaicite:2]{index=2}
  :contentReference[oaicite:3]{index=3}
}
.navbar {
  :contentReference[oaicite:4]{index=4}
  :contentReference[oaicite:5]{index=5}
}
.navbar a {
  :contentReference[oaicite:6]{index=6}
  :contentReference[oaicite:7]{index=7}
}
:contentReference[oaicite:8]{index=8}
.hero img {
  :contentReference[oaicite:9]{index=9}
}
.hero-text {
  :contentReference[oaicite:10]{index=10}
  :contentReference[oaicite:11]{index=11}
}
.btn {
  :contentReference[oaicite:12]{index=12}
  :contentReference[oaicite:13]{index=13}
  :contentReference[oaicite:14]{index=14}
  :contentReference[oaicite:15]{index=15}
}
.product-grid {
  display: grid;
  :contentReference[oaicite:16]{index=16}
  :contentReference[oaicite:17]{index=17}
}
.product-card {
  background: white;
  padding: 1rem;
  :contentReference[oaicite:18]{index=18}
  :contentReference[oaicite:19]{index=19}
}
:contentReference[oaicite:20]{index=20}
  :contentReference[oaicite:21]{index=21}
}
:contentReference[oaicite:22]{index=22}
  :contentReference[oaicite:23]{index=23}
}
:contentReference[oaicite:24]{index=24}
  :contentReference[oaicite:25]{index=25}
  :contentReference[oaicite:26]{index=26}
  :contentReference[oaicite:27]{index=27}
  cursor: pointer;
}
footer {
  :contentReference[oaicite:28]{index=28}
  :contentReference[oaicite:29]{index=29}
}
document.addEventListener('DOMContentLoaded', () => {
  document.querySelectorAll('.add-to-cart').forEach(btn => {
    btn.addEventListener('click', () => {
      alert('Added to cart!');
    });
  });
});
