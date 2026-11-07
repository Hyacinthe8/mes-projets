# Mes projets — application web progressive (PWA)

## Contenu
- `index.html` : les trois fiches TypeScript, Java et Git/GitHub
- `manifest.webmanifest` : nom, icônes et comportement d'installation
- `sw.js` : mise en cache de l'application pour une consultation hors connexion
- `icons/` : icônes de l'application

## Publication gratuite avec GitHub Pages
1. Crée un dépôt GitHub (par exemple `mes-projets`).
2. Décompresse cette archive sur ton ordinateur.
3. Envoie **le contenu** de ce dossier à la racine du dépôt : `index.html`, `manifest.webmanifest`, `sw.js`, `icons/` et `README.md`.
4. Sur GitHub, ouvre le dépôt → **Settings** → **Pages**.
5. Dans **Build and deployment**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
6. Attends la publication. GitHub affichera une adresse du type `https://TON-PSEUDO.github.io/mes-projets/`.

## Installation sur Android (Chrome)
1. Ouvre l'adresse GitHub Pages dans Chrome sur ton téléphone.
2. Attends que la page soit complètement chargée.
3. Ouvre le menu ⋮ de Chrome.
4. Choisis **Installer l'application** ou **Ajouter à l'écran d'accueil** (le libellé dépend de la version de Chrome).
5. Confirme. L'icône **Mes projets** apparaîtra sur l'écran d'accueil.

## Hors connexion
Ouvre l'application une première fois avec Internet et laisse-la charger complètement. Le service worker met en cache les fichiers de l'application. Ensuite, les fiches déjà mises en cache peuvent être consultées hors connexion.

Pour mettre à jour l'application après avoir modifié les fichiers, republie-les sur GitHub Pages, puis ouvre l'application avec Internet. Le cache se mettra à jour lors du prochain chargement/activation du service worker.

Note : GitHub Pages doit servir le site en HTTPS pour permettre l'installation PWA et le service worker.
