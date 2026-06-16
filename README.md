# 📓 Bloc-note AIS — Révision (PWA)

Version installable et partageable de ton bloc-note de révision AIS/TIP.

## Contenu
- `index.html` — l'application (réseau, CIDR, Cisco, AD/DNS/DHCP, Linux, GPO, diagnostics, quiz, notes)
- `manifest.json` — métadonnées PWA (nom, icône, couleurs)
- `sw.js` — service worker (fonctionne hors-ligne une fois ouvert une première fois)
- `icon.svg` — icône de l'application

## Publier gratuitement sur GitHub Pages

1. Va sur https://github.com/new et crée un dépôt **public** (ex: `bloc-note-ais`).
2. Dans ce dossier, ouvre un terminal et exécute :
   ```
   git init
   git add .
   git commit -m "Bloc-note AIS - version PWA"
   git branch -M main
   git remote add origin https://github.com/SALIGO7/bloc-note-ais.git
   git push -u origin main
   ```
3. Sur GitHub, va dans **Settings > Pages**, choisis la branche `main` et le dossier `/ (root)`, puis **Save**.
4. Après ~1 minute, ton site est en ligne à l'adresse :
   `https://saligo7.github.io/bloc-note-ais/`
5. Partage ce lien à tes camarades. Sur mobile ou PC, ils peuvent cliquer **📲 Installer**
   (ou le menu "Ajouter à l'écran d'accueil" / "Installer l'application" du navigateur)
   pour l'avoir comme une vraie application, utilisable hors-ligne.

## Alternative sans terminal
Tu peux aussi déposer les 4 fichiers directement via l'interface web GitHub
(bouton "Add file > Upload files" sur la page du dépôt vide), sans utiliser git en ligne de commande.

## Mettre à jour le contenu plus tard
Modifie `index.html`, puis :
```
git add .
git commit -m "Mise à jour du contenu"
git push
```
Le site se met à jour automatiquement en quelques minutes.
