# Modifications par rapport au ZIP de Yassir

1. `components/EriccLab.js`: ajoute un onglet Studio V21 (sélectionné par défaut) et un iframe vers le simulateur ERICC complet.
2. `components/NaoLab.js`: ajoute un onglet Motion Lab V2.1 (sélectionné par défaut) et un iframe vers le simulateur NAO complet.
3. `app/globals.css`: styles limités au conteneur des nouveaux onglets.
4. `public/studios/`: deux fichiers HTML autonomes et intacts.
5. Aucun fichier de la page d'accueil ni de `components/three/` n'a été modifié.
6. Les moteurs `lib/ericc.js` et `lib/nao.js` sont conservés pour les anciens onglets.

Le but est de préserver le design et le code de Yassir tout en offrant les calculs et simulations personnels complets, sans réécrire leurs moteurs scientifiques.
