# G-K-IMMOBILIER-<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>G-K IMMOBILIER - Travail - Honnêteté - Professionnalisme</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    background: #f9f9f9;
    color: #333;
  }
  header {
    background: #004aad;
    color: white;
    padding: 20px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  header h1 {
    margin: 0;
    font-size: 1.8rem;
    letter-spacing: 2px;
  }
  nav a {
    color: white;
    margin-left: 25px;
    text-decoration: none;
    font-weight: 600;
  }
  nav a:hover {
    text-decoration: underline;
  }
  .hero {
    background: url('https://images.unsplash.com/photo-1560184897-6d05a80b2451?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
    height: 400px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-shadow: 0 0 10px rgba(0,0,0,0.7);
    text-align: center;
    padding: 0 20px;
  }
  .hero h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
  }
  .hero p {
    font-size: 1.2rem;
    max-width: 600px;
  }
  main {
    max-width: 1000px;
    margin: 40px auto;
    padding: 0 20px;
  }
  section {
    margin-bottom: 60px;
  }
  section h3 {
    font-size: 1.8rem;
    color: #004aad;
    border-bottom: 3px solid #004aad;
    padding-bottom: 8px;
    margin-bottom: 20px;
  }
  .services-list, .contact-info {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }
  .service-item {
    flex: 1 1 300px;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 8px rgba(0,0,0,0.1);
  }
  footer {
    background: #004aad;
    color: white;
    text-align: center;
    padding: 15px 10px;
  }
  @media(max-width: 600px) {
    header {
      flex-direction: column;
      align-items: flex-start;
    }
    nav {
      margin-top: 10px;
    }
    .hero {
      height: 300px;
    }
    .hero h2 {
      font-size: 1.8rem;
    }
  }
</style>
</head>
<body>

<header>
  <h1>G-K IMMOBILIER</h1>
  <nav>
    <a href="#apropos">À propos</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Travail - Honnêteté - Professionnalisme</h2>
  <p>Votre partenaire de confiance pour la vente et la location de biens immobiliers au Cameroun.</p>
</section>

<main>
  <section id="apropos">
    <h3>À propos de G-K IMMOBILIER</h3>
    <p>G-K IMMOBILIER est une société spécialisée dans la vente, l’achat et la location de biens immobiliers, avec un engagement fort sur la transparence et la qualité du service. Notre mission est d'accompagner nos clients dans toutes leurs démarches immobilières avec sérieux et professionnalisme.</p>
  </section>

  <section id="services">
    <h3>Nos Services</h3>
    <div class="services-list">
      <div class="service-item">
        <h4>Vente de biens</h4>
        <p>Maisons, appartements, terrains titrés. Nous vous aidons à trouver le bien qui correspond à vos attentes.</p>
      </div>
      <div class="service-item">
        <h4>Location</h4>
        <p>Studios, appartements meublés ou non, maisons à louer, avec des offres adaptées à tous les budgets.</p>
      </div>
      <div class="service-item">
        <h4>Conseils immobiliers</h4>
        <p>Accompagnement personnalisé pour vos projets d’achat ou d’investissement immobilier.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h3>Contactez-nous</h3>
    <p>Téléphone : <a href="tel:+237696353487">+237 696 353 487</a></p>
    <p>Email : <a href="mailto:contact@gkimmobilier.com">contact@gkimmobilier.com</a></p>
    <p>Adresse : Douala, Cameroun</p>
  </section>
</main>

<footer>
  &copy; 2025 G-K IMMOBILIER - Tous droits réservés
</footer>

</body>
</html>
