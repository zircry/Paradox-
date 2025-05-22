# Paradox-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Paradox | Streetwear Brand</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="hero">
    <div class="hero-content">
      <h1>PARADOX</h1>
      <p>Rebel. Refine. Redefine.</p>
      <a href="#collection" class="btn">Explore Collection</a>
    </div>
  </header>

  <section class="about">
    <h2>Who We Are</h2>
    <p>
      Paradox is a streetwear label born at the crossroads of contradiction: minimal yet bold, raw yet refined. We don't follow trends—we set them.
    </p>
  </section>

  <section id="collection" class="products">
    <h2>Featured Collection</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://source.unsplash.com/400x500/?hoodie,fashion" alt="Paradox Hoodie">
        <h3>VOID Hoodie</h3>
        <p>$68</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/400x500/?jacket,urban" alt="Paradox Jacket">
        <h3>Shadow Jacket</h3>
        <p>$120</p>
      </div>
      <div class="product-card">
        <img src="https://source.unsplash.com/400x500/?tshirt,black" alt="Paradox T-shirt">
        <h3>Core Tee</h3>
        <p>$38</p>
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
  font-family: 'Oswald', sans-serif;
  background-color: #111;
  color: #fff;
  line-height: 1.6;
}

.hero {
  background: url('https://source.unsplash.com/1600x900/?streetwear,dark') no-repeat center center/cover;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
}

.hero::before {
  content: "";
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background-color: rgba(0, 0, 0, 0.7);
}

.hero-content {
  position: relative;
  z-index: 2;
}

.hero h1 {
  font-size: 4rem;
  letter-spacing: 6px;
}

.hero p {
  font-size: 1.2rem;
  color: #bbb;
  margin-top: 1rem;
}

.btn {
  display: inline-block;
  margin-top: 2rem;
  padding: 0.8rem 1.8rem;
  background: #fff;
  color: #000;
  text-decoration: none;
  font-weight: bold;
  transition: all 0.3s;
}

.btn:hover {
  background: #ff0033;
  color: #fff;
}

.about, .products {
  padding: 4rem 2rem;
  max-width: 1000px;
  margin: auto;
  text-align: center;
}

.products h2 {
  margin-bottom: 2rem;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.product-card {
  background: #222;
  padding: 1rem;
  border-radius: 10px;
  transition: transform 0.3s ease;
}

.product-card img {
  width: 100%;
  border-radius: 5px;
}

.product-card:hover {
  transform: scale(1.05);
}

footer {
  background: #000;
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
  margin-top: 3rem;
}
