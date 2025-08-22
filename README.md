# Examen-HTML-CSS-AOUT-2025
EXAMEN HTML CSS AOUT 2025
📝 Épreuve Pratique – Module HTML/CSS
Sujet :

Conception d’un mini site web vitrine en HTML5 et CSS3 pour un commerce local sénégalais

Contexte :

Tu es chargé de créer un petit site vitrine pour un commerce sénégalais qui souhaite améliorer sa visibilité en ligne.
Le site doit être simple, responsive, esthétique et codé uniquement avec HTML5 et CSS3 (sans Bootstrap ni JavaScript).

1. Structure du projet (HTML uniquement)

Le site doit contenir 3 pages obligatoires :

index.html (Accueil)

Un header avec le logo du commerce et une barre de navigation (Accueil | Produits | Contact).

Une section Hero avec une grande image représentative du commerce et un slogan.

Une section "À propos" présentant l’histoire du commerce (texte + image).

Une section Produits/Services avec au moins 6 produits affichés sous forme de cartes (image, nom, prix).

Un footer avec adresse, téléphone, et réseaux sociaux.

produits.html (Produits/Services)

Une liste de 8 à 10 produits ou services affichés en grille CSS (flex ou grid).

Chaque produit contient une image, un titre et un prix en FCFA.

contact.html (Contact)

Un formulaire contenant les champs : Nom, Email, Téléphone, Message.

Un lien cliquable "📞 Appeler" qui ouvre directement le téléphone :

<a href="tel:+221781234567">Appeler le commerce</a>

2. Styles CSS (style.css obligatoire)

Utiliser un fichier style.css externe.

Créer une palette de couleurs inspirée du drapeau sénégalais :

:root {
  --yellow: #FFDE00;
  --green: #00853F;
  --red: #CE1126;
}


Définir une classe personnalisée de bouton :

.btn-senegal {
  background-color: var(--green);
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}
.btn-senegal:hover {
  background-color: var(--red);
}


Rendre le site responsive (mobile-first) :

Menu en colonne sur mobile.

Grille des produits adaptée en 1 colonne sur mobile, 2 sur tablette, 3 sur desktop.

Optimiser les images (taille max 200KB).

3. Contraintes & Attentes

Respect de la sémantique HTML5 (<header>, <section>, <article>, <footer>).

Code clair et bien indenté.

Pas d’utilisation de frameworks (ni Bootstrap, ni Tailwind, ni JS).

Ajouter au moins 1 phrase en wolof dans le site (ex: "Nio faral ak seen bopp" – "Faisons confiance à nous-mêmes").

4. Critères d’Évaluation
Points	Détails
40%	Structure HTML bien organisée (pages, sections, liens fonctionnels)
30%	CSS personnalisé et responsive
15%	Originalité et design inspiré du Sénégal
15%	Propreté du code (indentation, commentaires, cohérence)
5. Rendu Final attendu

Un dossier compressé contenant :

index.html, produits.html, contact.html

style.css

Un dossier images/ contenant les visuels optimisés.

Un fichier README.md indiquant :

Nom du commerce choisi

Capture d’écran de la page d’accueil

(Bonus) Lien de déploiement (GitHub Pages, Netlify).

👉 Objectif : Créer un site simple mais professionnel, 100% HTML & CSS, utile aux commerces locaux.
