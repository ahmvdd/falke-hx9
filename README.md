# Falke HX-9

Vue éclatée 3D d'un drone tactique VTOL inventé. Au défilement, ses 15 sous-ensembles se remontent dans l'ordre de montage. En bas de page, un dossier de pré-dimensionnement détaille les calculs : masse, centrage, aérodynamique, rotors, batterie, structure, virages, mission.

- Rendu temps réel avec Three.js (r128) : matériaux PBR, occlusion ambiante, éclairage HDRI.
- Modèle entièrement procédural, construit en code, sans fichier 3D.
- Site statique : aucun build, `index.html` + le dossier `tex/`.

## Lancer en local

```bash
npx serve .
```

(Un serveur local est nécessaire : les textures sont chargées par `fetch`.)

## Crédits

- Matériaux scannés : [ambientCG](https://ambientcg.com) (Metal028, Metal012), licence CC0.
- Éclairage HDRI : « Empty Warehouse 01 », [Poly Haven](https://polyhaven.com), licence CC0.

Modèle et caractéristiques inventés : il ne reproduit aucun appareil existant.
