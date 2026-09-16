# 🎵 Les Zinzinstruments

Le tout premier projet Web en collaboration avec tous les élèves d'une classe de 2C-CI.

15 instruments à jouer en un clic, sons synthétisés en direct avec l'API Web Audio — aucun fichier audio !

## Participants

Profs : 
  - Pierre-Benjamin Monaco

Etudiants : 

## 🧪 Ta mission

Le zoo est presque vide : il ne reste que le **piano** 🎹 et la **voix** 🗣️ (les cases grises ❓ sont les instruments inconnus qui attendent d'être créés... par toi !).

1. Clone ce dépôt sur ton ordinateur.
2. Crée une branche personnelle à partir de main :
   git switch -c mon-instrument
3. Copie le dossier de l’exemple : src/instruments/piano/ vers src/instruments/mon-instrument/
4. Renomme les 3 fichiers : mon-instrument.html, mon-instrument.js, mon-instrument.css
5. Modifie le bouton dans le fichier HTML (nom, émoji, bulle), les sons dans le fichier JS et la couleur (--hue) dans le fichier CSS.
7. Vérifie que tout fonctionne :
   npm install
   npm test
8. Committe tes modifications, puis pousse ta branche :
   git add .
   git commit -m "Ajoute mon instrument"
   git push -u origin mon-instrument
9. Ouvre une Pull Request de ta branche vers main dans ce dépôt.
10. Travaille uniquement dans ta branche personnelle et ne modifie pas directement main.

Ton instrument remplacera automatiquement sa case ❓ dès que ton PR sera accepté !

## ▶️ Lancer le site

```bash
npm install
npm run dev
```

## 🧪 Lancer les tests

```bash
npm test
```

Chaque test qui échoue t'explique en français quoi corriger !
