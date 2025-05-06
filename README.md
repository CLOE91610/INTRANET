# INTRANET
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Intranet ABH</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f7f7f7;
    }

    header {
      background-color: #001f3f;
      color: white;
      padding: 20px 40px;
      font-size: 24px;
      font-weight: 700;
    }

    .container {
      display: flex;
      height: 100vh;
    }

    nav {
      width: 250px;
      background-color: #ffffff;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.1);
    }

    nav a {
      display: block;
      margin: 15px 0;
      color: #001f3f;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      flex: 1;
      padding: 40px;
      overflow-y: auto;
    }

    .card {
      background-color: white;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }

    .card h2 {
      margin-top: 0;
      color: #001f3f;
    }

    .card p {
      font-size: 15px;
      color: #333;
    }
  </style>
</head>
<body>
  <header>Bienvenue sur l'intranet ABH</header>

  <div class="container">
    <nav>
      <a href="#">Accueil</a>
      <a href="#">Actualités</a>
      <a href="#">Documents</a>
      <a href="#">Contacts</a>
      <a href="#">Liens utiles</a>
    </nav>

    <main>
      <div class="card">
        <h2>Actualité : Nouvelle salle de sport</h2>
        <p>La salle de sport est maintenant ouverte à tous les collaborateurs. Horaires disponibles sur l’affichage interne.</p>
      </div>

      <div class="card">
        <h2>Document à lire</h2>
        <p>Le nouveau guide d’intégration est disponible dans la section Documents. Merci de le lire avant fin du mois.</p>
      </div>

      <div class="card">
        <h2>Mot de la direction</h2>
        <p>Merci à toutes les équipes pour leur implication dans les derniers projets. Les résultats sont très encourageants.</p>
      </div>
    </main>
  </div>
</body>
</html>
