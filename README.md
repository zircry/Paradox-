# Paradox-
sensational 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Paradox | Clothing Brand</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="hero">
    <div class="overlay">
      <h1>PARADOX</h1>
      <p>Where Street Meets Minimal</p>
      <a href="#shop" class="btn">Shop Now</a>
    </div>
  </header>

  <section id="about" class="section">
    <h2>About Paradox</h2>
    <p>Paradox is a bold fusion of urban edge and minimalist fashion. Each piece tells a story—crafted for those who challenge norms and live uniquely.</p>
  </section>

  <section id="shop" class="section products">
    <h2>Featured Drops</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1600180758890-b5aa098c7322?auto=format&fit=crop&w=600&q=80" alt="Paradox Hoodie" />
        <h3>Oversized Hoodie</h3>
        <p>$65</p>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1520975918108-b0d4c1ecb6cc?auto=format&fit=crop&w=600&q=80" alt="Paradox Jacket" />
        <h3>Techwear Jacket</h3>
        <p>$120</p>
      </div>
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1602810318592-cb2a1e3e6cf1?auto=format&fit=crop&w=600&q=80" alt="Paradox Tee" />
        <h3>Graphic Tee</h3>
        <p>$35</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Paradox. All rights reserved.</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  line-height: 1.6;
  background-color: #111;
  color: #fff;
}

.hero {
  background: url('https://images.unsplash.com/photo-1521336575822-6da63fb45455?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.hero .overlay {
  background-color: rgba(0, 0, 0, 0.6);
  padding: 2rem;
  text-align: center;
}

.hero h1 {
  font-size: 4rem;
  letter-spacing: 4px;
}

.hero p {
  margin: 1rem 0;
  font-size: 1.2rem;
  color: #ccc;
}

.btn {
  background: #fff;
  color: #000;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s;
}

.btn:hover {
  background: #ff0055;
  color: #fff;
}

.section {
  padding: 4rem 2rem;
  text-align: center;
}

.products .product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.product-card {
  background: #222;
  padding: 1rem;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.product-card img {
  max-width: 100%;
  border-radius: 5px;
  height: auto;
}

.product-card:hover {
  transform: scale(1.05);
}

footer {
  background: #000;
  text-align: center;
  padding: 1rem 0;
  font-size: 0.9rem;
}
