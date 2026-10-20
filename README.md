# NEXUS GESTURE V3

Application web gestuelle gratuite sur Safari iPhone, esthétique hybride JARVIS / Minority Report.

## Fonctionnalités
- Contrôle de noyau énergétique (main ouverte, poing, pincement)
- Menu holographique avec modules sélectionnables
- Champ de particules animé
- Contrôle à deux mains
- Scanner visuel local expérimental : couleurs, luminosité, contraste (pas encore de reconnaissance d’objets)
- **V3 SPATIAL** : cube filaire 3D, contrôle des angles par pincement et zoom à deux mains
- **V3 VOIX** : commandes vocales françaises si le navigateur expose SpeechRecognition ; indisponible sur certains Safari et éventuellement dépendant de services du navigateur

## Déploiement
GitHub Pages avec branche `main` et workflow `.github/workflows/deploy.yml`.
Site : https://syravengroup-svg.github.io/nexus-gesture/

HTTPS et autorisation caméra nécessaires. Le modèle MediaPipe est téléchargé sur Internet. Aucune clé API payante requise. Les fonctions sont à tester sur iPhone réel.

## V4 Spatial Workspace
- Barre inférieure : NOTES, CONSOLE, FICHIERS, 3D.
- Fenêtres tactiles déplaçables et superposables ; sélection d'une fenêtre par pincement en haut du panneau.
- Notes sauvegardées sur cet iPhone dans le stockage local du navigateur.
- Console intégrée avec commandes simples (`help`, `status`, `time`, `clear`, `notes`, `spatial`).
- Explorateur local : liste les fichiers choisis sur l'iPhone, sans téléversement.
- Les fonctions V2/V3 restent intégrées. Le modèle IA de reconnaissance d'objets n'est pas inclus.
