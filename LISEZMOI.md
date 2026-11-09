# Site de Allège

Pages publiques de l'appli, pour la fiche App Store (iPhone et Mac).

| Page | Fichier | À utiliser pour |
|---|---|---|
| Accueil | `index.html` | URL marketing (facultatif) |
| Assistance | `assistance.html` | URL d'assistance (obligatoire) |
| Confidentialité | `confidentialite.html` | URL de politique de confidentialité (obligatoire) |

Version anglaise dans `en/` (`index.html`, `support.html`, `privacy.html`).

Site statique, sans script ni dépendance : GitHub Pages le sert tel quel
(`.nojekyll` désactive le traitement Jekyll). Style « tampon » en pastels (police Bricolage Grotesque, licence OFL),
avec un mode sombre automatique.

## Publier sur GitHub Pages

1. Créer un dépôt **public** `allege-site` sur le compte `Remy901`.
2. Envoyer les fichiers :
   ```
   git remote add origin https://github.com/Remy901/allege-site.git
   git push -u origin main
   ```
3. Sur GitHub : Settings > Pages > Source « Deploy from a branch », branche `main`, dossier `/ (root)`, Save.
4. Une ou deux minutes plus tard :
   - https://remy901.github.io/allege-site/
   - https://remy901.github.io/allege-site/assistance.html
   - https://remy901.github.io/allege-site/confidentialite.html

Chaque `git push` sur `main` met ensuite le site à jour automatiquement.
L'application ouvre déjà `assistance.html` (ou `en/support.html` en anglais)
depuis son menu « Assistance et contact ».
