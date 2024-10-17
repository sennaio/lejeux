Compteur d'Argent avec Multiplicateur, Auto-Clicker, Reset et Tableau des Scores
Description
Ce projet est un mini-jeu en HTML, CSS et JavaScript qui simule un système de clic pour accumuler de l'argent. Au fur et à mesure que l'utilisateur clique, il peut acheter des multiplicateurs et des auto-clickers pour augmenter la rapidité des gains. Une fois que le compteur atteint un certain seuil, l'utilisateur peut réinitialiser le jeu tout en enregistrant son score précédent dans un tableau des meilleurs scores.

Fonctionnalités
Compteur manuel : Ajoutez 1$ à chaque clic.
Multiplicateurs : Achetez des multiplicateurs pour augmenter les gains par clic.
Auto-clickers : Automatisez les clics à un certain rythme.
Reset : Réinitialisez le jeu une fois que vous avez atteint un million de dollars, tout en enregistrant votre score.
Tableau des scores : Affiche les meilleurs scores après chaque reset.
Son spécial : Un son est joué lorsque vous atteignez 1 000 000$.
Fichiers du projet
index.html : Contient le code HTML pour l'interface du jeu.
style.css (optionnel) : Contient les styles CSS pour la présentation du jeu (si séparé du fichier HTML).
README.md : Documentation du projet (ce fichier).
Démo du Jeu
Voici un aperçu des éléments visuels dans le jeu :

Un grand compteur affichant l'argent accumulé.
Des boutons pour augmenter manuellement la somme d'argent, acheter des multiplicateurs ou des auto-clickers.
Un bouton "Reset" qui se débloque une fois que le joueur atteint 1 000 000$.
Un tableau des scores en bas à droite, qui affiche les scores les plus élevés après chaque reset.
Instructions pour Exécuter le Projet
1. Télécharger ou Cloner le Projet
Téléchargez le projet ou clonez-le depuis votre dépôt GitHub (si disponible) :

bash
Copier le code
git clone https://github.com/votre-utilisateur/votre-repository.git
2. Ouvrir le Fichier
Une fois téléchargé, ouvrez simplement le fichier index.html dans votre navigateur Web.

3. Jouer au Jeu
Cliquez sur le bouton "+1$" pour commencer à accumuler de l'argent.
Une fois que vous avez suffisamment d'argent, des boutons supplémentaires apparaîtront pour acheter des multiplicateurs et des auto-clickers.
Continuez à accumuler de l'argent jusqu'à ce que vous puissiez réinitialiser le jeu (reset), tout en conservant votre score dans le tableau des meilleurs scores.
Personnalisation
Modifier les Prix des Multiplicateurs et Auto-Clickers
Dans le fichier index.html, vous pouvez ajuster les variables suivantes pour changer les prix de base des multiplicateurs et des auto-clickers :

javascript
Copier le code
let prixMultiplicateur = 20000;
let prixAutoClicker = 12000;
Ajouter ou Remplacer le Son
Le son est joué lorsque vous atteignez 1 000 000$. Vous pouvez remplacer le fichier audio en modifiant l'URL dans le tag <audio> de votre fichier HTML :

html
Copier le code
<audio id="score-sound" src="votre_fichier_audio.mp3"></audio>
Hébergement
Vous pouvez héberger ce projet sur une plateforme comme GitHub Pages ou Netlify. Il vous suffit de déposer votre fichier HTML (et CSS s'il est séparé) sur ces services, et un lien sera généré pour que tout le monde puisse accéder à votre jeu.

Améliorations Possibles
Voici quelques idées d'améliorations pour ce projet :

Ajout d'un système de sauvegarde : Permettre de sauvegarder l'état du jeu et le restaurer lors du prochain chargement.
Améliorer l'interface utilisateur : Ajouter des animations ou des transitions pour rendre le jeu plus interactif.
Ajouter des niveaux : Introduire des paliers où l'utilisateur doit atteindre un certain montant pour débloquer des fonctionnalités spéciales.
Ajouter un bouton de désactivation du son : Pour permettre aux utilisateurs de couper le son si nécessaire.
Technologies Utilisées
HTML : Structure de la page et des éléments.
CSS : Pour la mise en page et le style.
JavaScript : Pour la logique du jeu et l'interaction utilisateur.
Auteur
sennaio:ig
