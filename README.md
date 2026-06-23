<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Martin Le Ruen - Profile</title>
  <meta name="description" content="Page de profil de Martin Le Ruen pour le cours Développement Front-End.">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    
    <!-- Carte 1 : Présentation -->
    <div class="card-white">
      <h1>Hello, I'm Martin 😎</h1>
      <img src="ma-photo.jpg" alt="Martin Le Ruen" class="img-circle">
      <p>
        Actuellement étudiant en Master à l'IÉSEG School of Management, j'évolue dans le secteur du marketing digital et du e-commerce chez Lacoste. J'apprends le développement web pour maîtriser les aspects techniques de l'animation de sites et optimiser l'expérience utilisateur !
      </p>
      <a href="https://www.lewagon.com" target="_blank" class="btn-purple">Discover Le Wagon</a>
    </div>

    <!-- Carte 2 : Expérience -->
    <div class="card-white">
      <h2>E-commerce & Digital Marketing 🚀</h2>
      <p>
        Au sein des équipes e-commerce, je participe activement à la gestion du catalogue en ligne, à l'optimisation des pages de listes de produits (PLP) et au déploiement des campagnes d'animation commerciale.
      </p>
    </div>

    <!-- Carte 3 : Recherche -->
    <div class="card-white">
      <h2>Master's Thesis 📚</h2>
      <p>
        Auteur d'un travail de recherche appliqué sur l'adaptation de l'animation e-commerce aux spécificités des marchés européens, tout en garantissant une image de marque cohérente.
      </p>
    </div>

    <!-- Carte 4 : Passions -->
    <div class="card-white">
      <h2>Sports & Hobbies 🏃‍♂️🎾</h2>
      <p>
        Grand passionné de tennis, je suis de très près les tournois du Grand Chelem comme Roland-Garros et Wimbledon. Côté terrain, j'aime le dépassement de soi et je m'entraîne pour des courses de 10km.
      </p>
    </div>

    <!-- Carte 5 : Réseaux -->
    <div class="card-white">
      <h2>Follow me</h2>
      <ul class="list-vertical">
        <li>
          <a href="https://github.com/Martin-Le-Ruen" target="_blank">
            <i class="fab fa-github"></i> GitHub
          </a>
        </li>
        <li>
          <a href="https://linkedin.com/" target="_blank">
            <i class="fab fa-linkedin-in"></i> LinkedIn
          </a>
        </li>
      </ul>
    </div>

  </div>

</body>
</html>
body {
  background-color: #F4F6F9;
  color: rgb(45, 45, 45);
  font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 1.7;
  margin: 0;
  padding: 0;
}

h1 {
  font-size: 34px;
  font-weight: 700;
  color: #111111;
  margin-top: 10px;
  margin-bottom: 20px;
}

h2 {
  font-size: 22px;
  font-weight: 600;
  color: #1A1A1A;
  margin-bottom: 12px;
}

p {
  color: rgb(90, 90, 90);
  font-size: 15.5px;
  margin-bottom: 25px;
}

.container {
  width: 600px;
  margin: 50px auto;
  padding: 0 15px;
}

.card-white {
  background: #FFFFFF;
  padding: 40px;
  border-radius: 8px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
  margin-bottom: 25px;
  text-align: center;
}

.img-circle {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
}

.btn-purple {
  display: inline-block;
  background-color: #5D5FEF;
  color: #FFFFFF;
  padding: 14px 28px;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.3s ease;
}

.btn-purple:hover {
  background-color: #4B4DDC;
  color: #FFFFFF;
}

.list-vertical {
  list-style: none;
  padding-left: 0;
  margin: 20px 0 0 0;
}

.list-vertical li {
  margin: 14px 0;
}

.list-vertical a {
  color: #5D5FEF;
  text-decoration: none;
  font-size: 17px;
  font-weight: 500;
}

.list-vertical a:hover {
  color: #4B4DDC;
  text-decoration: underline;
}

.list-vertical i {
  margin-right: 10px;
  font-size: 19px;
}
