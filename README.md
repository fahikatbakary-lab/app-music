# 🎵 DeezerVibes — Lecteur Musical

## 📌 Description
DeezerVibes est une application web de lecture musicale qui permet de rechercher des morceaux via l’API Deezer, d’écouter des extraits audio (préviews de 30 secondes) et d’explorer des artistes et titres dans une interface moderne et interactive.

## 🚀 Fonctionnalités
- 🔍 Recherche de musiques par artiste, titre ou genre
- 🎧 Lecture des previews audio (30s)
- 📀 Affichage des résultats sous forme de cartes
- 👤 Recherche des artistes et affichage de leurs titres disponibles
- ⏯️ Lecteur intégré avec :
  - Play / Pause
  - Suivant / Précédent
  - Barre de progression interactive, limitée à la durée de l’extrait
  - Contrôle du volume et sourdine
- 🎨 Interface moderne avec animations et design responsive
- ⚡ Chargement dynamique des données via API

## 🛠️ Technologies utilisées
- HTML5
- CSS3 (animations, responsive design)
- JavaScript (Vanilla JS)
- API Deezer en priorité
- Apple Search API comme secours si Deezer est inaccessible
- Requêtes directes sans proxy public

## 🌐 API utilisée
- Deezer API : https://api.deezer.com
- Apple Search API : https://itunes.apple.com/search (secours, sans clé)

## ▶️ Lancement
- Ouvrir `index.html` dans un navigateur ou utiliser l’extension Live Server de VS Code.
- Aucune clé API ni installation de dépendance n’est nécessaire.

## ⚠️ Limites audio
- Deezer et Apple Search fournissent ici des URL de prévisualisation, pas les morceaux complets; les extraits sont généralement limités à environ 30 secondes.
- La durée affichée et la recherche dans l’extrait suivent les métadonnées et capacités réelles du fichier audio.
- La disponibilité des résultats et des previews dépend du catalogue, de la région et de l’API Deezer. Certains titres peuvent être absents ou mal classés.
- Les previews sont lues directement depuis les URL fournies par Deezer; aucun proxy ou mécanisme de contournement n’est utilisé.