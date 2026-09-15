# 🎵 Les Zinzinstruments

Le tout premier projet Web en collaboration avec tous les élèves d'une classe de 2C-CI.

15 instruments à jouer en un clic, sons synthétisés en direct avec l'API Web Audio — aucun fichier audio !

## Participants

Prof : Pierre-Benjamin Monaco
Etudiant : Tarita
Etudiant : Ruben 
étudient : Dario goat

## 🧪 Ta mission

Le zoo est presque vide : il ne reste que le **piano** 🎹 et la **voix** 🗣️ (les cases grises ❓ sont les instruments inconnus qui attendent d'être créés... par toi !).

1. **Fork** ce projet (bouton « Fork » en haut à droite de GitHub)
2. Clone ton fork sur ton ordinateur
3. Copie le dossier de l'exemple : `src/instruments/piano/` → `src/instruments/mon-instrument/`
4. Renomme les 3 fichiers : `mon-instrument.html`, `mon-instrument.js`, `mon-instrument.css`
5. Modifie le bouton dans le `.html` (nom, émoji, bulle), les sons dans le `.js` et la couleur (`--hue`) dans le `.css`
6. Copie aussi le test `tests/piano.test.js` en `tests/mon-instrument.test.js` et adapte-le
7. Vérifie que tout marche : `npm install` puis `npm test`
8. Commit, push, puis ouvre une **Pull Request** vers ce dépôt 🎉

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
