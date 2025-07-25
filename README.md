<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Boutique Velraj</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      direction: ltr;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #111;
      color: #fff;
      padding: 1rem 2rem;
    }

    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      padding: 0;
      margin: 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffd700;
    }

    #products {
      padding: 2rem;
      text-align: center;
    }

    #products h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #111;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .product-card {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      padding: 1rem;
      transition: transform 0.3s ease;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    .product-card h3 {
      margin-top: 1rem;
      font-size: 1.2rem;
      color: #222;
    }

    .product-card p {
      font-size: 0.95rem;
      color: #666;
      margin: 0.5rem 0 1rem;
    }

    .btn {
      display: inline-block;
      background-color: #111;
      color: #fff;
      padding: 0.5rem 1.2rem;
      border-radius: 6px;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #333;
    }

    footer {
      background-color: #111;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .container {
        flex-direction: column;
        text-align: center;
      }

      nav ul {
        flex-direction: column;
        gap: 1rem;
        margin-top: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- En-tête -->
  <header>
    <div class="container">
      <div class="logo">Velraj Boutique</div>
      <nav>
        <ul>
          <li><a href="#home">Accueil</a></li>
          <li><a href="#products">Produits</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Produits -->
  <section id="products">
    <h2>Nos Produits</h2>
    <div class="product-grid">
      <!-- Produit 1 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/400x400.png?text=T-shirt+Blanc" alt="T-shirt blanc">
        <h3>T-shirt Blanc Classique</h3>
        <p>100% coton, coupe oversize légère idéale pour l'été.</p>
        <a href="#" class="btn">Acheter</a>
      </div>

      <!-- Produit 2 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/400x400.png?text=Polo+Noir" alt="Polo noir">
        <h3>Polo Noir Moderne</h3>
        <p>Mix coton & élasthanne, design élégant et confortable.</p>
        <a href="#" class="btn">Acheter</a>
      </div>

      <!-- Produit 3 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/400x400.png?text=Jean+Slim" alt="Jean slim">
        <h3>Jean Bleu Slim Fit</h3>
        <p>Tissu stretch pour un confort optimal au quotidien.</p>
        <a href="#" class="btn">Acheter</a>
      </div>

      <!-- Produit 4 -->
      <div class="product-card">
        <img src="https://via.placeholder.com/400x400.png?text=Veste+d'hiver" alt="Veste hiver">
        <h3>Veste Hiver Matelassée</h3>
        <p>Chaude, imperméable et équipée d’une capuche amovible.</p>
        <a href="#" class="btn">Acheter</a>
      </div>
    </div>
  </section>

  <!-- Pied de page -->
  <footer id="contact">
    <p>© 2025 Velraj. Tous droits réservés.</p>
  </footer>

</body>
</html>
