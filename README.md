# DoneWithItBackend

Backend pour l'application React Native DoneWithItRN
(ce n'est pas un véritable backend connecté à une base de données.
Les données sont seulement stockées en mémoire et les données crées sont supprimées dès que l'on redémarre le serveur.
Le but étant juste de pouvoir tester l'application DoneWithItRN)

# Installation

Apres avoir cloné le projet, on va entrer dans un terminal la commande suivante : " npm i "
pour installer les dependences.

Ensuite, il va falloir se rendre dans le dossier " config " puis dans le fichier " development.json "
Ce fichier json affiche 2 settings : assetsBaseUrl et port
Il faut remplacer "[yourIpAddress]" par votre adresse ip et faire attention que votre port 9000 ne soit pas déjà utilisé

# Utilisation

node index.js
Si tout fonctionne, la console devrait afficher ce message :
" Server started on port 9000... "

# Test

Pour tester que tout va bien, on peut aller dans le navigateur et taper http://localhost:9000/api/listings
