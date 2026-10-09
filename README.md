# SOKO BUDGET

3 fichiers : `index.html`, `manifest.json`, `sw.js` (à garder dans le même dossier).

## Obtenir l'appli sur Android (gratuit)
1. Va sur app.netlify.com/drop (ou Cloudflare Pages / GitHub Pages) et glisse le dossier.
2. Ouvre le lien HTTPS sur ton téléphone avec Chrome.
3. Menu ⋮ → « Installer l'application » ou « Ajouter à l'écran d'accueil ».
4. Ouvre-la une fois avec internet : ensuite elle marche hors ligne (service worker).

## Données
Stockées sur l'appareil (IndexedDB). Réglages → Exporter JSON régulièrement. Restauration dans Réglages → Restaurer. Mode démo = base séparée.
Vider les données du navigateur efface l'appli et ses données : garde une sauvegarde.
