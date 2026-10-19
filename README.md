# NEXUS GESTURE V2

Application web de contrôle gestuel pour Safari iPhone.

## Modules
- **HOLOGRAPHIC MENU** : main ouverte pour afficher les quatre modules ; pointer puis pincer pour choisir. Les boutons sont aussi tactiles.
- **ENERGY MANIPULATION** : particules animées et champ énergétique contrôlé par la main.
- **DUAL HAND CONTROL** : deux mains détectées ; écarter/rapprocher pour zoomer et pivoter pour changer la rotation.
- **VISION SCANNER** : analyse locale expérimentale de l'image (luminosité, contraste, RGB). Pas encore de reconnaissance sémantique d'objets.

## Lancer
Ouvrir https://syravengroup-svg.github.io/nexus-gesture/ dans Safari, autoriser la caméra. La reconnaissance MediaPipe nécessite Internet au premier lancement. Aucun identifiant/API payant. Utiliser HTTPS pour la caméra.

## Déploiement
Le workflow .github/workflows/deploy.yml déploie sur GitHub Pages, si Pages et GitHub Actions sont activés dans les réglages du dépôt.

## Notes
Test à effectuer sur l'iPhone réel pour calibrer les seuils de gestes. La vidéo est traitée localement dans le navigateur.
